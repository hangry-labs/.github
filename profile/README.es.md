<p align="center">
  <img src="./assets/hangrylabs_logo_horizontal.webp" alt="Hangry Labs: sistemas útiles sin misterios" width="100%">
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README.nb.md">Norsk bokmål</a> ·
  <a href="README.pl.md">Polski</a> ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.zh.md">简体中文</a> ·
  <strong>Español</strong>
</p>

# 🧪 Hangry Labs

**IA local y software abierto, preparados para ejecutarse en hardware bajo tu control. Por la humanidad y el poder de los nuggets.**

Hangry Labs crea sistemas prácticos de IA autoalojables, automatización, paneles, estándares y herramientas creativas. Empaquetamos las partes difíciles, ofrecemos interfaces útiles y explicamos las limitaciones reales para que el software avanzado sea más fácil de ejecutar, comprender, conectar y conservar.

Explora el [catálogo de software de Hangry Labs](https://hangrylabs.app/es/software) para encontrar guías de productos, ejemplos reales y ayuda de instalación.

Porque a veces solo quieres que la cosa funcione.  
No invocar doce demonios de dependencias y sacrificar el fin de semana a los entornos de Python.

---

## ⚡ Elige una herramienta y empieza

El [catálogo de software](https://hangrylabs.app/es/software) presenta las aplicaciones que ya tienen la nueva interfaz de Hangry Labs y el empaquetado actualizado. Puedes compararlas y escuchar ejemplos reales de voz antes de descargar nada.

Para las herramientas de voz basadas en Docker, cada guía de instalación hace seis preguntas breves sobre el sistema operativo, el hardware, el tamaño de descarga, el canal de versiones, el registro de imágenes y el acceso de red. Después genera un único comando exacto y explica cada paso con lenguaje sencillo. Tus respuestas permanecen en el navegador y no se envían al servidor.

Elige un proyecto, abre **Ayuda de instalación** y deja que el asistente se encargue de la misión secundaria de construir el comando.

---

## 🌍 Por qué existe Hangry Labs

Las herramientas modernas de IA son potentes, pero muchas dependen de servicios alojados, infraestructura oculta, enlaces de modelos que desaparecen, rituales de configuración complejos o cuentas externas.

Hangry Labs adopta un enfoque más independiente:

- ejecuta herramientas localmente o en infraestructura que controles
- mantén privados los prompts, las voces, las transcripciones, los documentos y las imágenes
- utiliza comandos de Docker claros y valores predeterminados razonables
- incluye modelos y dependencias cuando resulte práctico
- ofrece interfaces web para personas y API documentadas para aplicaciones
- publica información honesta sobre hardware, mediciones y limitaciones
- conserva la atribución, las licencias y los enlaces de los proyectos originales

La primera experiencia ideal debería ser así:

```text
docker run ...
```

y entonces funciona.

Quizá no siempre a la perfección. Todavía estamos apagando incendios de dependencias. Pero esa es la dirección.

---

## 🧰 Aplicaciones

Lo que comenzó con herramientas locales de voz ha crecido hasta convertirse en una colección más amplia de software de IA, operaciones y creación.

| Proyecto | Área | Qué ofrece |
|---|---|---|
| [**KokoroTTS**](https://github.com/hangry-labs/kokoroTTS) | Voz local rápida | 173 voces en 11 idiomas, cinco paquetes de modelos administrados de forma independiente, streaming, diálogos SSML, API nativas y compatibles con OpenAI, y herramientas MCP opcionales. |
| [**MeloTTS**](https://github.com/hangry-labs/MeloTTS) | Voz multilingüe | Ocho modelos en seis idiomas, administración de modelos desde el navegador, seis formatos de salida, MP3 y PCM transmitidos por frases, y API nativas y compatibles con OpenAI. |
| [**OmniVoiceTTS**](https://github.com/hangry-labs/OmniVoiceTTS) | Laboratorio de voz | Voz para más de 600 idiomas con diseño de voces, clonación desde micrófono y referencias, perfiles reutilizables, diálogos SSML-H, streaming y API compatibles con OpenAI. |
| [**VoxCPMTTS**](https://github.com/hangry-labs/VoxCPMTTS) | Voz creativa | Generación en 30 idiomas mediante Nano-vLLM, diseño natural de voces, clonación guiada por referencias y transcripciones, perfiles reutilizables, streaming progresivo y API HTTP. |
| [**Qwen3-ASR-STT**](https://github.com/hangry-labs/Qwen3-ASR-STT) | Voz a texto | Transcripción local en 30 idiomas, sesiones de micrófono en directo, marcas de tiempo y subtítulos, clientes compatibles con OpenAI y transcripción MCP opcional de archivos y URL. |
| [**llama.nodrama**](https://github.com/hangry-labs/llama.nodrama) | Operación de LLM | Un panel ligero para slots de llama.cpp, colas, rendimiento, comportamiento de la caché KV, líneas de tiempo de solicitudes y detalles operativos ocultos tras un endpoint LLM local. |
| [**see-through**](https://github.com/hangry-labs/see-through) | Herramientas creativas | Descomposición local y privada de personajes de anime en capas, con exportación PSD por capas, vistas de profundidad interactivas, orden manual, regeneración selectiva y recuperación de detalles originales. |

Los diferentes motores y herramientas tienen fortalezas distintas. Los empaquetamos según aquello en lo que realmente destacan, en lugar de fingir que un solo modelo debería resolverlo todo.

Nuggets diferentes para desastres diferentes.

### Estándares y componentes básicos

| Proyecto | Función | Enfoque actual |
|---|---|---|
| [**Faster Qwen3-TTS**](https://github.com/hangry-labs/faster-qwen3-tts-studio) | Entorno de ejecución de alto rendimiento | Inferencia Qwen3-TTS en tiempo real, con y sin streaming, aceleración CUDA Graph, un servidor compatible con OpenAI y un backend GGML experimental para CUDA y Apple Silicon. |
| [**Especificación SSML-H**](https://github.com/hangry-labs/ssml-h-spec) | Marcado de voz | La fuente normativa del perfil de extensión independiente de Hangry Labs para W3C SSML 1.1, con declaraciones dinámicas de voces e instrucciones por turno. |
| [**SSML-H Tools**](https://github.com/hangry-labs/ssml-h-tools) | Biblioteca de referencia | Un analizador, validador y constructor de Python independiente del motor que compila SSML y SSML-H en planes de síntesis inmutables. |

---

## 🛠️ Cómo construimos

### IA local y privacidad predeterminada

Tus datos deberían permanecer cerca. Los proyectos de Hangry Labs buscan funcionar en tu máquina o servidor sin enviar entradas sensibles a la nube de otra persona.

### Todo incluido cuando resulta práctico

Las imágenes completas de Docker pueden incluir los modelos, las dependencias de ejecución y la propia aplicación. Cuando una imagen totalmente preparada no resulte práctica, los proyectos pueden ofrecer una imagen más pequeña respaldada por un volumen de datos persistente y estable.

El objetivo es la fiabilidad, no ganar un concurso por la imagen más pequeña. Una imagen más grande que siga funcionando el año que viene suele ser más útil que una imagen diminuta que se rompe cuando cambia un paquete o desaparece un enlace de modelo.

### Interfaces abiertas

Las personas deberían disponer de una interfaz web clara. Las aplicaciones y automatizaciones deberían tener API HTTP documentadas, endpoints de estado útiles y un comportamiento predecible.

Cuando las API compatibles con OpenAI tienen sentido, las usamos como base práctica de compatibilidad mientras mantenemos disponibles las funciones específicas y útiles de cada producto.

### Límites honestos

Los modelos rápidos pueden tener capacidades más limitadas. Los modelos potentes pueden necesitar más memoria y paciencia. Los benchmarks deben indicar el hardware y los ajustes, y las guías de compatibilidad deben explicar con claridad qué se midió.

Nada de humo mágico. Solo una realidad de ingeniería ligeramente dramática.

### Respeto por el trabajo original

Muchos proyectos de Hangry Labs se basan en excelentes investigaciones y software de código abierto. Mantenemos visibles la atribución y las licencias, explicamos qué procede de los proyectos originales y documentamos lo que Hangry Labs añade en empaquetado, interfaces, despliegue y validación.

---

## 🚀 Dirección a largo plazo

Hangry Labs sigue siendo un laboratorio para misiones secundarias útiles. La dirección general incluye herramientas locales para:

- compañeros de IA e interfaces de voz
- sistemas de memoria y conocimiento
- paneles autoalojados
- automatización privada
- herramientas creativas
- utilidades para juegos y streaming
- servicio y observabilidad de modelos
- marcado de voz e interoperabilidad
- inferencia de IA rápida y reproducible

El objetivo es una colección de herramientas que las personas puedan ejecutar, comprender, modificar, conectar y conservar.

No todo necesita ser una suscripción en la nube. Algunas cosas deberían pertenecer simplemente a quienes las utilizan.

---

## 🧃 Por la humanidad y el poder de los nuggets

Construimos para quienes quieren ejecutar las cosas por sí mismos.

Por quienes construyen.<br>
Por quienes crean.<br>
Por la privacidad.<br>
Por los experimentos extraños.<br>
Por los pequeños arreglos que se convierten en proyectos gigantes.<br>
Por la humanidad.

Y, por supuesto, por el poder de los nuggets.

Consulta los repositorios fijados a continuación para ver los proyectos que reciben más atención actualmente.
