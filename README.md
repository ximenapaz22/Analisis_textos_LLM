# Analisis Automatizado de Textos Historicos con Modelos de Lenguaje

## Descripcion

Este proyecto desarrolla un sistema para el analisis automatizado de textos historicos utilizando modelos de lenguaje de gran escala (LLMs).

El objetivo es transformar documentos extensos en una estructura organizada de informacion que permita su analisis sin necesidad de realizar una lectura manual completa.

El sistema busca apoyar el trabajo de especialistas mediante la extraccion automatizada de entidades, conceptos y relaciones presentes en los textos.

## Objetivos

- Procesar textos historicos de manera automatizada.
- Extraer entidades y relaciones relevantes.
- Generar una estructura organizada de conocimiento.
- Reducir el tiempo de exploracion documental.
- Validar cualitativamente los resultados con un especialista.

## Metodologia

El flujo general del sistema es el siguiente:

1. Carga de documentos historicos.
2. Limpieza basica del texto.
3. Division en fragmentos (chunking) para facilitar el procesamiento.
4. Uso de modelos de lenguaje para:
   - Identificar entidades.
   - Detectar relaciones.
   - Clasificar conceptos.
5. Generacion de salidas estructuradas.
6. Evaluacion cualitativa de los resultados.

## Tecnologias utilizadas

- Python
- Ollama (ejecucion local de modelos)

## Sobre el Prompt

El desempeno del sistema depende directamente del diseno del prompt utilizado con el modelo.

Se emplearon instrucciones explicitas y restricciones de formato para mejorar la consistencia de las respuestas. Variaciones en el prompt pueden afectar significativamente la calidad y precision de la informacion extraida.

## Limitaciones

- Sensibilidad a ambiguedad historica.
- Posibles inferencias incorrectas generadas por el modelo.
- Dependencia del contexto proporcionado.
- Revision de un especialista.
