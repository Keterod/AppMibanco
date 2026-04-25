# 📱 AppMibanco

Aplicación móvil desarrollada en Android que simula funcionalidades básicas de una app bancaria, permitiendo gestionar cuentas, visualizar movimientos y realizar solicitudes de crédito.

---

## 🚀 Características principales

- 🏦 Visualización de cuentas bancarias (ahorros y corriente)
- 💰 Consulta de saldo disponible
- 📊 Registro de últimos movimientos
- 📝 Solicitud de créditos
- 📚 Historial de solicitudes de crédito
- 🎯 Gestión de metas de ahorro (proyección incluida)

---

## 🧩 Módulos de la aplicación

### 🏠 Dashboard

Pantalla principal donde el usuario puede:

- Ver sus cuentas
- Acceder a opciones como movimientos, pagos, préstamos y ahorro
- Consultar últimos movimientos

---

### 💳 Solicitud de Crédito

Formulario donde el usuario puede:

- Ingresar monto solicitado
- Definir plazo en meses
- Seleccionar tipo de crédito
- Registrar DNI

📌 Los datos se almacenan localmente usando SQLite.

---

### 📜 Historial de Solicitudes

- Muestra todas las solicitudes registradas
- Permite:
  - Marcar como enviada
  - Eliminar solicitudes
- Los datos se obtienen desde SQLite

---

### 🎯 Meta de Ahorro

- Visualización del progreso de ahorro
- Indicador porcentual de avance
- Proyección de cumplimiento
- Cálculo estimado basado en depósitos mensuales y tasa de interés

---

## 🛠️ Tecnologías utilizadas

- Kotlin
- Jetpack Compose
- SQLite (persistencia local)
- Arquitectura por capas (data, model, ui, navigation)

---

## 📂 Estructura del proyecto

com.example.appmibancosem2
│
├── data
│ ├── local (SQLite)
│ └── model (clases de datos)
│
├── navigation
│ └── NavGraph
│
├── ui
│ ├── screens
│ └── components
│
└── theme

---

## ⚙️ Estado actual del proyecto

- ✅ Solicitud de crédito funcional (guardado en SQLite)
- ✅ Historial conectado a base de datos local
- ⚠️ Otros módulos (movimientos, pagos, etc.) aún en desarrollo
- ⚠️ Uso de datos simulados (`DemoData`) en algunas secciones

---

## 📌 Notas

- La aplicación actualmente funciona de manera local (sin backend)
- Parte de la información mostrada es simulada
- El enfoque principal está en la lógica de navegación y persistencia local

---

## 👨‍💻 Autor

Desarrollado por Diego Carhuamaca
