# 🧠 Laboratorio Multimodal
### Más allá de las palabras: cuando la inteligencia artificial aprende a mirar

**Masterclass interactiva de autoaprendizaje sobre modelos multimodales: integración de texto y análisis interactivo de imágenes.**

![Estado](https://img.shields.io/badge/Estado-Material%20educativo-blueviolet)
![Duración](https://img.shields.io/badge/Duración-45%20minutos-ff9f68)
![Tecnologías](https://img.shields.io/badge/HTML-CSS-JavaScript-4f46e5)
![Licencia](https://img.shields.io/badge/Contenidos-CC%20BY--NC--SA%204.0-blue)

### 🌐 [ACCEDER AL LABORATORIO INTERACTIVO](https://mary1922.github.io/laboratorio-multimodal/)

---

## 📖 1. Presentación del proyecto

**Laboratorio Multimodal** es un recurso didáctico interactivo desarrollado para facilitar la comprensión de los modelos de inteligencia artificial capaces de procesar conjuntamente texto e imágenes.

El proyecto nace como material de aprendizaje para estudiantes de un bootcamp de Inteligencia Artificial y Machine Learning, con conocimientos previos de programación en Python, NLP, LLM y fundamentos de Machine Learning, pero sin necesidad de experiencia anterior en visión artificial.

A través de explicaciones progresivas, analogías, experimentos interactivos y un caso práctico, se exploran las capacidades, el funcionamiento y las limitaciones de estos modelos.

La web está diseñada para el **aprendizaje autónomo**, con una duración orientativa de 45 minutos.

### 🎯 Objetivos de aprendizaje

Al completar el laboratorio, el estudiante será capaz de:

- Comprender qué es un modelo multimodal y qué modalidades de información puede procesar.
- Diferenciar un modelo de lenguaje tradicional, un modelo de visión-lenguaje (VLM) y un agente de IA.
- Entender conceptualmente cómo se transforman las imágenes en representaciones numéricas.
- Comprender cómo se integra la información visual con las instrucciones escritas.
- Formular prompts que permitan realizar análisis interactivos de imágenes.
- Diferenciar observaciones, inferencias e información que necesita verificación.
- Reconocer limitaciones, errores de interpretación y riesgos de seguridad.
- Identificar cómo incorporar capacidades multimodales a una aplicación desarrollada en Python.

## 📥 Guía didáctica descargable

Además del laboratorio interactivo, está disponible una **guía de autoaprendizaje en PDF** con las explicaciones completas de los siete capítulos, ejemplos, ejercicios con soluciones razonadas, glosario y referencias técnicas.

📘 **[Descargar guía completa en PDF](docs/guia-modelos-multimodales.pdf)**

El documento puede consultarse sin conexión y utilizarse como material de estudio o repaso.

**Duración orientativa:** 45 minutos de lectura y actividades principales.
---

## 🕵️ 2. El hilo conductor: una investigación visual

El aprendizaje gira alrededor de un caso práctico.

Un vecino comunica una posible incidencia en el garaje de su comunidad y adjunta una fotografía en la que se observa una zona mojada próxima a un armario de instalaciones.

La pregunta es:

**¿Qué puede determinar realmente una IA a partir de esa fotografía?**

A lo largo del laboratorio, el estudiante investiga el caso mediante preguntas sucesivas y aprende a distinguir entre:

- **Lo que se observa:** información visual identificable.
- **Lo que se infiere:** interpretaciones o hipótesis.
- **Lo que debe comprobarse:** afirmaciones que requieren información adicional.

Este caso conecta los conceptos teóricos con una posible aplicación de IA para analizar y documentar incidencias.

---

## 🗂️ 3. Contenido del laboratorio

El recorrido está dividido en siete capítulos:

| Capítulo | Contenido | Duración |
|:---|:---|:---:|
| 01 | El caso: ¿qué puede afirmar la IA? | 4 min |
| 02 | Qué es un modelo multimodal | 6 min |
| 03 | De píxeles a lenguaje: cómo interpreta imágenes | 8 min |
| 04 | Conversar con imágenes: análisis interactivo | 7 min |
| 05 | Cuando la IA se equivoca: limitaciones y riesgos | 8 min |
| 06 | Integración en aplicaciones Python | 8 min |
| 07 | Cerrar el expediente y comprobar conocimientos | 4 min |
| | **Duración total estimada** | **45 min** |

### 🔬 Experimentos interactivos

Durante el recorrido se realizan distintas actividades:

**Experimento 01 — ¿Qué puede afirmar la IA?**

Análisis de una fotografía para identificar qué conclusiones están justificadas y cuáles no.

**Experimento 02 — ¿Multimodal o agente?**

Identificación de las diferencias entre un modelo que procesa imágenes y un sistema con autonomía y herramientas.

**Experimento 03 — De píxeles a representaciones**

Visualización de una cuadrícula sobre una imagen para comprender el concepto de parches visuales y su relación con las representaciones numéricas.

**Experimento 04 — Conversar con la misma imagen**

Simulación de cinco preguntas sucesivas que muestran cómo cambia el análisis al mejorar y precisar las instrucciones.

**Experimento 05 — Observa, infiere y verifica**

Ejercicio de clasificación de afirmaciones según su relación con la evidencia disponible.

**Experimento 06 — Construye un prompt**

Generación interactiva de instrucciones estructuradas para analizar imágenes y obtener resultados organizados.

**Evaluación final — Tu prueba de criterio**

Cuestionario autocorregible de cinco preguntas para consolidar los conceptos aprendidos.

---

## 💡 4. Metodología didáctica

El laboratorio utiliza una metodología de **aprendizaje basado en casos y experimentación guiada**.

Combina:

- **Microlecciones:** conceptos explicados de manera progresiva y contextualizada.
- **Analogías:** relaciones con conocimientos previos de NLP, tokens y embeddings.
- **Aprendizaje activo:** preguntas y experimentos que requieren tomar decisiones.
- **Retroalimentación:** soluciones razonadas para comprobar y corregir errores.
- **Aplicación práctica:** conexión de los conceptos con APIs, Python y respuestas JSON.
- **Pensamiento crítico:** análisis de la fiabilidad, seguridad y limitaciones de los resultados.

Se prioriza comprender el funcionamiento y desarrollar criterio técnico antes que memorizar definiciones.

---

## 🛠️ 5. Tecnologías utilizadas

| Tecnología | Utilización |
|---|---|
| HTML5 | Estructura de la web y contenidos educativos |
| CSS3 | Diseño responsive, tipografía y componentes visuales |
| JavaScript | Navegación, experimentos, cuestionario y seguimiento del progreso |
| LocalStorage | Conservación del progreso en el navegador |
| Git y GitHub | Control de versiones y alojamiento del código |
| GitHub Pages | Publicación gratuita de la web |

### Características técnicas

- Web estática, sin backend.
- No necesita instalación de dependencias.
- No requiere claves de API.
- No necesita crear cuentas para realizar el laboratorio.
- Compatible con navegadores modernos.
- Diseño adaptable a distintos tamaños de pantalla.
- Progreso almacenado localmente en el navegador.

**Importante:** las respuestas de IA que aparecen en los experimentos son simulaciones didácticas. No se realizan llamadas reales a modelos multimodales ni se procesan fotografías mediante una API.

Esta decisión permite que los resultados sean reproducibles y que el aprendizaje no dependa de servicios externos.

---

## 🚀 6. Cómo utilizar el laboratorio

### Opción A. Acceso online (recomendada)

Entra directamente desde tu navegador:

**[Abrir Laboratorio Multimodal](https://mary1922.github.io/laboratorio-multimodal/)**

No necesitas descargar archivos ni instalar programas.

Una vez dentro:

1. Selecciona **Comenzar la investigación**.
2. Lee los capítulos siguiendo el orden propuesto.
3. Realiza los experimentos y consulta sus explicaciones.
4. Marca los capítulos completados.
5. Finaliza con el cuestionario de evaluación.

### Opción B. Ejecutar la web localmente

También puedes utilizar el proyecto sin publicarlo.

**1. Clona el repositorio:**

```bash
git clone https://github.com/Mary1922/laboratorio-multimodal.git
```

**2. Accede a la carpeta:**

```bash
cd laboratorio-multimodal
```

**3. Abre el archivo `index.html` en tu navegador.**

No es necesario instalar paquetes de Python, Node.js ni ejecutar un servidor para las actividades incluidas.

---

## 🏗️ 7. Estructura del repositorio

```text
laboratorio-multimodal/
│
├── index.html
│   └── Web y experimentos interactivos
│
├── README.md
│   └── Documentación del proyecto
│
├── LICENSE
│   └── Licencia MIT para el código
│
└── LICENSE-CONTENIDOS.md
    └── Licencia Creative Commons
        para los contenidos educativos
```

El laboratorio se ha desarrollado como una web estática, con una estructura sencilla que facilita su publicación y mantenimiento.

---

## ⚠️ 8. Limitaciones y consideraciones

Este proyecto tiene una finalidad exclusivamente educativa.

- Las actividades interactivas utilizan respuestas simuladas.
- Los ejemplos no constituyen diagnósticos técnicos.
- La interpretación de imágenes mediante IA puede contener errores.
- Las conclusiones automatizadas deben verificarse cuando puedan afectar a personas, instalaciones o decisiones importantes.
- Un formato de salida correcto, como JSON, no garantiza que la información sea verdadera.
- Las instrucciones incluidas en imágenes y documentos externos deben tratarse como datos no confiables.

El laboratorio busca fomentar una utilización responsable y crítica de la inteligencia artificial.

---

## 📚 9. Referencias y recursos

Para ampliar los conceptos tratados:

- [OpenAI — Images and Vision](https://developers.openai.com/api/docs/guides/images-vision)
- [Hugging Face — Vision Language Models](https://huggingface.co/docs/transformers/tasks/image_text_to_text)
- [Google Research — An Image is Worth 16x16 Words (Vision Transformer)](https://arxiv.org/abs/2010.11929)
- [OWASP — LLM Prompt Injection Prevention](https://cheatsheetseries.owasp.org/cheatsheets/LLM_Prompt_Injection_Prevention_Cheat_Sheet.html)

Estas fuentes permiten profundizar en los fundamentos técnicos de los modelos de visión-lenguaje, las arquitecturas visuales y los riesgos de seguridad.

---

## 👩‍💻 10. Autoría

**María Roldán**

Proyecto educativo desarrollado en el contexto de formación en Inteligencia Artificial y Machine Learning.

El objetivo es compartir conocimientos, favorecer el aprendizaje colaborativo y acercar conceptos técnicos de IA a estudiantes que comienzan a trabajar con estas tecnologías.

---

## ⚖️ 11. Licencias

© 2026 María Roldán.

Este proyecto utiliza dos licencias diferenciadas:

### 📘 Contenidos educativos — Creative Commons

Los textos, explicaciones, ejercicios y materiales educativos originales se distribuyen bajo:

**Creative Commons Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0).**

Se permite compartir y adaptar el material con atribución, sin fines comerciales y manteniendo la misma licencia para las adaptaciones distribuidas.

Consulta [LICENSE-CONTENIDOS.md](LICENSE-CONTENIDOS.md).

### 💻 Código fuente — MIT License

El código HTML, CSS y JavaScript original del proyecto se distribuye bajo la licencia MIT.

Consulta [LICENSE](LICENSE).

Los recursos de terceros, cuando existan, conservan sus propias condiciones de uso.

---

### ✨ La idea clave

**La IA multimodal no consiste únicamente en reconocer lo que aparece en una imagen, sino en relacionar información visual y lenguaje, interpretar el contexto y reconocer los límites de lo que puede concluirse.**

*Laboratorio Multimodal — Aprender a mirar también significa aprender a cuestionar lo que vemos.*
