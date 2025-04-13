Gracias, Juan José. Con toda la información del PDF, he preparado un `README.md` **realista, profesional y completo** para el repositorio principal de tu proyecto **Social Club**. Incluye descripción general, estructura, tecnologías exactas usadas, funcionalidades, instrucciones de instalación y ejecución, y enlaces a los subrepositorios.

---

### ✅ Aquí tienes el README listo para copiar y pegar:

```markdown
# 🏢 Social Club – Plataforma Integral para la Gestión de Clubes Sociales

<div align="center">
  <img src="https://raw.githubusercontent.com/JuanJoseLobatonMateos/SocialClub/main/src/main/resources/images/logo.png" alt="Logo del Club Social" width="180" />
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
- 🔐 **Inicio de sesión con roles**: Administrador y empleados
- 👥 **Gestión de socios**: alta, baja, modificaciones, generación de carnets
- 📅 **Gestión de reservas** de pistas e instalaciones
- 📌 **Gestión de eventos** con carteles
- 📊 **Informes** con JasperReports (PDF, Excel)
- 📸 **Captura de imágenes** con cámara
- 🧬 **Control de acceso mediante huella dactilar**
- 🌤️ **Clima en tiempo real** y aforo de piscina
- 📧 **Envío automático de credenciales por email**
- 🧪 **Pruebas unitarias** con Mockito

### Móvil
- 🔐 Login con credenciales enviadas por correo
- 🆔 Visualización del carnet digital
- 📆 Reservas de pistas con control de disponibilidad
- 📬 Notificaciones automáticas de eventos
- 📋 Gestión del perfil y datos personales
- ❌ Cancelación de reservas desde la app

---

## 🛠️ Tecnologías Utilizadas

### Escritorio
- `Java 21 (Eclipse Temurin)`
- `JavaFX 23.0.1`
- `Hibernate` + `MySQL (Google Cloud)`
- `JasperReports` para generación de informes
- `JavaMail` para envíos automáticos
- `BCrypt` para contraseñas seguras
- `Webcam Capture API`
- `SceneBuilder` para diseño FXML
- `DigitalPersona SDK` para huellas dactilares
- `Mockito` para tests

### Móvil
- `Android Studio Meerkat (2024.3.1 Patch 1)`
- `Java`
- `ViewBinding` y `DataBinding`
- `Executor`, `Handler`, `DriverManager` (MySQL remoto)
- `JBcrypt` para encriptación
- `AndroidX`, `ConstraintLayout`, `Lifecycle`, `Navigation`

---

## 📁 Estructura del Repositorio Principal

```
SocialClub/
├── SocialClub/                # App de escritorio
└── SocialClub_app_proyecto/  # App móvil para socios
```

> ⚠️ Este repositorio usa submódulos. Para clonar correctamente:

```bash
git clone --recurse-submodules https://github.com/JuanJoseLobatonMateos/ClubSocial.git
cd ClubSocial
```

---

## 📲 Instaladores y Accesos

- 📦 Instalador para escritorio (Windows):  
  [🔗 Descargar desde Google Drive](https://drive.google.com/file/d/1O8eYR2HjK1HJ6BuutddeIuD2IJwepNFp/view?usp=drive_link)

- 📱 App móvil (beta en Play Store):  
  [🔗 https://play.google.com/store/apps/details?id=com.jlobatonm.socialclub](https://play.google.com/store/apps/details?id=com.jlobatonm.socialclub)

---

## 📈 Pruebas y Calidad

Se han implementado más de 30 pruebas unitarias con **Mockito** y pruebas de integración para asegurar la fiabilidad del sistema.

---

## 🛡️ Seguridad

- Contraseñas encriptadas con **BCrypt**
- Roles diferenciados (admin / empleado / socio)
- Acceso biométrico opcional
- Validaciones en formularios
- Gestión de errores y logs

---

## 💡 Mejoras Futuras

- 💬 Chat interno con el club
- 💸 Gestión de pagos y TPV virtual
- 📢 Foro para socios
- 🧾 Control de invitados
- 🧠 Inteligencia artificial para análisis predictivo

---

## 👨‍💻 Autor

**Juan José Lobatón Mateos**  
📧 [jlobatonm@gmail.com](mailto:jlobatonm@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/jjlobatonmateos) | [GitHub](https://github.com/JuanJoseLobatonMateos)

---

## 📝 Licencia

Este proyecto está bajo la **Licencia MIT**. Consulta los términos en el archivo `LICENSE` de cada subrepositorio.

```

---

¿Quieres que te genere este archivo en `.md` y te lo prepare para subirlo directamente al repositorio principal? También puedo ayudarte a crear un `GitHub Pages` si quieres mostrarlo como presentación visual.