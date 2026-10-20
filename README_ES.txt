FOTBALL ULTIMATE X — PROTOTIPO ANDROID 0.1
==========================================

Qué incluye esta base:
- Aplicación Android nativa (no WebView ni página web).
- Pantalla horizontal y pantalla completa.
- Menú principal táctil.
- Carrera con temporada, semana, presupuesto y balance de resultados.
- Plantilla inicial de demostración.
- Mercado de fichajes de demostración.
- Patrocinadores ficticios para probar contratos e ingresos.
- Simulación instantánea de partidos y progresión de temporadas.
- Pantallas de crear club y guardado local en el dispositivo.

IMPORTANTE
----------
Esto es un prototipo jugable en código fuente, no un APK ya compilado ni probado en un teléfono real.
Los nombres, valores y medias de futbolistas son datos de demostración y pueden no coincidir con datos actuales. Los patrocinadores son ficticios. No incluye licencias oficiales, escudos oficiales ni conexión a datos en vivo.

CÓMO GENERAR EL APK
-------------------
Opción A — Android Studio:
1. Instala Android Studio en una computadora.
2. Abre la carpeta FOTBALL_ULTIMATE_X como proyecto existente.
3. Deja que Gradle sincronice y descargue las dependencias.
4. Ejecuta Build > Build APK(s).
5. El APK de depuración se generará en app/build/outputs/apk/debug/app-debug.apk.

Opción B — GitHub Actions:
1. Sube el contenido de esta carpeta a un repositorio GitHub nuevo.
2. En la pestaña Actions, permite ejecutar workflows si GitHub lo solicita.
3. Abre el workflow “Build Android APK” y pulsa “Run workflow”.
4. Cuando termine correctamente, abre la ejecución y descarga el artefacto
   “FOTBALL-ULTIMATE-X-debug-apk”. Ese ZIP contiene app-debug.apk.
5. Copia el APK al teléfono Android y ábrelo para instalarlo. Android puede pedirte
   autorizar temporalmente la instalación desde esa fuente.

La compilación requiere Internet para descargar Gradle y los componentes Android.
La versión de depuración es para pruebas, no una versión firmada para publicar en Play Store.
