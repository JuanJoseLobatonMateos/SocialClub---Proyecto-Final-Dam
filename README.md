# 🏢 Social Club – Plataforma Integral para la Gestión de Clubes Sociales

<div align="center">
  <img src="assets/logo.png" alt="Logo del Club Social" width="180" />

  <br><br>
  <em>Sistema completo de gestión para clubes sociales con aplicación de escritorio y app móvil integrada</em>
  <br><br>
</div>

---

## 📦 Repositorios del Proyecto

Este repositorio principal integra dos aplicaciones conectadas a la misma base de datos en la nube:

| Aplicación | Descripción | Repositorio |
|-----------|-------------|-------------|
| 🖥️ Escritorio (Administración del club) | Gestión completa: socios, reservas, empleados, eventos, estadísticas, control de accesos (huella) | [🔗 SocialClub (JavaFX)](https://github.com/JuanJoseLobatonMateos/SocialClub) |
| 📱 Móvil (Socios) | Gestión de reservas, perfil personal, notificaciones y carnet digital | [🔗 SocialClub_app_proyecto (Android)](https://github.com/JuanJoseLobatonMateos/SocialClub_app_proyecto) |

---

## 🧠 Descripción General

**Social Club** es un sistema multiplataforma desarrollado como proyecto de fin de ciclo del Grado Superior en DAM. Consta de:

- 🖥️ Aplicación de escritorio para empleados y administradores.
- 📱 Aplicación móvil para socios del club.
- ☁️ Base de datos centralizada en **Google Cloud**.

El objetivo es digitalizar y centralizar toda la gestión del club: desde socios y reservas, hasta la entrada/salida y estadísticas.

---

## 🚀 Funcionalidades Principales

### Escritorio
- 🔐 Inicio de sesión con roles (administrador y empleados)
- 👥 Gestión de socios: altas, bajas, edición, envío de credenciales
- 📅 Reservas de instalaciones con control de horarios y aforo
- 🧾 Generación de carnets y reportes con JasperReports
- 📸 Captura de imágenes con cámara integrada
- 🧬 Control biométrico con huella dactilar (DigitalPersona)
- 📧 Envío automático de correos electrónicos
- 🌤️ Información del clima en tiempo real
- 🧪 Pruebas unitarias con Mockito

### Móvil
- 🔐 Login con credenciales enviadas por email
- 🆔 Visualización del carnet digital de socio
- 📆 Reservas de pistas con validación de disponibilidad
- 🔔 Notificaciones automáticas de eventos
- 📋 Edición de perfil personal
- ❌ Cancelación de reservas desde la app

---

## 🛠️ Tecnologías Utilizadas

### Aplicación de Escritorio
- Java 21 (Eclipse Temurin)
- JavaFX 23.0.1
- Hibernate + MySQL (Google Cloud)
- JasperReports
- JavaMail
- BCrypt para contraseñas
- Webcam Capture API
- SceneBuilder + FXML
- SDK DigitalPersona
- Mockito

### Aplicación Móvil
- Android Studio Meerkat (2024.3.1)
- Java
- ViewBinding / DataBinding
- JDBC con DriverManager
- jBCrypt
- AndroidX, ConstraintLayout, Navigation

---

## 🗄️ Base de Datos

La base de datos **MySQL** se encuentra estructurada y optimizada para una gestión completa del club. Incluye relaciones entre socios, empleados, reservas, eventos y control de accesos.

- 💾 Script disponible: [`socialclub.sql`](./socialclub.sql)
- 📦 Nombre de la base de datos: `socialclub`
- 🔐 Soporta integridad referencial, claves foráneas y cascadas
- 🎯 Compatibilidad: **MySQL 5.7+**
- 🌍 Conectada a Google Cloud SQL para acceso remoto desde ambas apps

Estructura principal:

| Tabla           | Descripción                                     |
|------------------|-------------------------------------------------|
| `socio`          | Datos personales, huella, foto y credenciales  |
| `reserva`        | Fecha, hora, instalación y socio               |
| `empleado`       | Gestión de empleados y roles                   |
| `rol`            | Administrador, empleado, socio, etc.           |
| `evento`         | Actividades del club                           |
| `instalacion`    | Pistas deportivas y salones disponibles        |

---

## 📁 Estructura del Repositorio Principal

```
SocialClub/
├── SocialClub/                # App de escritorio
└── SocialClub_app_proyecto/   # App móvil para socios
```

> ⚠️ Este repositorio usa submódulos. Para clonar correctamente:

```bash
git clone --recurse-submodules https://github.com/JuanJoseLobatonMateos/ClubSocial.git
cd ClubSocial
```

---

## 📲 Instaladores y Accesos

- 📦 Instalador escritorio (Windows):  
  [🔗 Descargar desde Google Drive](https://drive.google.com/file/d/1O8eYR2HjK1HJ6BuutddeIuD2IJwepNFp/view?usp=drive_link)

- 📱 App móvil (beta en Play Store):  
  [🔗 https://play.google.com/store/apps/details?id=com.jlobatonm.socialclub](https://play.google.com/store/apps/details?id=com.jlobatonm.socialclub)

---

## 📈 Pruebas

- ✅ Más de 30 pruebas unitarias implementadas con Mockito
- 🧪 Pruebas de integración en DAO y lógica de negocio
- ⚙️ Validaciones de entradas, manejo de errores y simulaciones de flujos completos

---

## 🔐 Seguridad

- Contraseñas encriptadas con BCrypt
- Roles diferenciados: administrador, empleado y socio
- Acceso biométrico con huella dactilar (escritorio)
- Validaciones de campos, autenticación y autorización

---

## 🔮 Mejoras Futuras

- 💬 Chat interno y foro para los socios
- 💳 Pago de reservas online
- 🧾 Gestión de invitados
- 📈 Dashboards estadísticos en tiempo real
- 🤖 Funciones inteligentes y predicción de aforos

---

## 👨‍💻 Autor

**Juan José Lobatón Mateos**  
📧 [jlobatonm@gmail.com](mailto:jlobatonm@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/jjlobatonmateos) | [GitHub](https://github.com/JuanJoseLobatonMateos)

---

## 📝 Licencia

Este proyecto está protegido por una licencia propietaria. Ver LICENSE.txt para más información.
