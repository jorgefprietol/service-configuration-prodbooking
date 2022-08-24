# service-configuration-prodbooking
service-configuration-prodbooking

Aprende a implementar microservicios basados ​​en Spring Boot y la arquitectura de API RESTful paso a paso.

Contenido del vídeo:
1. Entendiendo la Configuración Centralizada, Config Server
2. Creando properties por perfiles para los Microservicios
3. Creando y configurando el proyecto Spring Config Server
4. Conectando Microservicios Producto y Booking al Config Server 


vault server:
vault server -dev --dev-root-token-id="0000-0000-0000-000000000000"
para registrar los secrets en vault:
vault kv put secret/booking-microservicio @booking.microservicio.json
