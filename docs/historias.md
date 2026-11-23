# Historias de usuario — OsintKit

## HU-01 · Iniciar sesión

**Como** Analista / Auditor  
**Quiero** ingresar mi correo institucional y contraseña  
**Para** autenticarme de forma segura, entrar al dashboard y asociar mis análisis a mi perfil.

**Criterios de aceptación**

1. Validar que correo y contraseña no estén vacíos.
2. Verificar formato válido de correo.
3. Mostrar mensaje de error si las credenciales son incorrectas.
4. Generar sesión vinculada al id_analista.

**Prioridad:** Must

---

## HU-02 · Registro de usuarios

**Como** Analista Junior / usuario nuevo  
**Quiero** registrar nombre, correo, rol y aceptar términos  
**Para** crear una cuenta y obtener credenciales de acceso.

**Criterios de aceptación**

1. Verificar que el correo no esté registrado.
2. Permitir elegir rol (Analista Junior, Auditor, Administrador).
3. Bloquear el registro si no se aceptan los términos.

**Prioridad:** Must

---

## HU-03 · Búsqueda de nicknames y correos

**Como** Analista OSINT  
**Quiero** ingresar un alias, username o correo y seleccionar fuentes  
**Para** rastrear la presencia digital del objetivo.

**Criterios de aceptación**

1. Sanitizar el texto ingresado antes de consultar.
2. Mostrar indicador de carga mientras se consultan las fuentes.
3. Presentar resultados en tarjetas con estado (Confirmado, Probable, Filtrado).

**Prioridad:** Must

---

## HU-04 · Auditoría de dominios e IP

**Como** Auditor de ciberseguridad  
**Quiero** ingresar un dominio o dirección IP  
**Para** consultar WHOIS, registros DNS y geolocalización.

**Criterios de aceptación**

1. Validar el formato del dominio o IP.
2. Mostrar datos por secciones (WHOIS, DNS, geolocalización).
3. Ofrecer botón para guardar los resultados.

**Prioridad:** Must

---

## HU-05 · Extracción de metadatos

**Como** Analista OSINT  
**Quiero** cargar un archivo (imagen o PDF)  
**Para** extraer metadatos técnicos y EXIF.

**Criterios de aceptación**

1. Validar tipo y tamaño máximo del archivo.
2. Presentar los metadatos en una tabla legible.
3. Incluir opción de limpiar metadatos y generar copia segura.

**Prioridad:** Must

---

## HU-06 · Generación de reportes

**Como** Analista / Administrador  
**Quiero** exportar hallazgos en PDF o JSON  
**Para** presentar reportes o integrar datos con otras herramientas.

**Criterios de aceptación**

1. Solo permitir generar reporte si hay resultados previos.
2. Generar PDF con marca del sistema, fecha y analista.
3. Generar JSON descargable.

**Prioridad:** Must

---

## HU-07 · Historial de consultas

**Como** Analista OSINT  
**Quiero** ver el listado de mis búsquedas, análisis y extracciones anteriores  
**Para** retomar investigaciones sin repetir consultas.

**Criterios de aceptación**

1. Mostrar fecha, tipo de consulta y objetivo.
2. Permitir filtrar por tipo (usuario, dominio, metadatos).
3. Solo mostrar registros del analista autenticado.

**Prioridad:** Must

---

## HU-08 · Recuperar / cambiar contraseña

**Como** Analista  
**Quiero** recuperar el acceso o cambiar mi contraseña  
**Para** mantener segura mi cuenta.

**Criterios de aceptación**
1. Solicitar el correo registrado para recuperación.
2. Exigir contraseña actual al cambiarla desde el perfil.
3. Mostrar mensaje de confirmación al completar el cambio.

**Prioridad:** Should
