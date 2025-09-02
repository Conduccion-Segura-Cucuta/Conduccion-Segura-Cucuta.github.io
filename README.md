# 🚦 Conducción Segura - Cúcuta

Aplicación móvil desarrollada en **Flutter** para fomentar la seguridad vial en la ciudad de **Cúcuta**.  
Su objetivo es brindar a los conductores y ciudadanos una herramienta confiable para **reportar incidencias**, **recibir alertas en tiempo real** y **conducir con mayor tranquilidad**.

---

## ✨ Características principales

- 🗺️ **Mapa interactivo** con ubicación en tiempo real usando geolocalización.
- 📍 **Marcadores de incidencias** (accidentes, trancones, riesgos en vía).
- 🚨 **Notificaciones push** para alertar a los conductores de incidentes cercanos.
- 🧭 **Filtro de distancia** para recibir solo alertas relevantes.
- 🤝 **Comunidad colaborativa**: reportes de conductores y ciudadanos.
- 🔒 **Seguridad y confianza** con reglas de Firebase y control de datos.
- 🌐 **Optimizada para Cúcuta**: diseñada teniendo en cuenta la movilidad local.

---

## 🛠️ Tecnologías utilizadas

- **Frontend:** Flutter
- **Mapas y geolocalización:** `flutter_map`, `geolocator`, `background_geolocation`
- **Backend / Servicios:** Firebase (Auth, Firebase, imgdb, Reglas de seguridad)
- **Notificaciones:** Flutter Local Notification
- **Gestión de incidencias:** Servicios propios (`IncidenceService`)
- **UI/UX:** Material Design + personalización para confianza y accesibilidad

---

## 📷 Funcionalidades destacadas en la app

- **Pantalla principal con mapa:**  
  Visualiza tu ubicación y reportes cercanos.
- **Reportar incidencia:**  
  Los usuarios pueden subir incidencias con descripción y foto (almacenadas en Firebase).
- **Alertas inteligentes:**  
  Notificaciones cuando el usuario se acerca a una zona de riesgo.
- **Modo confiable:**  
  Iconografía e interfaz diseñadas para transmitir confianza y seguridad.

---

## 🚀 Instalación y ejecución

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Ludoviko451/conduccion-segura.git
   cd conduccion_segura

2. Instala las dependencias:

   ```bash
   flutter pub get
   ```
3. Configura Firebase (descarga `google-services.json` o `GoogleService-Info.plist` según la plataforma).
4. Ejecuta la app:

   ```bash
   flutter run
   ```

---

## 📍 Ciudad de enfoque

La app está pensada inicialmente para la ciudad de **Cúcuta, Norte de Santander (Colombia)**, con planes de expandirse a otras ciudades en el futuro.

---

## ⚖️ Descargo de responsabilidad

La información mostrada en **Conducción Segura** es **generada por los usuarios** de manera colaborativa.  
El propósito de esta aplicación es **mejorar la seguridad vial y la movilidad en la ciudad de Cúcuta**, ayudando a prevenir accidentes y alertar sobre condiciones riesgosas en la vía (como huecos, choques o congestiones).  

- 🚫 No promovemos la evasión de controles viales ni actividades ilegales.  
- 📌 Los datos sobre retenes o puntos de control son aportes de la comunidad y se muestran únicamente con fines informativos.  
- 🔒 Los desarrolladores no se hacen responsables del uso indebido que terceros puedan darle a la aplicación o la información compartida.  

Al usar esta aplicación, aceptas que su contenido es **referencial** y puede variar en cualquier momento.
