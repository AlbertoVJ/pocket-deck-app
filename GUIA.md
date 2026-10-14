# Empezar con Pocket Deck

## Solo quiero ver cómo se siente

[Abre la demo](https://albertovj.github.io/pocket-deck-app/demo.html). Toca Juegos, Apps u Ocio para cambiar de carpeta. Los botones de acción explican qué harían. No necesitas conectar dispositivos.

También puedes descargar el ZIP y abrir Probar-interfaz.html sin internet.

## Quiero controlar mi PC

1. Descarga el archivo **PocketDeck-Windows-x64.zip** desde Releases. No el ZIP automático llamado Source code.
2. Extrae la carpeta en Documentos y abre **PocketDeck.exe**.
3. Copia el código que muestra el panel de Windows.
4. En Chrome de Android actualizado, abre https://pocket-deck-oxy.albertovj6969.chatgpt.site/ y toca **Conectar PC**.
5. Escribe el código. Permite el acceso a la red local si el navegador lo solicita y estás en tu red de confianza.
6. En Windows, pulsa **Editar botones**, personaliza un botón y guarda.

Para detenerlo: clic derecho sobre Pocket Deck junto al reloj → **Salir de Pocket Deck**. Cerrar el panel solo lo oculta.

## Si no conecta

Comprueba misma Wi-Fi, programa abierto y permiso de red local. Evita la red de invitados. Si ya tienes otra copia de Pocket Deck abierta, ciérrala primero. No expongas el puerto 4319 a Internet.

El paquete incluye Node.js. Usa Windows 11 x64 para esta primera edición. Está sin firma digital; no desactives las protecciones de Windows para ejecutarlo.

## Datos y actualizaciones

Tus botones se guardan en config.json y la vinculación en .pairing-token. Son archivos propios de tu PC. Respáldalos y consérvalos al actualizar. El ZIP de descarga no contiene la configuración de otra persona.

## Qué se comprobó

Runtime oficial de Node verificado por SHA-256. Configuración de nueve botones, autenticación, rechazo de orígenes ajenos, acciones simuladas y guardado con respaldo/conflictos. La demo es independiente del servidor real. No se afirma que todos los teléfonos o redes estén comprobados.
