# Material de consulta para aprendizaje y uso de LLM 

Material sobre Grandes Modelos de Lenguajes (LLM) realizado en forma colaborativa. Se espera poder emigrar pronto a una asociación propia, haciendo este espacio abierto no solo a la MCD o a la Universidad de Sonora, si no en forma más abierta.

## Tabla de contenidos
- [Recursos de aprendizaje](#recursos-aprendizaje)
- [Newsletters y otros documentos para actualizarse](#newsletters)
- [Frameworks de evaluación](#evaluación)
- [Frameworks de building and deploying](#buildingdeploy)
- [Monitoreo de aplicaciones LLM](#monitoreo)
- [Tips & Tricks](#tipsandtricks)


## Recursos de aprendizaje<a name="recursos-aprendizaje"></a>

* [Visual Storytelling: Generative AI exists because of the transformer](https://ig.ft.com/generative-ai/)
* [Overview of Large Language Models](https://aman.ai/primers/ai/LLM/).
* [DataTalks.Club](https://datatalks.club/). Manejan cursos gratuitos de MLOps y LLMOps, además de otros recursos importantes.
* [DeepLearning.AI short courses](https://www.deeplearning.ai/short-courses/). Cursos de menos de dos horas para mantenerse actualizado.


## Newsletters y otros documentos para actualizarse <a name="newsletters"></a>

* [LLM Papers of the Week][https://github.com/dair-ai/ML-Papers-of-the-Week]. Un pequeño newsletter en donde te puedes [suscribir](https://github.com/dair-ai/ML-Papers-of-the-Week?tab=readme-ov-file) para que te llegue a tu correo los top 5 mejores papers de la semana de LLM.
* [The AI Index Report](https://aiindex.stanford.edu/report/). Reporte anual de Standford en donde describen las tendencias del momento y los avances de la AI, incluyendo LLM. Sale cada año desde el 2018.
* [The Big Bog of GenAI](https://github.com/mcd-unison/llm/blob/main/documentos/Databricks-Big-Book-Of-GenAI-FINAL.pdf). Documento de Databricks de Inteligencia Artificial Generativa. Incluye un apartado de lenguaje. Para poderlo obtener, era necesario llenar un formulario. Por eso, se sube como material dentro del repositorio.

## Frameworks de evaluación<a name="evaluacion"></a>

* [RAGAS](https://github.com/explodinggradients/ragas). Framework de evaluación open source. Sus ideas de evaluación son simples pero efectivas y creativas. Al día de hoy, 12 de mayo del 2024, cuentan con 9 métricas. Las tres originales se pueden leer en extenso en el [paper original](https://arxiv.org/abs/2309.15217) donde lo proponen.

## Frameworks de building and deploying<a name="buildingdeploy"></a>

* [DIFY](https://github.com/langgenius/dify). Algo asi como un MLflow, pero para LLM.
* [COGNITA](https://github.com/truefoundry/cognita).

## Monitoreo de aplicaciones LLM<a name="monitoreo"></a>

* [Langfuse](https://langfuse.com/). Uso en navegador, pero se puede contenerizar en Docker.
* [Langsmith](https://www.langchain.com/langsmith). Uso en navegador, pero se puede ocntenerizar en Docker. Es el sistema de monitoreo de langchaing.
* [Phoenix](https://phoenix.arize.com/). No permite un tracking tan profundo de los logs de la solución LLM como langfuse o langsmith, pero si se pueden almacenar. Tiene un muy bien sistema para hacer EDA de informaciónb vectorial que utiliza el LLM, y trae integrados algunos algoritmos de reducción de la dimensionalidad.

## Tips & Tricks<a name="tipsandtricks"></a>
* [ASCIIFlow](https://asciiflow.com/#/). Mejora la documentación de tu código incluyendo diagramas en ASCII del flujo, como en el [siguiente ejemplo](https://twitter.com/ChristianSelig/status/1451193663657164810?t=NFO7jjhDHzDMUEAbNiCJaA&s=08).
