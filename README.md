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

### 4. 🎼 Estudio de Adaptación Musical al Español (`adaptador-musical.html`)
- **Taller Creativo en 3 Columnas**:
  - **Columna 1: Original en Inglés (LRC & Audio)** con timestamps, reproducción individual y métrica de sílabas original.
  - **Columna 2: Traducción Literal (Guía)** para mantener intacto el significado y el mensaje de cada verso, con sugerencias automáticas de traducción.
  - **Columna 3: Adaptación Rítmica en Español** con compositor interactivo donde escribes tu adaptación musical.
- **Bucle Continuo y Re-escucha Inmediata de Frases**:
  - Botón **Bucle de Línea** (`Alt + L`) para reproducir en bucle infinito la frase actual mientras cantas y ajustas tu letra al compás.
  - Botón **Escuchar otra vez** (`Ctrl + Espacio` o `R`) para repetir la línea una vez desde el inicio.
  - Control de velocidad (`0.75x`, `0.85x`, `1.0x`, `1.15x`) para desmenuzar las sílabas y la cadencia melódica.
- **Contador Silábico & Métrica Poética en Tiempo Real**:
  - Cálculo instantáneo de sílabas métricas en español (incluyendo sinalefas) frente a las sílabas del verso en inglés.
  - Indicador visual inteligente: coincidencia exacta (verde), leve desfase de ±1 sílaba (amarillo) o ajuste rítmico requerido (rojo).
- **Asistente de Rimas y Diccionario Musical**:
  - Buscador integrado de rimas consonantes y asonantes en español con inserción con un clic.
- **Modo Canto a Pantalla Completa (Karaoke)**:
  - Ensayar la canción completa con la adaptación en pantalla grande sincronizada con el audio original.
- **Exportación Flexible**:
  - Descarga directa de archivo `.lrc` en español (con los timestamps originales listos para reproducir).
  - Descarga de guion completo de 3 columnas (`.txt`) para doblaje o estudio.
  - Envío y prueba con un clic en el Reproductor de Escucha Activa (`player.html`).
  - Interconexión directa desde el Creador de LRC (`crear-lrc.html`).
