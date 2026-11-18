# Política de privacidad de la aplicación «Cerebro»

Última actualización: 18 de noviembre de 2026.

## 1. Responsable

La aplicación «Cerebro» es desarrollada y operada por Sebastián Estol, arquitecto, con domicilio en Joaquín Suárez, departamento de Canelones, Uruguay. Correo electrónico de contacto: estolsebastian@gmail.com.

## 2. Naturaleza de la aplicación

«Cerebro» es una herramienta de uso estrictamente personal: su único usuario es el propio responsable, quien la emplea para integrar información de su cuenta de Google en su sistema personal de gestión del conocimiento. La aplicación no está abierta al público, no admite el registro de terceros y no presta servicio alguno a otras personas.

## 3. Datos a los que accede

Mediante el protocolo OAuth 2.0 de Google, la aplicación solicita únicamente los alcances (scopes) que se enumeran a continuación, cada uno con su finalidad. Con `openid` y `https://www.googleapis.com/auth/userinfo.email` identifica la cuenta de Google que otorga la autorización. Con `https://www.googleapis.com/auth/gmail.readonly` lee, en modo de solo lectura, los mensajes de correo electrónico para extraer plazos, observaciones, expedientes y antecedentes hacia el sistema de notas; no envía, modifica ni elimina correos. Con `https://www.googleapis.com/auth/drive.readonly` lee, en modo de solo lectura, los archivos de Google Drive para indexarlos y consultarlos desde el sistema. Con `https://www.googleapis.com/auth/drive.file` crea y edita en Google Drive únicamente los archivos que la propia aplicación genera, sin acceso de escritura al resto. Con `https://www.googleapis.com/auth/calendar.events` lee y crea eventos de calendario para registrar vencimientos, visitas y plazos. No se solicitan alcances distintos de los enumerados; en particular, la aplicación no solicita acceso completo al buzón de correo ni a la totalidad de Google Drive.

## 4. Finalidad del tratamiento

Los datos obtenidos se utilizan exclusivamente para consultarlos, organizarlos e incorporarlos al sistema personal de notas y documentación del propio usuario. No se emplean con fines publicitarios, comerciales, de perfilado ni de entrenamiento de modelos de inteligencia artificial.

## 5. Almacenamiento y conservación

La información se procesa en los equipos y en el almacenamiento privado del responsable. Los tokens de acceso se guardan de forma local y protegida, y pueden eliminarse en cualquier momento. Los datos se conservan solo mientras resultan útiles a la finalidad indicada.

## 6. Comunicación a terceros

Los datos de usuario de Google no se venden, ceden, transfieren ni comparten con terceros, salvo que una norma legal lo exija.

## 7. Cumplimiento de la Política de datos de usuario de los servicios de API de Google

El uso y la transferencia de la información recibida de las API de Google por parte de «Cerebro» se ajustan a la Política de datos de usuario de los servicios de API de Google (Google API Services User Data Policy), incluidos los requisitos de uso limitado (Limited Use).

## 8. Revocación del acceso

El usuario puede revocar en cualquier momento el acceso concedido a la aplicación desde la configuración de seguridad de su cuenta de Google (https://myaccount.google.com/permissions). Revocado el acceso, la aplicación deja de poder obtener datos nuevos.

## 9. Cambios

Cualquier modificación de esta política se publicará en esta misma dirección, con indicación de la fecha de actualización.

## 10. Contacto

Para consultas sobre esta política: estolsebastian@gmail.com.
