# Un modelo robusto para maximizar la propagación de la influencia en redes sociales

## Extracto Ejecutivo de Investigación
Este repositorio contiene un documento con el Resumen, Abstract y Prólogo de mi Trabajo de Fin de Grado (TFG) en Matemáticas por la Universidad de Sevilla. 

> **Nota para Responsables de Selección y Equipos Técnicos:**  
> El documento adjunto es un extracto introductorio del proyecto. La **memoria completa de la investigación**, así como los códigos de programación desarrollados (R, AMPL y Python) y los resultados del estudio computacional, están disponibles y se muestran bajo petición en fase de entrevista técnica. Puedes contactar conmigo directamente a través de mi correo electrónico o mi perfil de LinkedIn.

---

## Enfoque Matemático y Metodología Destacada
En este proyecto abordo el problema de optimización combinatoria (NP-completo) de selección de nodos clave en redes complejas bajo escenarios de alta incertidumbre:

* **Optimización Robusta:** Implementación de un modelo analítico basado en la metodología de Bertsimas y Sim (2004), *The price of robustness*, asumiendo un modelo de incertidumbre donde los parámetros de influencia varían de forma acotada.
* **Resolución Exacta:** Formulación matemática basada en conjuntos minimales de activación, aplicando un algoritmo exacto del tipo **Branch-Cut-and-Price** con el **método de generación de columnas** (basado en la literatura de Nannicini et al., 2020).
* **Desarrollo Propio:** Diseño, programación y validación computacional de un **algoritmo heurístico de elaboración propia** para optimizar la eficiencia algorítmica y minimizar los tiempos de cómputo frente a los métodos exactos tradicionales.

---

## Tecnologías Aplicadas en el Estudio
* **AMPL:** Modelado matemático y conjuntos de restricciones.
* **R:** Procesamiento de matrices de datos, simulación experimental del modelo y ejecución del algoritmo heurístico propio.

---

## Autora
* **Patricia Jiménez Sanabria** - Graduada en Matemáticas (Universidad de Sevilla).
