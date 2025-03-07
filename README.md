**Trabajo 04: Construcción de un Generador de Contenido Educativo basado en LLM**

![image.png](attachment:f58bc38b-6289-45af-8b2c-77cb43ee2e55:image.png)

**Grupo 6**

Integrantes:

- Valentina Ospina Narváez - [vospinan@unal.edu.co](mailto:vospinan@unal.edu.co)
- Juan Pablo Pineda Lopera - [jppinedal@unal.edu.co](mailto:jppinedal@unal.edu.co)
- Juan Camilo Torres Arboleda - [jutorresar@unal.edu.co](mailto:jutorresar@unal.edu.co)

Semestre 2024 - 2

---

# 1. Introducción

En el contexto actual de la educación, se requiere acceso a materiales de estudio personalizados, dinámicos y adaptables a  necesidades específicas. Los modelos de lenguaje de gran escala (LLMs) ofrecen una solución innovadora para la generación de contenido educativo automatizado, permitiendo la creación de materiales como resúmenes, explicaciones, preguntas de evaluación y ejercicios interactivos.

## **1.1 Objetivos**

El desarrollo de un **Generador de Contenido Educativo basado en LLM** tiene los siguientes propósitos principales:

- **Automatizar la creación de contenido**: Reducir el tiempo y esfuerzo requerido para generar materiales de estudio estructurados y de calidad.
- **Personalización del aprendizaje**: Adaptar el contenido según el nivel de conocimiento y las necesidades de cada estudiante.
- **Facilitar el acceso a información compleja**: Explicar conceptos difíciles en un lenguaje más accesible y con ejemplos prácticos.
- **Optimizar el proceso de enseñanza y evaluación**: Proveer herramientas interactivas para la autoevaluación y refuerzo del aprendizaje.

## **1.2 Beneficios**

- **Eficiencia**: Permite generar materiales en tiempo real sin intervención manual.
- **Escalabilidad**: Puede ser utilizado por múltiples usuarios simultáneamente en diversas disciplinas.
- **Interactividad**: Potencia el aprendizaje mediante preguntas, respuestas y generación de casos de estudio.
- **Accesibilidad**: Facilita el acceso a contenido educativo de calidad sin barreras geográficas o económicas.

## **1.3 Aplicaciones**

- **Generación de resúmenes y apuntes**: Síntesis de información clave de textos académicos.
- **Creación de cuestionarios y ejercicios**: Evaluaciones automáticas basadas en el contenido generado.
- **Explicación de conceptos**: Respuestas detalladas y adaptadas al nivel del usuario.
- **Apoyo en la investigación**: Sugerencias de referencias, estructura de ensayos y generación de hipótesis.

# 2. Contexto

## **2.1 Qué es un agente?**

Un **agente en inteligencia artificial** es un sistema autónomo que percibe su entorno a través de sensores, procesa la información utilizando reglas, modelos o algoritmos de aprendizaje, y ejecuta acciones mediante actuadores para lograr un objetivo específico. Dependiendo de su complejidad, un agente puede ser **reactivo**, respondiendo directamente a estímulos, o **basado en modelos**, donde mantiene un estado interno que le permite razonar sobre el entorno y planificar acciones.

Según Russell y Norvig, *"un agente es cualquier cosa que puede percibir su entorno mediante sensores y actuar sobre ese entorno mediante actuadores. Un agente inteligente es aquel que selecciona sus acciones de manera que maximicen el éxito en la consecución de sus objetivos"* [1].

Los agentes pueden clasificarse en distintos tipos según su capacidad de decisión y aprendizaje:

- **Agentes reactivos simples:** Responden a entradas específicas sin mantener un estado interno.
- **Agentes basados en modelos:** Construyen una representación interna del entorno para tomar decisiones más informadas.
- **Agentes basados en objetivos:** Evalúan diferentes acciones en función de un objetivo específico.
- **Agentes basados en utilidad:** Consideran múltiples factores para maximizar una función de utilidad.
- **Agentes de aprendizaje:** Mejoran su comportamiento con el tiempo a través de la experiencia y el aprendizaje automático.

## **2.2 Qué es un LLM?**

Un **Large Language Model (LLM)** es un modelo de inteligencia artificial basado en redes neuronales profundas, entrenado con grandes volúmenes de texto para realizar tareas de procesamiento del lenguaje natural, como generación de texto, traducción automática y respuesta a preguntas. Estos modelos utilizan arquitecturas como **Transformers** para capturar patrones lingüísticos a gran escala. Según Bommasani et al., *"los modelos de lenguaje a gran escala representan un cambio en la forma en que se desarrolla la inteligencia artificial, ya que pueden adaptarse a una amplia gama de aplicaciones sin necesidad de un entrenamiento especializado para cada tarea"* [2].

# 3. Metodología

Se desarrollará un **agente inteligente** capaz de generar materiales didácticos basados en programas de curso universitarios, utilizando **Grandes Modelos de Lenguaje (LLMs)**. Este agente tomará como entrada documentos en formatos comunes (**PDF, TXT, DOCX**) y producirá contenido estructurado como **notas de clase, problemas de práctica, preguntas de discusión, objetivos de aprendizaje y lecturas recomendadas**.

El sistema se implementará en **Python**, aprovechando **PyTorch** para componentes personalizados y garantizando un manejo eficiente de errores y tokens en las llamadas a la API. Además, se diseñará un **marco de evaluación** que permitirá medir la calidad, relevancia y coherencia del contenido generado.
