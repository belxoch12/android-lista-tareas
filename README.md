<h1 align="center">Lista de Tareas</h1>

<p align="center">
  App Android para agregar y eliminar tareas, construida con RecyclerView y CardView.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white" alt="Android">
  <img src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/min_SDK-24-blue" alt="min SDK 24">
</p>

---

## Funcionalidades

- Lista de tareas mostrada en tarjetas (`RecyclerView` + `CardView`).
- Botón flotante (FAB) que abre un diálogo para agregar una nueva tarea.
- Botón en cada tarjeta para eliminar la tarea.

## Estructura

```
app/src/main/java/com/example/listadetareas/
├── MainActivity.java          # Lista, FAB y diálogo para agregar tareas
└── RecyclerViewAdapter.java   # Adaptador y eliminación de tareas
app/src/main/res/layout/
├── activity_main.xml
└── my_card_view.xml           # Diseño de cada tarjeta
```

## Tecnologías

Java · Android SDK (min 24, target 33) · RecyclerView · Material Components · GridLayout

## Cómo ejecutarlo

1. Clona el repositorio y ábrelo en **Android Studio**.
2. Espera a que Gradle sincronice las dependencias.
3. Ejecútalo en un emulador o dispositivo físico.

## Autoría

Desarrollado por [belxoch12](https://github.com/belxoch12).
