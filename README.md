# 🏟️ FichaDirecta - Backend API

![Spring Boot](https://img.shields.io/badge/Spring_Boot-4.0.6-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Java](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-Deployed-000000?style=for-the-badge&logo=railway&logoColor=white)

El motor central de **FichaDirecta**, encargado de la gestión de clubes, jugadores y procesos de digitalización del fútbol base.

## 🚀 Tecnologías
- **Core:** Java 21 + Spring Boot 4.
- **Seguridad:** Spring Security + JWT (JSON Web Tokens).
- **Persistencia:** PostgreSQL + Spring Data JPA.
- **Despliegue:** Docker + Railway (CI/CD).
- **Arquitectura:** Hexagonal / Clean Architecture.

## 🛠️ Configuración Local
1. Clona el repositorio.
2. Configura las variables de entorno:
   - `JWT_SECRET`: Tu clave secreta.
   - `JWT_EXPIRATION`: Tiempo en ms.
   - `DB_URL`: jdbc:postgresql://localhost:5432/fichadirecta
3. Ejecuta con Maven:
   ```bash
   cd api
   mvn spring-boot:run
   ```

## 🌐 Despliegue
Este proyecto se despliega automáticamente en **Railway** al hacer push a `main`.
La API está disponible en: `https://fichadirecta-development.up.railway.app`

---
© 2024 FichaDirecta - Desarrollado con ❤️ para el fútbol base.
