- INSTALAR TRYTONDD, TRYTON EN SUS VERSIONES 6.0 Y TRYTON_SALES (DE PREFERENCIA INICIAR CON ENTORNO VIRTUAL)
- INSTALAR POSTGRESQL
- CREAR UN ARCHIVO trytond.config en una ruta y agregar la sigueinte linea:
[database]
uri = postgresql://<usuario>:<contraseña>@localhost:5432/

- IMPORTAR LA BASE DE DATOS DE TRYTON_SALES CON "trytond-admin -d <nombre_db> --all"

- PARA INICIAR EL SERVIDOR TRYTOND SE DEBE DE ESCRIBIR EN LA CONSOLA: "trytond -c /ruta/del/archivo/trytond.config"

- LUEGO INICIAR TRYTON , ELEGIR EL SERVIDOR DE TRYTOND (POR DEFECTO ES LOCALHOST:8000)

- NOTA : COMO ESTAMOS EN UN ENTORNO VIRTUAL, AL CREAR UN MODULO, DEBEMOS IR A LA RUTA <nombre_entorno>/lib/python3.12/site-packages/trytond/modules/
- NOTA: SI SE CREO UN NUEVO MODULO, ENTONCES DEBERIA DE EJECUTAR EL ANTERIOR CODIGO DE trytond-admin
