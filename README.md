# 🎰 RuletaSTR

**Ruleta de sorteos multichat para streamers.** Tus espectadores de **Twitch, Kick y YouTube** participan a la vez en el mismo sorteo escribiendo una palabra clave en el chat (por ejemplo `!sorteo`), y el ganador se anuncia con un overlay animado en OBS.

## ⬇️ Descargar

Ve a **[Releases](../../releases/latest)** y descarga `RuletaSTR-vX.Y.Z-Windows.zip`.

1. Descomprime el zip y mueve `RuletaSTR.exe` a una carpeta fija (por ejemplo, Documentos).
2. Ábrelo con doble clic. La primera vez Windows puede mostrar *“Windows protegió su PC”*: haz clic en **Más información → Ejecutar de todas formas** (la app es nueva y no tiene una firma digital de pago).
3. Se abre el panel en su propia ventana. Sigue el `LEEME.txt` incluido.

**Actualizar:** la app te avisa sola cuando hay una versión nueva. Descarga el zip nuevo y reemplaza `RuletaSTR.exe`: tu configuración, historial y audios se mantienen (están en `%APPDATA%\RuletaSTR`).

## ✨ Qué incluye

- **Tres chats a la vez:** Twitch, Kick y YouTube, sin contraseñas (solo el nombre de tu canal). Un ticket por persona y plataforma.
- **7 tipos de ruleta:** clásica, tragamonedas, cofre estilo CS:GO, eliminación, eliminación por porcentaje (con efectos de trizas, fuego, agujero negro y polvo), **Battle royale** y **Galaxia**.
- **Modo dramático:** zoom, viñeta y latido antes de revelar al ganador.
- **Confirmación del ganador:** cuenta regresiva para que escriba en el chat; si no, se vuelve a girar sin él.
- **Personalización:** temas, colores, tipografías, posición y tamaño del overlay, y **tus propios audios** para cada momento.
- **Sorteo justo:** el ganador se elige al azar entre todos los inscritos; la animación solo lo muestra.

## En OBS

Fuente **Navegador** → URL `http://127.0.0.1:3777/overlay` · Ancho `1920` · Alto `1080` · marca **Controlar audio mediante OBS**.

---

Este repositorio solo contiene las versiones para descargar.
