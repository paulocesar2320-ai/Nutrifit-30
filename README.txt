NUTRIFIT 30 — MVP 0.1

Incluye: registro manual de alimentos y kcal, resumen diario, registro de agua, recetario de 30 preparaciones, planes de fuerza de 1/3/5 días, perfil, estimación orientativa de mantenimiento, recordatorios con la app abierta, respaldo JSON y caché offline.

PRUEBA LOCAL:
- En computadora, abre una terminal dentro de esta carpeta y ejecuta: python -m http.server 8000
- Abre http://localhost:8000
- Para instalar en un celular, publica la carpeta en un hosting HTTPS y abre el enlace desde el navegador.
- Android: Chrome > menú > Instalar aplicación / Añadir a pantalla de inicio.
- iPhone: Safari > Compartir > Añadir a pantalla de inicio.

LIMITACIONES:
- Esta entrega es una PWA, no un APK firmado ni una app publicada en App Store.
- El Service Worker permite reutilizar la app sin conexión después de la primera carga.
- Los recordatorios web solo funcionan de forma fiable mientras la app está abierta; las alarmas en segundo plano requieren integrar notificaciones nativas (por ejemplo, Capacitor/Flutter) y probarlas en dispositivos reales.
- Los datos se guardan en el navegador del dispositivo. Exporta respaldos para no perderlos.
- Las calorías/proteínas de recetas son aproximadas. El recetario inicial ofrece 30 ideas de platos principales/desayunos, no todavía un menú completo de cuatro o cinco comidas diarias para cada día.
- Las rutinas son plantillas generales y deben ajustarse a experiencia, lesiones, movilidad y equipo disponible.

SIGUIENTE FASE:
1. Completar calendario de 30 días con desayuno, refrigerios, almuerzo y cena y lista de compras.
2. Catálogo de alimentos con porciones en gramos y macros.
3. Progresión de entrenamiento, registro de cargas/repeticiones y ajustes casa/gimnasio.
4. Notificaciones nativas Android/iOS.
5. Pruebas, accesibilidad, seguridad, empaquetado y publicación.
