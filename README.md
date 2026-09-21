# Creador de Contenido — Suite Privada de Creación & Audio

Plataforma privada y personalizada para generar contenido de alto impacto, videos con doblaje/voz en off y sincronización interactiva de canciones.

---

## 🛠️ Herramientas Incluidas

### 1. 🎙️ Estudio de Voz en Off para Videos (`voz-en-off.html`)
- **Importación de Video**: Soporte para videos locales `.mp4`, `.webm`, `.mov`.
- **Grabación Sincronizada con Video**: Graba tu voz en off mientras el video se reproduce, con cuenta regresiva inteligente (`3, 2, 1, ¡Al aire!`).
- **Nivelador de Volumen & Mezclador**:
  - Faders de control independiente para el audio original del video (0% - 200%) y la voz en off (0% - 300%).
  - **Auto-Ducking**: Atenúa el volumen de fondo del video automáticamente al 20% cuando hablas.
  - Vúmetro reactivo en tiempo real con indicador dB y prevención de saturación.
- **Gestión de Tomas (Takes & Punch-In)**:
  - Guarda tomas múltiples (Toma 1, Toma 2, Toma 3...) para elegir o comparar la mejor.
  - Opción de **Punch-In**: regraba solo desde el segundo actual del video sin reiniciar toda la grabación.
  - Forma de onda interactiva (Waveform) y calibración de latencia de micrófono (`-400ms` a `+400ms`).
- **Teleprompter Integrado**: Lee tu guion en pantalla con auto-scroll sincronizado y tamaño de fuente ajustable.
- **Exportación Dual**:
  - Descarga directa del video final renderizado con el audio mezclado.
  - Descarga de la pista de voz aislada en `.wav` de alta calidad para editores externos (CapCut, Premiere, DaVinci).

### 2. 🎶 Estudio Creador de LRC (`crear-lrc.html`)
- Herramienta para marcar tiempos y generar archivos `.lrc` al compás de la música con la barra espaciadora (Tap-to-Sync).
- Ajuste milimétrico frase por frase, modo karaoke en vivo y exportación.

### 3. 🎧 Escucha Activa (`index.html` y `player.html`)
- Catálogo de canciones y entrenamiento auditivo frase por frase a ciegas con ejercicios y quizzes.