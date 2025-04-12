# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
- **Primer segmento: Usuarios que desean alquilar bicicletas (arrendatarios)**
- **Segundo segmento: Usuarios que ofrecen sus bicicletas en alquiler (arrendadores)**
## 3.2. User Stories
A continuación se presentan las épicas que describen las funcionalidades clave para la aplicación web.
| Epic ID | Título | Descripcion |
|--------|--------|------|
|EP01 |Implementación de Landing page | Como visitante quiero poder visualizar las diferentes características de la plataforma en su landing page para conocer información y acceder a la aplicación web de la misma
|EP02|Gestion de cuenta|Como usuario quiero crear una cuenta y acceder a la plataforma, para realizar alquileres o publicar mis bicicletas 
|EP03|Gestión de bicicletas para arrendatarios|Como arrendatario quiero registrar y gestionar mi bicicleta para poder ofrecerla en alquiler
|EP04|Alquiler para usuarios|Como arrendador quiero encontrar, reservar y pagar mi bicicleta, para tener una forma de transporte alternativa
|EP05|Seguridad y soporte|Como usuario quiero sentirme seguro durante el uso de la plataforma para usarla de forma recurrente
|EP06|Suscripción Premium|Como usuario premium quiero acceder a beneficios adicionales para tener ventajas y descuentos

Para asegurar que se desarrollen funcionalidades específicas que el usuario necesita, las siguientes user stories han sido definidas. Cada una de estas historias será implementada y validada durante el desarrollo.  

| ID User Story | Título | Descripción | Criterios de aceptación | ID Epic |
|---------------|--------|-------------|-------------------------|---------|
|US01|Barra de navegación en la Landing Page|Como usuario quiero una barra de navegación en la parte superior para acceder a las secciones de la  landing page|Scenario: Navegación entre secciones internas <br> Dado que el visitante ve la barra de navegación <br>Cuando hace clic en cada sección <br>Entonces la página hace scroll hacia la sección correspondiente|EP01|
|US02|Sección de Beneficios	|Como visitante, quiero ver una sección con los beneficios y servicios que ofrece la plataforma, para decidir si me interesa usarla|Scenario: Mostrar beneficios de la plataforma <br> Dado que el visitante está en la landing page <br>Cuando hace clic en la sección con el título "Beneficios" <br>Entonces se muestran los servicios y beneficios que ofrece la solución web|EP01|
|US03|Sección “Sobre nosotros”|Como visitante, quiero saber quiénes están detrás de la plataforma y cuál es su misión, para generar confianza|Scenario: Mostrar información sobre la startup o equipo <br> Dado que el visitante está en la landing page <br>Cuando hace clic en la sección con el título "Sobre nosotros"<br>Entonces se muestra una breve descripción de la misión del proyecto e información del equipo|EP01|
|US04|Sección de contacto|Como usuario, quiero poder contactar al equipo de soporte o atención al cliente desde la landing, para resolver dudas o problemas|Scenario: Visualizar medios de contacto<br>Dado que el visitante está en la landing page<br>Cuando hace clic en la sección con el título "Contacto"<br>Entonces se muestra una dirección de correo o redes sociales|EP01|
|US05|Botones de acción|Como visitante, quiero ver botones que me inviten a registrarme o buscar bicicletas, para poder interactuar rápidamente|Scenario:Botones visibles al entrar<br>Dado que el visitante está en la landing page<br>Cuando hace clic en un botón con el texto "Registrarme" o "Buscar bicicletas"<br>Entonces se redirige a la aplicación web|EP01|

## 3.3. Impact Mapping
## 3.4. Product Backlog