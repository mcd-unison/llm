# Material de consulta para aprendizaje y uso de LLM 

<img src="https://raw.githubusercontent.com/mcd-unison/llm/main/img/DALL%C2%B7E%202024-05-12%2015.28.49%20-%20A%20conceptual%20image%20representing%20the%20integration%20of%20language%20and%20technology.%20The%20scene%20features%20a%20modern%2C%20sleek%20workspace%20with%20a%20high-tech%20computer%20dis.webp" alt="Computadoras y lenguaje" width="400" height="auto">

Material sobre Grandes Modelos de Lenguajes (LLM) realizado en forma colaborativa. Se espera poder emigrar pronto a una asociación propia, haciendo este espacio abierto no solo a la MCD o a la Universidad de Sonora, si no en forma más abierta.

## Tabla de contenidos
- [Recursos de aprendizaje](#recursos-aprendizaje)
- [Newsletters y otros recursos para mantenerse actualizado](#newsletters)
- [Frameworks de evaluación y visualización de LLM](#evaluación)
- [Frameworks de building and deploying](#buildingdeploy)
- [Monitoreo de aplicaciones LLM](#monitoreo)
- [Tips & Tricks](#tipsandtricks)


## Recursos de aprendizaje<a name="recursos-aprendizaje"></a>

* [Visual Storytelling: Generative AI exists because of the transformer](https://ig.ft.com/generative-ai/)
* [Overview of Large Language Models](https://aman.ai/primers/ai/LLM/).
* [DataTalks.Club](https://datatalks.club/). Manejan cursos gratuitos de MLOps y LLMOps, además de otros recursos importantes.
* [DeepLearning.AI short courses](https://www.deeplearning.ai/short-courses/). Cursos de menos de dos horas para mantenerse actualizado.

## Newsletters y otros recursos para mantenerse actualizado <a name="newsletters"></a>

* [LLM Papers of the Week](https://github.com/dair-ai/ML-Papers-of-the-Week). Un pequeño newsletter en donde te puedes [suscribir](https://github.com/dair-ai/ML-Papers-of-the-Week?tab=readme-ov-file) para que te llegue a tu correo los top 5 mejores papers de la semana de LLM.
* [The AI Index Report](https://aiindex.stanford.edu/report/). Reporte anual de Standford en donde describen las tendencias del momento y los avances de la AI, incluyendo LLM. Sale cada año desde el 2018.
* [The Big Bog of GenAI](https://github.com/mcd-unison/llm/blob/main/documentos/Databricks-Big-Book-Of-GenAI-FINAL.pdf). Documento de Databricks de Inteligencia Artificial Generativa. Incluye un apartado de lenguaje. Para poderlo obtener, era necesario llenar un formulario. Por eso, se sube como material dentro del repositorio.
* [Hugging Face Artificial Analysis LLM Performance Leaderboard](https://huggingface.co/spaces/ArtificialAnalysis/LLM-Performance-Leaderboard).
* [Hugging Face Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard).
* [Hugging Face Chatbot Arena Leaderboard](https://huggingface.co/spaces/lmsys/chatbot-arena-leaderboard). En esta plataforma, LLM devs votan cuales son sus modelos favoritos al momento. El procedimiento de ranking es se lleva de una forma sistematizada y puede consultarse en su artículo de presentación, [Chatbot Arena: An Open Platform for Evaluating LLMs by Human Preference](https://arxiv.org/abs/2403.04132).

## Frameworks de evaluación y visualización de LLM<a name="evaluacion"></a>

* [RAGAS](https://github.com/explodinggradients/ragas). Framework de evaluación open source. Sus ideas de evaluación son simples pero efectivas y creativas. Al día de hoy, 12 de mayo del 2024, cuentan con 9 métricas. Las tres originales se pueden leer en extenso en el [paper original](https://arxiv.org/abs/2309.15217) donde lo proponen.
* [Embedding projector de Tensorflow](https://projector.tensorflow.org/). Permite realizar reducciones de dimensionalidad para identificar como se están agrupando ideas, frases, palabras, etc. Para realizarlo, se utiliza [Tensorboard](https://www.tensorflow.org/tensorboard/tensorboard_projector_plugin?hl=es-419).
* [LDAvis](https://github.com/bmabey/pyLDAvis). Un framework para hacer topic modeling cuando se usa el algoritmo LDA. Hay que tener cuidado de cómo interpretar las gráficas que genera. Para poder entender qué significan, es necesario ir al [paper original](https://aclanthology.org/W14-3110.pdf) donde lo proponen. Está para R y Python.

## Frameworks de building and deploying<a name="buildingdeploy"></a>

* [DIFY](https://github.com/langgenius/dify). Algo asi como un MLflow, pero para LLM.
* [COGNITA](https://github.com/truefoundry/cognita).

## Monitoreo de aplicaciones LLM<a name="monitoreo"></a>

* [Langfuse](https://langfuse.com/). Uso en navegador, pero se puede contenerizar en Docker.
* [Langsmith](https://www.langchain.com/langsmith). Uso en navegador, pero se puede contenerizar en Docker. Es el sistema de monitoreo de langchaing.
* [Phoenix](https://phoenix.arize.com/). No permite un tracking tan profundo de los logs de la solución LLM como langfuse o langsmith, pero si se pueden almacenar. Tiene un muy bien sistema para hacer EDA de informaciónb vectorial que utiliza el LLM, y trae integrados algunos algoritmos de reducción de la dimensionalidad.

## Tips & Tricks<a name="tipsandtricks"></a>
* [ASCIIFlow](https://asciiflow.com/#/). Mejora la documentación de tu código incluyendo diagramas en ASCII del flujo, como en el [siguiente ejemplo](https://twitter.com/ChristianSelig/status/1451193663657164810?t=NFO7jjhDHzDMUEAbNiCJaA&s=08).
* [Sphinx](https://www.sphinx-doc.org/en/master/). Haz la documentación de tu proyecto de una forma bien estilera en un dos por tres con Sphinx.
* [Markdown Cheatsheet en GitHub](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
