# 🏟️ FichaDirecta - Backend API
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.2.5-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Java](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-Multimedia-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-Deployed-000000?style=for-the-badge&logo=railway&logoColor=white)
**FichaDirecta** es la plataforma definitiva para la digitalización del fútbol base. Este repositorio contiene el API Core, encargado de gestionar la inteligencia de negocio, la persistencia de datos y el procesamiento multimedia de los jugadores.
---
## ✨ Características Principales
*   **🛡️ Autenticación Robusta:** Implementación de seguridad mediante Spring Security y JWT (Stateless).
*   **🎥 Sistema Multimedia Avanzado:** Integración con **Cloudinary** para:
    *   Subida y streaming optimizado de vídeos de presentación.
    *   Generación automática de miniaturas (thumbnails).
    *   Procesamiento de fotos de perfil mediante IA (detección de rostros y auto-recorte).
*   **🏗️ Arquitectura de Vanguardia:** Diseño basado en **Arquitectura Hexagonal (Ports & Adapters)** para un código desacoplado, testeable y mantenible.
*   **📊 Gestión de Perfiles:** CRUD completo de jugadores, incluyendo datos técnicos, categorías y disponibilidad.
*   **🚀 Despliegue Continuo:** Configurado para CI/CD en Railway con Docker.
---
## 🏗️ Estructura del Proyecto (Clean Architecture)
El proyecto sigue los principios de *Domain-Driven Design (DDD)*:
```text
src/main/java/com/fichaDirecta/api/
├── domain/            # Modelos de negocio puros (Sin dependencias externas)
├── application/       # Puertos (Interfaces) y Casos de Uso (Lógica de negocio)
└── infrastructure/    # Adaptadores (JPA, Cloudinary, Web Controllers, Seguridad)

© 2026 FichaDirecta - El fútbol base, digitalizado.
