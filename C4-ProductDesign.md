# CAPÍTULO IV: Product Design
Gracias al Product Design **adoptamos un enfoque de diseño centrado en el usuario**, lo cual nos permitirá desarrollar productos y servicios funcionales, atractivos y alineados con las expectativas del cliente. Esta metodología será clave para resolver desafíos específicos, aportar valor tangible a nuestros usuarios y avanzar de forma más efectiva hacia nuestras metas comerciales.

## 4.1. Style Guidelines
Los **Style Guidelines** son una guía que reúne las directrices para asegurar un diseño y presentación coherente de sitios web y software.A continuación, se presentan los parámetros aplicados para el desarrollo del proyecto.

### 4.1.1. General Style Guidelines
**Branding** <br>
Al momento de crear el logo de BikeShare, se optó por un modelo minimalista que refleja nuestro compromiso de brindar un servicio de transporte accesible. Se utilizaron colores suaves, lo que permite que el usuario identifique fácilmente el logo y lo mantenga reconocible. <br>

<img src="images/bikeshare-logo.png" alt="Brand Logo"> <br>

**Typography** <br>
Para la tipografía de BikeShare, se eligió una fuente elegante y funcional que complementa la imagen general de la aplicación. La tipografía principal es **Roboto**, una fuente que ofrece excelente legibilidad en dispositivos móviles y proporciona un toque moderno y profesional al diseño. Para generar contraste en los textos importantes, se optó por **Roboto Slab**, una fuente llamativa que destaca la información clave y capta la atención del usuario. <br>

<img src="images/Roboto.png" alt="Roboto">
<img src="images/RobotoSlab.png" alt="RobotoSlab"> <br>

**Colors** <br>
La paleta de colores de BikeShare está compuesta por tonos que evocan vitalidad, tranquilidad y motivación, alineados con un estilo de vida activo y equilibrado. Los colores seleccionados son brillantes y estimulantes, permitiendo captar la atención del usuario y reflejar la esencia de un producto innovador y lleno de energía. <br>
 ![Alt Text](images/Colors.png)

**Spacing** <br>
El espaciado desempeña un papel fundamental en el diseño de BikeShare, ya que organiza la información de forma clara y coherente.Se aplicó una separación amplia entre los elementos de la interfaz para mejorar la legibilidad y facilitar la navegación del usuario. Asimismo, se mantuvo un espaciado constante en todo el diseño, aportando equilibrio y armonía a la composición.

Ejemplo de espaciado:

<img src="images/Spacing.png" alt="Spacing">

### 4.1.2. Web Style Guidelines
Para el desarrollo de la plataforma web se decidió implementar **Responsive Web Design**, permitiendo que la plataforma se adapte a cualquier dispositivo. Gracias a ello, el contenido se mantiene intacto, mejorando la presentación y la experiencia del usuario. Se optó por utilizar **Material Design**, ya que se enfoca en elementos clave y dirige la atención del usuario hacia los aspectos más importantes de la página.

**Icons** <br>
Se garantiza la consistencia y legibilidad de los íconos, asegurando que expresen claramente sus funciones y características esenciales.

<img src="images/Icons.png" alt="Icons">

**Scale** <br>
Se utilizará un rango de 7 tipos de esquinas en las figuras:
- None
- Extra Small
- Small
- Medium
- Large
- Extra Large
- Full

> <img src="images/Shape.png" alt="Shape">

### 4.1.3. Mobile Style Guidelines
Para el desarrollo de la versión móvil, se continuará utilizando **Material Design** para mantener la uniformidad entre la plataforma web y móvil.

**Transitions** <br>
Se aplicarán transiciones que permitan una experiencia cohesiva y predecible durante el uso de la plataforma.

<img src="images/Transition.png" alt="Transition">

## 4.2. Information Architecture
> En este apartado se detallarán el contenido visual y las etiquetas que se usarán en la elaboración del Landing Page y de la Página Web. Se revisarán tópicos como Labelling Systems, Organization Systems, SEO, Meta Tags, y Searching y Navigation Systems.

### 4.2.1. Organization Systems
**Home** <br>
| Tópico | Definición |
|----------|----------|
| Home | Sección principal donde se mostrará una descripción del servicio, sus características y el proceso de funcionamiento de la plataforma. |
| Our System | Sección donde se explicará cómo alquilar bicicletas. |
| Be a Partner | Sección donde se presentarán los beneficios para los arrendadores de bicicletas. |
| Reviews | Sección donde se mostrarán las opiniones de arrendadores y usuarios. |
| Log In | Sección de registro e inicio de sesión en la plataforma. |

**Our System** <br>
| Tópico | Definición |
|----------|----------|
| How to Rent a Bike | Pasos para alquilar una bicicleta a través de la plataforma. |

**Be a Partner** <br>
Sección que muestra las características y beneficios para arrendadores.

**Reviews** <br>
Sección que muestra los comentarios y opiniones de arrendadores y clientes sobre la plataforma.

**Log In** <br>
| Tópico | Definición |
|----------|----------|
| Log In | Autenticación de credenciales de perfiles existentes. |
| Sign Up | Registro de nuevos usuarios, tanto arrendadores como clientes. |

**Responsive Design** <br>
Permitirá una experiencia fluida y adaptable en diferentes dispositivos.

### 4.2.2. Labeling Systems
Se decidió usar etiquetas para organizar las secciones de la plataforma web, permitiendo un acceso más rápido y ordenado.

| Tópico | Definición |
|----------|----------|
| Home | Sección principal de descripción general. |
| Our System | Información sobre cómo alquilar bicicletas. |
| Be a Partner | Información para arrendadores. |
| Reviews | Opiniones de usuarios y arrendadores. |
| Log In | Acceso y registro de usuarios. |

### 4.2.3. SEO Tags and Meta Tags
Las Meta Tags permiten codificar y detallar los metadatos de la página web, facilitando su lectura y análisis por parte de los navegadores, aunque no son visibles para los usuarios.

**Título** <br>
Influye en el posicionamiento dentro de los motores de búsqueda.  
`<title>Rent bikes with us - BikeShare</title>`

**Codificación de caracteres** <br>
Se utilizó **UTF-8** por su eficiencia para caracteres del Plano Multilingüe Básico (BMP).  
`<meta charset="utf-8">`

**Descripción** <br>
Breve descripción para buscadores.  
`<meta name="description" content="BikeShare is a web app that helps you rent bikes around Lima."/>`

**Palabras clave** <br>
Facilitan la asociación temática en buscadores.  
`<meta name="keywords" content="bike, rent, lend, smart, save"/>`

**Autor y derechos de autor** <br>
Protección de la propiedad intelectual.  
`<meta name="author" content="BikeShare Team"/>`  
`<meta name="copyright" content="Copyright BikeShare Team"/>`

### 4.2.4. Searching Systems
El **Searching System** es fundamental para que los usuarios encuentren la información que buscan.

**Características clave:**
- **Búsqueda por distrito:** Buscar bicicletas en distritos específicos.
- **Búsqueda por disponibilidad:** Buscar bicicletas disponibles en estaciones específicas.
- **Búsqueda por calificación:** Filtrar estaciones por puntuación de usuarios.

### 4.2.5. Navigation Systems
El **Navigation System** permitirá a los usuarios desplazarse fácilmente por las secciones de la plataforma.

**Estructura de navegación:**
- Home
- Our System
- Be a Partner
- Reviews
- Log In

## 4.3. Landing Page UI Design
El diseño de la **Landing Page** es crucial, ya que será la primera impresión de nuestro producto. Debemos crear una experiencia que capte la atención de los usuarios y los incentive a regresar.

### 4.3.1. Landing Page Wireframe
**Web Version - Home Page**  
Sección principal que presenta el servicio.

<img src="images/Wireframe-HomePage.png" alt="HomePage">

**Web Version - Our System**  
Explicación de cómo alquilar bicicletas.

<img src="images/Wireframe-OurSystem.png" alt="OurSystem">

**Web Version - Be a Partner**  
Información para arrendadores.

<img src="images/Wireframe-BeAPartner.png" alt="BeAPartner">

**Web Version - Reviews**  
Opiniones de usuarios.

<img src="images/Wireframe-Reviews.png" alt="Reviews">

**Mobile Web Version - Home Page**

<img src="images/Wireframe-MobileHomePage.png" alt="Wireframe-MobileHomePage">

**Mobile Web Version - Our System**

<img src="images/Wireframe-MobileOurSystem.png" alt="Wireframe-MobileOurSystem">

**Mobile Web Version - Be a Partner**

<img src="images/Wireframe-MobileBeaPartner.png" alt="Wireframe-MobileBeaPartner">

**Mobile Web Version - Reviews**

<img src="images/Wireframe-MobileReviews.png" alt="Wireframe-MobileReviews">

### 4.3.2.Landing Page Mock-up
**Web Version - Home Page**  
Sección principal que presenta el servicio.

<img src="images/MockUp-Home.png" alt="HomePage">

**Web Version - Our System**  
Explicación de cómo alquilar bicicletas.

<img src="images/MockUo-OurSystem.png" alt="OurSystem">

**Web Version - Be a Partner**  
Información para arrendadores.

<img src="images/MockUp-BePartner.png" alt="BeAPartner">

**Web Version - Reviews**  
Opiniones de usuarios.

<img src="images/MockUp-Reviews.png" alt="Reviews">

## 4.4.Web Applications UX/UI Design
### 4.4.1.Web Applications Wireframes
**Web Version - Login**  
<img src="images/Wireframes-Login.png" alt="Login">
<img src="images/Wireframes-Login2.png" alt="Login">

**Web Version - Sing Up**  
<img src="images/Wireframes-Singup.png" alt="SingUP">

**Web Version - Home**  
<img src="images/Wireframes-Home.png" alt="Home">

**Web Version - Map**  
<img src="images/Wireframes-Map.png" alt="Map">

**Web Version - Profile**  
<img src="images/Wireframes-Profile.png" alt="Profile">

**Web Version - Home Arrendatario**  
<img src="images/Wireframes-HomeArr.png" alt="Home">

**Web Version - Addbike Arrendatario**  
<img src="images/Wireframes-MyBike.png" alt="Addbike">

### 4.4.2.Web Applications Wireflow Diagrams

<img src="images/Wireflow1.PNG" alt="wireflow">

User Goals:<br>
Inicio de sesión<br>
Como usuario registrado, quiero poder iniciar sesión con mis credenciales para acceder a mi cuenta y funcionalidades.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Selección de rol<br>
Como usuario, quiero poder elegir si quiero registrarme como arrendador o arrendatario desde la pantalla principal para que la plataforma me dirija a la pantalla de registro correspondiente.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Edición de datos personales<br>
Como usuario, quiero poder actualizar mi perfil y datos personales para mantener mi información actualizada.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Cierre de sesión<br>
Como usuario, quiero cerrar sesión de forma segura para proteger mi cuenta cuando dejo de usar la plataforma.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Edición de información de una bicicletaa<br>
Como arrendador, quiero editar la información de mis bicicletas para actualizar detalles.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Eliminación de una bicicleta<br>
Como arrendador, quiero eliminar bicicletas que ya no deseo alquilar para mantener mi listado limpio y actualizado.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Historial de alquileres<br>
Como arrendador, quiero visualizar un historial de alquileres de mis bicicletas para conocer la demanda y evaluar ingresos.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Visualización de estadísticas de uso<br>
Como arrendador, quiero visualizar estadísticas de uso e ingresos generados por mis bicicletas para tomar mejores decisiones sobre mi oferta.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Configuración de disponibilidad<br>
Como arrendador, quiero establecer días y horas disponibles para cada bicicleta para evitar reservas en momentos no deseados.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Búsqueda de bicicletas por ubicación y disponibilidad<br>
Como arrendatario, quiero buscar bicicletas disponibles según mi ubicación y horario deseado para encontrar opciones convenientes.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Visualización de detalles de bicicletas<br>
Como arrendatario, quiero ver información detallada de cada bicicleta incluyendo reseñas antes de alquilarla para tomar una decisión informada.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Alquiler de bicicleta	<br>
Como arrendatario, quiero poder reservar una bicicleta por un periodo específico para utilizarla según mi necesidad.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Gestión de alquileres		<br>
Como arrendatario, quiero ver mis alquileres actuales y pasados para gestionar el uso y control de mis reservas.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

### 4.4.3.Web Applications Mock-ups

**Web Version - Login**  
<img src="images/Mockup-login.PNG" alt="Login">
<img src="images/Mockup-login2.PNG" alt="Login">

**Web Version - Sing Up**  
<img src="images/Mockup-singup.PNG" alt="SingUP">

**Web Version - Home**  
<img src="images/Mockup-home.PNG" alt="Login">

**Web Version - Map**  
<img src="images/Mockup-map.PNG" alt="SingUP">

**Web Version - Profile**  
<img src="images/Mockup-profile.PNG" alt="SingUP">

### 4.4.4.Web Applications User Flow Diagrams
<img src="images/Wireflow1.PNG" alt="wireflow">

User Goals:<br>
Inicio de sesión<br>
Como usuario registrado, quiero poder iniciar sesión con mis credenciales para acceder a mi cuenta y funcionalidades.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Selección de rol<br>
Como usuario, quiero poder elegir si quiero registrarme como arrendador o arrendatario desde la pantalla principal para que la plataforma me dirija a la pantalla de registro correspondiente.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Edición de datos personales<br>
Como usuario, quiero poder actualizar mi perfil y datos personales para mantener mi información actualizada.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Cierre de sesión<br>
Como usuario, quiero cerrar sesión de forma segura para proteger mi cuenta cuando dejo de usar la plataforma.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Edición de información de una bicicletaa<br>
Como arrendador, quiero editar la información de mis bicicletas para actualizar detalles.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Eliminación de una bicicleta<br>
Como arrendador, quiero eliminar bicicletas que ya no deseo alquilar para mantener mi listado limpio y actualizado.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Historial de alquileres<br>
Como arrendador, quiero visualizar un historial de alquileres de mis bicicletas para conocer la demanda y evaluar ingresos.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Visualización de estadísticas de uso<br>
Como arrendador, quiero visualizar estadísticas de uso e ingresos generados por mis bicicletas para tomar mejores decisiones sobre mi oferta.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Configuración de disponibilidad<br>
Como arrendador, quiero establecer días y horas disponibles para cada bicicleta para evitar reservas en momentos no deseados.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Búsqueda de bicicletas por ubicación y disponibilidad<br>
Como arrendatario, quiero buscar bicicletas disponibles según mi ubicación y horario deseado para encontrar opciones convenientes.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Visualización de detalles de bicicletas<br>
Como arrendatario, quiero ver información detallada de cada bicicleta incluyendo reseñas antes de alquilarla para tomar una decisión informada.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Alquiler de bicicleta	<br>
Como arrendatario, quiero poder reservar una bicicleta por un periodo específico para utilizarla según mi necesidad.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

Gestión de alquileres		<br>
Como arrendatario, quiero ver mis alquileres actuales y pasados para gestionar el uso y control de mis reservas.<br>
<img src="images/Wireflow1.PNG" alt="wireflow">

## 4.5.Web Applications Prototyping



## 4.6.Domain-Driven Software Architecture
En esta seccion se presentaran los tres niveles del modelo C4 aplicando Domain Driven Design.

### 4.6.1.Software Architecture Context Diagram.
El diagrama de contexto nos muestra los tipos de usuario que interactuan con el aplicativo web, y a la vez los servicios y/o con los que la plataforma interactua.  <br>
<img src="images/structurizr-101334-Context.png" alt="ContextDiagram"> <br>
### 4.6.2.Software Architecture Container Diagrams. <br>
Este diagrama nos permite tener una vision enfocada al desarrollo. Se muestra la forma en la que los usuarios interactuan con la Landing Page, Web App y Mobile App. A la vez que se muestra como estas plataformas interactuan con los servicios externos vinculados. <br>

<img src="images/structurizr-101334-Contenedor.png" alt="ContainerDiagram"> <br>
### 4.6.3.Software Architecture Components Diagrams. <br>
En esta seccion se muestra los diagramas de comppnentes de cada uno de los bounded contexts definidos. <br>
**APIRest - Component** <br>
<img src="images/structurizr-101334-API Rest Component Diagram.png" alt="APIRest"> <br>
**Geolocation - Component** <br>
<img src="images/structurizr-101334-GeoLocation.png" alt="Booking"> <br>
**Bike Inventory - Component** <br>
<img src="images/structurizr-101334-Bike Inventory BC Component Diagram.png" alt="Booking"> <br>
**Lender Management - Component** <br>
<img src="images/structurizr-101334-Bike Owner BC Component Diagram.png" alt="LocationRouting"> <br>
**Bike Rental - Component** <br>
<img src="images/structurizr-101334-Bike Rental BC Component Diagram.png" alt="Notification"> <br>
**Notification - Component** <br>
<img src="images/structurizr-101334-Notification BC Component Diagram.png" alt="Payment"> <br>
**Review - Component** <br>
<img src="images/structurizr-101334-Review BC Component Diagram.png" alt="Review"> <br>
**Payment - Component** <br>
<img src="images/structurizr-101334-Payment BC Component Diagram.png" alt="Scheduling"> <br>
**User Management - Component** <br>
<img src="images/structurizr-101334-User Management BC Component Diagram.png" alt="ServiceCatalog"> <br>

## 4.7.Software Object-Oriented Design.
### 4.7.1.Class Diagrams
**General Diagram** <br>
<img src="images/ClassDiagram.png" alt="ClassDiagram"> <br>
**Geolocation - Component** <br>
<img src="images/ClassDiagram-Geolocation.png" alt="APIRest"> <br>
**Bike Inventory - Component** <br>
<img src="images/ClassDiagram-BikeInventory.png" alt="Booking"> <br>
**Lender Management - Component** <br>
<img src="images/ClassDiagram-LenderManagement.png" alt="LocationRouting"> <br>
**Bike Rental - Component** <br>
<img src="images/ClassDiagram-Rental.png" alt="Notification"> <br>
**Notification - Component** <br>
<img src="images/ClassDiagram-Notification.png" alt="Payment"> <br>
**Review - Component** <br>
<img src="images/ClassDiagram-Review.png" alt="Review"> <br>
**Payment - Component** <br>
<img src="images/ClassDiagram-Payment.png" alt="Scheduling"> <br>
**User Management - Component** <br>
<img src="images/ClassDiagram-UserManagement.png" alt="ServiceCatalog"> <br>

### 4.7.2.Class Dictionary.
#### User Management BC

#### User

- userId: Identificador único del usuario.

- email: Correo electrónico.

- passwordHash: Contraseña cifrada.

- fullName: Nombre completo del usuario.

- role: Indica si el usuario es CLIENT o LENDER.

#### UserRole (enum)

- CLIENT: Usuario que alquila bicicletas.

- LENDER: Usuario que presta sus bicicletas a la plataforma.

#### AuthService

login(email, password): Autentica a un usuario y retorna un AuthToken.

register(userData): Registra un nuevo usuario.

resetPassword(email): Inicia el proceso de restablecimiento de contraseña.

#### Bike Inventory BC

#### Bike

bikeId: Identificador único de la bicicleta.

ownerId: Identificador del propietario (LENDER).

model: Modelo de la bicicleta.

type: Tipo de bicicleta (ROAD, MOUNTAIN, etc.).

location: Coordenadas geográficas actuales.

status: Estado operativo actual de la bicicleta.

#### BikeType (enum)

ROAD, MOUNTAIN, ELECTRIC, HYBRID: Tipos de bicicletas.

#### BikeStatus (enum)

AVAILABLE, IN_USE, RESERVED, MAINTENANCE: Estados operacionales posibles.

#### GeoPoint

latitude: Latitud geográfica.

longitude: Longitud geográfica.

#### InventoryService

registerBike(bikeData): Registra una bicicleta en el sistema.

updateBikeLocation(bikeId, GeoPoint): Actualiza la ubicación de la bicicleta.

setBikeStatus(bikeId, status): Cambia el estado operativo.

getAvailableBikes(location, radius): Devuelve bicicletas disponibles cercanas.

#### Rental Operations BC

#### Rental

rentalId: Identificador único del alquiler.

bikeId: Bicicleta alquilada.

clientId: Cliente que realiza el alquiler.

startTime: Fecha y hora de inicio.

endTime: Fecha y hora de fin.

status: Estado del alquiler.

price: Precio del alquiler.

#### RentalStatus (enum)

ONGOING, COMPLETED, CANCELLED: Estados posibles del alquiler.

#### RentalService

startRental(bikeId, clientId): Inicia un nuevo alquiler.

endRental(rentalId): Finaliza el alquiler.

calculatePrice(rentalId): Calcula el precio del alquiler.

#### Lender Management BC

#### LenderProfile

lenderId: Identificador del LENDER (igual que userId).

bio: Descripción o biografía del lender.

totalEarnings: Total acumulado de ingresos por alquileres.

rating: Calificación promedio basada en reviews.

#### LenderService

getLenderDashboard(lenderId): Retorna métricas del lender.

listBikes(lenderId): Lista las bicicletas del lender.

#### DashboardData

earnings: Dinero ganado por el lender.

activeBikes: Número de bicicletas disponibles.

totalRentals: Total de alquileres completados.

#### Payment & Billing BC

#### Payment

paymentId: Identificador del pago.

rentalId: Alquiler asociado al pago.

userId: Usuario que realiza el pago.

amount: Cantidad pagada.

timestamp: Fecha y hora del pago.

status: Estado actual del pago.

#### PaymentStatus (enum)

PENDING, COMPLETED, FAILED: Posibles estados del pago.

#### BillingService

processPayment(userId, rentalId): Procesa el pago de un alquiler.

refundPayment(paymentId): Procesa la devolución.

generateInvoice(userId): Genera la factura del usuario.

#### Invoice

invoiceId: Identificador de la factura.

userId: Usuario asociado.

amount: Total facturado.

issuedDate: Fecha de emisión.

lineItems: Detalle de cargos.

#### Geolocation & Navigation BC

#### GeoService

getNearbyBikes(location, radius): Encuentra bicicletas cercanas.

trackBike(bikeId): Retorna ubicación actual de la bicicleta.

getParkingZones(): Devuelve zonas de aparcamiento disponibles.

#### GeoZone

zoneId: Identificador único de la zona.

coordinates: Coordenadas que definen la zona.

#### Review & Feedback BC

#### Review

reviewId: Identificador del review.

reviewerId: Usuario que hizo la review.

targetUserId: Usuario evaluado.

rating: Puntaje (por ejemplo, del 1 al 5).

comment: Comentario del usuario.

submittedAt: Fecha de envío.

#### ReviewService

submitReview(reviewerId, targetUserId, rating, comment): Crea un review.

getUserReviews(userId): Obtiene reviews de un usuario.

#### Notification BC

#### Notification

notificationId: Identificador de la notificación.

userId: Destinatario.

message: Contenido del mensaje.

type: Categoría de notificación.

createdAt: Fecha de creación.

#### NotificationType (enum)

REMINDER, ALERT, PROMOTION: Tipos de notificaciones.

#### NotificationService

sendNotification(userId, message, type): Envía una notificación.

getUserNotifications(userId): Lista notificaciones del usuario.
## 4.8.Database Design.
### 4.8.1.Database Diagram.
<img src="images/DataBaseDiagram.png" alt="DBdiagram">
