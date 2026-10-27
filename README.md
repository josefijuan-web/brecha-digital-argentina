# Diagnóstico de la Brecha Digital e Inclusión Tecnológica en Argentina

## Sobre mí

**Rita Josefina Juan Briones** - Consultora Analista de Datos (en formación)

*Datos claros para decisiones públicas más justas.*

Estudio la carrera de Técnico Superior en Ciencia de Datos e Inteligencia Artificial. Me interesa usar los datos para entender problemas sociales y explicarlos de forma simple, para que sirvan a quienes tienen que tomar decisiones.

### Qué ofrezco

En este proyecto trabajo como consultora de una organización gubernamental de desarrollo social y tecnología. Mi propuesta es un diagnóstico de la **brecha digital en Argentina**: ver qué hogares tienen computadora e internet fija y cómo influyen el ingreso, la educación y la región. El objetivo es que los resultados ayuden a pensar políticas de inclusión tecnológica.

### Por qué confiar en este trabajo

Un diagnóstico sobre hogares solo sirve si se puede confiar en cómo se trataron los datos y en cómo se usan los resultados. Por eso explico acá cuáles son mis compromisos.

**Datos anonimizados**

- **Qué significa.** Las bases de microdatos de la EPH del INDEC no tienen nombres, DNI, domicilios ni teléfonos. Cada hogar se identifica solo con un código (CODUSU), que no permite saber quién es. Esto responde al secreto estadístico (Ley 17.622) y a la protección de datos personales (Ley 25.326).
- **Por qué importa.** Aunque no haya nombres, si se combinan muchas variables (región, ingreso, nivel educativo, cantidad de integrantes) se podría llegar a reconocer a un hogar, sobre todo en grupos muy chicos. Por eso la anonimización no alcanza por sí sola: también hay que cuidar cómo se presentan los resultados.
- No intento identificar a ningún hogar ni cruzo la base con otras fuentes.
- Muestro solo resultados agregados (porcentajes, promedios, tablas por categoría) y no publico grupos con muy pocos casos.
- Uso los datos únicamente para este proyecto.
- El archivo original queda sin modificar en la carpeta /data. La limpieza se hace sobre una copia que se guarda aparte.
- En el repositorio público no hay ningún dato personal: solo la base anonimizada y las referencias a la fuente.
- **Base utilizada:** microdatos con estructura de la EPH (INDEC), provistos por la cátedra con fines académicos.

**Uso responsable de los resultados**

- **Para qué se usan.** Para mostrar desigualdades y ayudar a pensar políticas de inclusión, nunca para estigmatizar a personas, hogares ni regiones.
- **Hablo de grupos, no de personas.** Si en una región el acceso es más bajo en promedio, eso no significa que todos los hogares de esa región estén igual.
- **No culpo a las personas.** No tener computadora o internet se explica por condiciones económicas y de infraestructura, no por falta de interés o de esfuerzo.
- **No se usan para excluir.** Los resultados sirven para ampliar el acceso, nunca para negar beneficios a nadie.
- **Digo qué límites tiene el análisis.** Los datos son de un solo momento (corte transversal): permiten ver asociaciones, pero no demostrar causas. Además, solo se mide el acceso a computadora e internet fija, no las habilidades digitales ni el uso que se hace de ellas.
- **Explico mis decisiones.** Cada decisión de limpieza (datos faltantes, respuestas "sin respuesta") queda escrita y justificada.

**Todo se puede repetir**

- El análisis está hecho en Python, en notebooks ordenados y comentados que se ejecutan en Google Colab. Cualquier persona puede correrlos y llegar a los mismos resultados.

### Alcance del servicio

**Qué incluye:**

- Limpieza y preparación de los datos (datos faltantes, respuestas "sin respuesta", recodificación).
- Estadística descriptiva (media, mediana, desvío, percentiles) e histogramas.
- Análisis de relaciones entre variables (tablas de contingencia y correlaciones).
- Informe técnico en PDF con conclusiones y recomendaciones de política pública.
- Presentación oral de 8 minutos con un máximo de 7 diapositivas.

**Qué no incluye:**

- Modelos predictivos ni machine learning.
- Afirmaciones sobre causalidad: los datos permiten ver asociaciones, no demostrar causas.
- Relevamiento de datos nuevos.
- Evaluación de la eficiencia de programas o inversiones concretas.

### Cómo comunico los resultados

- Uso un lenguaje claro y sin tecnicismos innecesarios.
- Cada gráfico tiene un título y una frase que explica qué muestra.
- Cada hallazgo viene acompañado de una recomendación concreta.
- La presentación final está pensada para la toma de decisiones: primero lo más importante y después el detalle.

### Herramientas

Python, pandas, numpy, matplotlib, seaborn, scipy, Google Colab y GitHub.

### Contacto

- LinkedIn: [linkedin.com/in/josefina-juan-briones-b6102740](https://www.linkedin.com/in/josefina-juan-briones-b6102740/)
- Correo electrónico: josefijuan@gmail.com
