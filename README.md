#Gestión de Rutas

Descripción

Gestión de Rutas es un proyecto de orientación y localización que permite al usuario visualizar y gestionar rutas en un mapa, utilizando sensores de geolocalización y orientación. El objetivo principal es ofrecer una experiencia interactiva para trazar rutas, seguir direcciones y marcar localizaciones de forma sencilla y eficiente.

El proyecto combina el manejo de GPS, brújula y mapas, con persistencia de datos en Firebase y almacenamiento local, ofreciendo tanto funcionalidades básicas como avanzadas para la gestión de rutas.

Funcionalidades

Básicas
  - Orientación mediante brújula (magnetómetro).
  - Geolocalización en tiempo real mediante GPS.
  - Visualización de la posición actual en un mapa interactivo.
  - Persistencia de localizaciones y rutas en Firebase Firestore y almacenamiento local.

Avanzadas
  - Crear rutas mediante un listado de ubicaciones.  
  - Diferenciar rutas mediante polígonos coloreados en el mapa.  
  - Representación gráfica de rumbo y dirección.  
  - Interacción táctil para manipular mapas y rutas.

Requisitos técnicos
  - Sensor Magnetómetro: para la orientación del dispositivo y cálculo del rumbo.
  - GPS: para geolocalización y seguimiento de rutas.
  - Mapas: visualización de posiciones, rutas y polígonos.
  - Persistencia de datos: Firebase Firestore y almacenamiento local.
  - Gráficos sencillos: para representar direcciones y rutas.
  - Pantalla táctil: interacción directa con el mapa y las rutas.

Tecnologías utilizadas
  - Kotlin (principal) y Java (interoperabilidad).
  - Android Studio como entorno de desarrollo.
  - Firebase Firestore para almacenamiento en la nube.
  - Google Maps SDK para Android.
  - Sensor Manager de Android para magnetómetro y GPS.

Notas
- Se requiere que el dispositivo tenga GPS y brújula funcionales.
- La app requiere conexión a internet para sincronizar con Firebase.
- Los datos de localización se pueden almacenar también de manera local si no hay conexión.

Autor: Iván Wilfrido Delgado Chaparro
