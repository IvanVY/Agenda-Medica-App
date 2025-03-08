# Agenda Médica App 🩺

[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Aplicación de gestión de citas médicas desarrollada en C# con .NET, utilizando Firebase para autenticación y Firestore como base de datos.

---

## 🚀 Funcionalidades Principales

- **Autenticación de Usuarios**:
  - Registro e inicio de sesión con correo electrónico y contraseña (Firebase Authentication).
  - Roles de usuario (pacientes, médicos, administradores).

- **Gestión de Citas**:
  - Crear, editar y eliminar citas médicas.
  - Filtrar citas por fecha, médico o estado.

- **Base de Datos en Tiempo Real**:
  - Almacenamiento de registros en Firestore (historial de citas, perfiles de usuarios).

- **Interfaz Intuitiva**:
  - Diseño moderno con WPF o WinForms (especificar según tu proyecto).

- **Notificaciones**:
  - Recordatorios de citas próximas (opcional, si está implementado).

---

## 🛠 Tecnologías Utilizadas

- **Frontend**: C# .NET (WPF/WinForms).
- **Backend**: Firebase Authentication + Firestore.
- **Herramientas**:
  - Visual Studio 2022.
  - Git para control de versiones.

---

## 📝 Requisitos Previos

1. **Cuenta de Firebase**:
   - Configura un proyecto en [Firebase Console](https://console.firebase.google.com/).
   - Habilita **Authentication** y **Firestore**.

2. **Dependencias**:
   - Instala los paquetes NuGet:
     ```bash
     Install-Package FirebaseAdmin
     Install-Package Google.Cloud.Firestore
     ```

---

## 🚦 Primeros Pasos

1. **Clona el Repositorio**:
   ```bash
   git clone https://github.com/IvanVY/Agenda-Medica-App.git
   cd Agenda-Medica-App

2. **configura Firebase** :
   ```bash
  Crea un archivo firebase-config.json en la carpeta AgendaMedicaApp con las credenciales de tu proyecto Firebase.
  ¡Nunca subas este archivo a GitHub! Agrégalo a .gitignore.
  Ejecuta la Aplicación :
Abre el proyecto en Visual Studio y ejecútalo.


**Capturas de pantalla**:
   ```markdown
   ## 📸 Capturas de Pantalla
   ![Vista Principal](screenshots/main-window.png)
   ![Vista Principal](screenshots/main-window.png)
   ![Vista Principal](screenshots/main-window.png)
