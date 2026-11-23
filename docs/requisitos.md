# Requisitos funcionales — OsintKit

| Código | Descripción                                                                          | HU de origen        | Prioridad |
| ------ | ------------------------------------------------------------------------------------ | ------------------- | --------- |
| RF-01  | El sistema debe autenticar al usuario con correo y contraseña                        | HU-01               | Must      |
| RF-02  | El sistema debe permitir el registro de nuevos usuarios con validación de datos      | HU-02               | Must      |
| RF-03  | El sistema debe buscar nicknames y correos en fuentes abiertas seleccionadas         | HU-03               | Must      |
| RF-04  | El sistema debe consultar WHOIS, DNS y geolocalización de dominios o IP              | HU-04               | Must      |
| RF-05  | El sistema debe extraer metadatos de archivos cargados por el analista               | HU-05               | Must      |
| RF-06  | El sistema debe generar reportes en PDF y JSON a partir de resultados guardados      | HU-06               | Must      |
| RF-07  | El sistema debe listar el historial de consultas del analista autenticado            | HU-07               | Must      |
| RF-08  | El sistema debe permitir recuperar o cambiar la contraseña del usuario               | HU-08               | Should    |
| RF-09  | El sistema debe asociar cada búsqueda, análisis, extracción y reporte al id_analista | HU-01               | Must      |
| RF-10  | El sistema debe mostrar estados de carga durante consultas a fuentes externas        | HU-03, HU-04, HU-05 | Must      |
