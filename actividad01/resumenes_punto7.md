# Resúmenes de Documentos (Punto 7)

## 1. Resumen de: 0-ingenieria-del-conocimiento.pdf
Este documento aborda los fundamentos y los procesos principales de la Ingeniería del Conocimiento (IC), una rama de la Inteligencia Artificial encargada de desarrollar sistemas basados en el conocimiento, como los Sistemas Expertos.

* **Conceptos y roles básicos:** Define el conocimiento y establece los roles del Ingeniero de Conocimiento (especialista informático), el Experto Humano (quien aporta la experiencia) y el Usuario.
* **Procesos fundamentales:** La IC se compone de cinco procesos clave: Adquisición, Representación, Validación, Inferencia y Explicación o Justificación del conocimiento.
* **Adquisición del conocimiento:** Es la fase central donde se extrae información de fuentes estáticas (documentos) o dinámicas (el experto). Para ello, se utilizan métodos manuales (entrevistas, análisis de protocolos), semiautomatizados (herramientas de soporte) y automatizados (inducción de reglas y aprendizaje automatizado).
* **Representación del conocimiento:** Consiste en estructurar el conocimiento adquirido para que el sistema lo entienda y procese. Se utilizan diversos esquemas como reglas de lógica simbólica, redes semánticas, árboles de decisiones, *frames* (marcos) y gráficos conceptuales.

## 2. Resumen de: C-sistemasExpertosBasadosEnReglas.pdf
Este documento detalla la estructura y el funcionamiento lógico de los sistemas expertos deterministas que utilizan reglas para resolver problemas.

* **Base de conocimiento:** Está conformada por los "hechos", que son dinámicos y temporales, y por las "reglas", que son estáticas y definen las relaciones lógicas mediante una premisa (antecedente) y una conclusión (consecuente).
* **Motor de Inferencia:** Es el componente que deduce nueva información aplicando reglas de inferencia clásicas, principalmente el *Modus Ponens* (que avanza de la premisa a la conclusión), el *Modus Tollens* (que retrocede de una conclusión falsa a una premisa falsa) y el mecanismo de resolución para conclusiones compuestas.
* **Estrategias de encadenamiento:** Explica cómo el sistema puede encadenar reglas hacia adelante (a partir de los hechos conocidos hasta llegar a nuevas conclusiones) o utilizar un encadenamiento orientado a un objetivo (partiendo de una meta y buscando los hechos que la validen).
* **Control de la Coherencia:** Subraya la necesidad de verificar que tanto las reglas como los hechos ingresados al sistema no sean contradictorios, eliminando valores no factibles para evitar conclusiones absurdas.
* **Explicación de conclusiones:** Indica que el sistema debe ser capaz de justificar sus resultados ante el usuario, listando los hechos deducidos junto con las reglas exactas que provocaron dicha conclusión.
