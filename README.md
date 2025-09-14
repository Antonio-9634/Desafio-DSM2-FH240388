# 📱 ColeAppDSM

Aplicación Android desarrollada en **Kotlin** como parte del **Segundo Desafío Práctico - DSM**.  
La app permite gestionar estudiantes y sus notas escolares utilizando **Firebase Authentication** y **Cloud Firestore**.

---
👨‍💻 Autor

Nombre: Diego Antonio Flores Herrera.

Carnet: FH240388

Materia: Desarrollo de Software para Móviles (DSM)

Universidad Don Bosco

---

## 🚀 Funcionalidades

- **Login y Registro de usuarios** con Firebase Authentication.
- **CRUD de estudiantes**: crear, listar, actualizar y eliminar.
- **CRUD de notas**: ingresar, listar, actualizar y eliminar.
- **Validaciones**:
  - No permite campos vacíos.
  - Notas únicamente entre 0 y 10.
- **Notificaciones** mediante Toast en cada operación.
- **UI con Material Design** y paleta de colores personalizada.
- **Icono de aplicación** generado con [Android Asset Studio](https://romannurik.github.io/AndroidAssetStudio/index.html).

---

## 🛠️ Tecnologías utilizadas

- **Lenguaje**: Kotlin  
- **IDE**: Android Studio  
- **Base de datos**: Firebase Cloud Firestore  
- **Autenticación**: Firebase Authentication (Email/Password)  
- **UI**: Material Components / XML Layouts  

---

## 📂 Estructura del Proyecto

app/src/main/java/com/example/desafio_moviles_fh240388/
├─ auth/ # Login y Registro
├─ students/ # Pantallas CRUD estudiantes
├─ grades/ # Pantallas CRUD notas
└─ models/ # Data classes (Student, Grade)

app/src/main/res/layout/
├─ activity_login.xml
├─ activity_register.xml
├─ activity_add_student.xml
├─ activity_student_list.xml
├─ activity_add_grade.xml
└─ activity_edit_student.xml

app/src/main/res/values/
├─ strings.xml
├─ colors.xml
└─ themes.xml
