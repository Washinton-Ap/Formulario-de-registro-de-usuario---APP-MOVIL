# 📱 Formulario de Registro de Usuario - APP MÓVIL

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Material Design](https://img.shields.io/badge/Material%20Design-757575?style=for-the-badge&logo=material-design&logoColor=white)

## 📋 Descripción

Aplicación móvil nativa Android que implementa un formulario completo de inscripción de usuarios, desarrollada con Kotlin y Material Design. Utiliza los controles comunes de la Interfaz de Usuario (UI) de Android siguiendo el patrón **ConstraintLayout**.

---

## 🏫 Información Académica

| Campo | Detalle |
|---|---|
| **Universidad** | Universidad Técnica Estatal de Quevedo (UTEQ) |
| **Facultad** | Ciencias de la Computación y Diseño Digital |
| **Carrera** | Ingeniería de Software |
| **Asignatura** | Aplicaciones Móviles |
| **Docente** | Ing. Cristian Gabriel Zambrano Vega PhD. |
| **Estudiante** | Apunte Pazmiño Washington German |
| **Nivel** | 6to Software — Paralelo B |
| **Período** | 2026-2027 PPA |

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Versión |
|---|---|
| Lenguaje | Kotlin 2.0.21 |
| Android Studio | Ladybug |
| Min SDK | API 24 (Android 7.0) |
| Target SDK | API 35 (Android 15) |
| Material Components | 1.12.0 |
| ConstraintLayout | 2.1.4 |
| Gradle | 8.7 |
| AGP | 8.5.2 |

---

## 📱 Pantallas de la Aplicación

### Pantalla 1 — Formulario de Registro
- Avatar circular con borde naranja
- Campos con íconos naranja
- Validaciones en tiempo real
- Botones Limpiar y Enviar

### Pantalla 2 — Datos Registrados
- Muestra todos los datos ingresados
- Botón para volver al formulario

---

## 📝 Campos del Formulario

| Campo | Tipo | Validación |
|---|---|---|
| **Cédula** | Numérico | Solo números, exactamente 10 dígitos |
| **Nombres** | Texto | Máx. 500 caracteres, MAYÚSCULAS automático |
| **Fecha Nacimiento** | Fecha | DatePickerDialog, sin fechas futuras |
| **Ciudad** | Texto | Máx. 200 caracteres, MAYÚSCULAS automático |
| **Género** | RadioButton | Selección única: Hombre / Mujer |
| **Correo** | Email | Validación formato Patterns.EMAIL_ADDRESS |
| **Teléfono** | Phone | 10 dígitos, inputType phone |

---

## 🎨 Controles UI Utilizados

- ✅ `ScrollView` — scroll en pantallas pequeñas
- ✅ `ConstraintLayout` — layout principal responsivo
- ✅ `LinearLayout` — agrupación horizontal de botones
- ✅ `ImageView` — avatar circular naranja
- ✅ `TextView` — títulos y etiquetas
- ✅ `TextInputLayout + TextInputEditText` — campos OutlinedBox
- ✅ `RadioGroup + RadioButton` — selección de género
- ✅ `MaterialButton` — botones Limpiar y Enviar
- ✅ `DatePickerDialog` — selector de fecha nativo

---

## 🎨 Paleta de Colores

| Color | Código | Uso |
|---|---|---|
| Naranja | `#E8841A` | Color principal, íconos, botones |
| Blanco | `#FFFFFF` | Fondo de pantallas |
| Negro | `#1A1A1A` | Texto principal |
| Gris texto | `#6B7280` | Hints y texto secundario |
| Gris borde | `#E5E7EB` | Bordes de campos |

RegistroApp/
├── app/src/main/
│   ├── java/com/example/registro/
│   │   ├── MainActivity.kt
│   │   └── ResultadoActivity.kt
│   ├── res/
│   │   ├── layout/
│   │   │   ├── activity_main.xml
│   │   │   └── activity_resultado.xml
│   │   ├── drawable/
│   │   └── values/
│   └── AndroidManifest.xml
└── gradle/
└── libs.versions.toml

---

## 🚀 Cómo Ejecutar

1. Clona el repositorio
```bash
   git clone https://github.com/Washinton-Ap/Formulario-de-registro-de-usuario---APP-MOVIL.git
```
2. Abre **Android Studio** → `File → Open` → selecciona la carpeta `RegistroApp`
3. Clic en **"Trust Project"**
4. Espera que **Gradle sincronice** (~1-2 minutos)
5. Selecciona emulador **Pixel 4 (API 37)**
6. Presiona ▶️ **Run**

---

## 📄 Licencia

Proyecto académico — Universidad Técnica Estatal de Quevedo © 2026
---

## 📁 Estructura del Proyecto
