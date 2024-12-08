# FSIII_Tienda_Ordenes_Ar
FSIII - SUMATIVA - Arquetipo - Microservicio gestión de ordenes

# Ejecutar app Spring Boot
mvn spring-boot:run

# Levantar contenedor Docker
docker build -t tienda_ordenes_backend .
docker run --name tienda_ordenes_backend -p 8083:8083 tienda_ordenes_backend