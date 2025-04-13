# 🧩 Social Club - Proyecto Integral de Gestión de Club Social

<div align="center">
  <img src="https://raw.githubusercontent.com/JuanJoseLobatonMateos/SocialClub/main/src/main/resources/images/logo.png" alt="Logo del Club Social" width="200">
  <br><br>
  <em>Aplicación de gestión para clubes sociales con versiones de escritorio y móvil</em>
  <br><br>
</div>

## 📦 Estructura del Proyecto

Este repositorio agrupa dos aplicaciones que forman un único sistema de gestión integral:

| Aplicación | Descripción | Tecnologías | Repositorio |
|-----------|-------------|-------------|-------------|
| 🖥️ **Aplicación de Escritorio** | App principal para administración del club: socios, eventos, reservas, estadísticas y autenticación biométrica | Java 11+, JavaFX, Hibernate, MySQL, DigitalPersona | [🔗 Ver repositorio](https://github.com/JuanJoseLobatonMateos/SocialClub) |
| 📱 **Aplicación Móvil** | App para los socios del club: reservas, eventos, comunicación y perfil personal | Kotlin, Jetpack Compose, Firebase | [🔗 Ver repositorio](https://github.com/JuanJoseLobatonMateos/SocialClub_app_proyecto) |

---

## 🧠 Visión General

El proyecto **Social Club** proporciona una solución moderna, escalable y multiplataforma para clubes sociales. Su objetivo es automatizar y optimizar la gestión de socios, reservas, actividades y comunicaciones internas.

---

## 🌟 Funcionalidades Clave

### 🎯 Gestión de Eventos
- Creación y seguimiento de eventos
- Asistencia y calendario integrado
- Recordatorios para los socios

### 🏟️ Instalaciones y Reservas
- Gestión de pistas deportivas y salas
- Control de disponibilidad y mantenimiento
- Reservas desde escritorio o móvil

### 👤 Socios y Control de Acceso
- Alta/baja de socios
- Gestión de datos personales y carnet
- Control de acceso mediante **huella dactilar** (escritorio)

### 📈 Estadísticas y Reportes
- Generación de informes en PDF y Excel
- Análisis de uso por fechas, instalaciones o usuarios

### 🔒 Seguridad y Autenticación
- Integración biométrica con **DigitalPersona**
- Firebase para gestión segura de usuarios móviles

---

## 📁 Repositorios del Proyecto

- 🖥️ Escritorio (JavaFX): [`SocialClub`](https://github.com/JuanJoseLobatonMateos/SocialClub)
- 📱 Móvil (Kotlin/Firebase): [`SocialClub_app_proyecto`](https://github.com/JuanJoseLobatonMateos/SocialClub_app_proyecto)

---

## 🚀 Clonación del Proyecto Completo

Este repositorio utiliza **submódulos** para mantener separadas las aplicaciones. Para clonar todo correctamente:

```bash
git clone --recurse-submodules https://github.com/JuanJoseLobatonMateos/ClubSocial.git
cd ClubSocial
