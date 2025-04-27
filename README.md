[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zmvs671/ProbBayes_AlgoritGeneticos.git/HEAD)

Accese a este repositorio haciendo click en la insignia azul de arriba o en la siguiente URL:
https://mybinder.org/v2/gh/zmvs671/ProbBayes_AlgoritGeneticos.git/HEAD

================================================================================

## Proyecto 1: Crecimiento poblacional en México

**Objetivo:**  
Este proyecto tiene como objetivo ajustar una función logística a los datos reales de la población de México entre 1940 y 2023. La función logística se utiliza para modelar el crecimiento de la población, considerando un límite de saturación y una tasa de crecimiento que varía a lo largo del tiempo.

**Metodología:**  
Se parte de una función logística con parámetros iniciales \(x_0\), \(a\), y \(b\), que representan la población inicial, la tasa de crecimiento y el límite de saturación, respectivamente. A través de un algoritmo genético, se ajustan estos parámetros mutándolos mediante ruido gaussiano. Se busca encontrar los parámetros óptimos para que la curva ajustada se aproxime lo más posible a los datos reales de la población, evaluando el número de mutaciones y el tiempo para alcanzar el límite de saturación.

**Preguntas clave:**  
- ¿Cuáles son los valores óptimos de los parámetros \(x_0\), \(a\), y \(b\)?
- ¿Cuántas mutaciones efectivas se necesitan por parámetro?
- ¿Cuánto tiempo tarda en alcanzarse el límite de saturación?
- Reflexión sobre la importancia de reducir la tasa de crecimiento poblacional.

---

## Proyecto 2: Crecimiento acumulado de personas con VIH-SIDA en México

**Objetivo:**  
Este proyecto replica el análisis del Proyecto 1, pero con los datos de casos de VIH-SIDA en México. El objetivo es aplicar la función logística para modelar el crecimiento acumulado de casos, a partir de los datos de nuevos casos reportados anualmente.

**Metodología:**  
Al igual que en el Proyecto 1, se utiliza una función logística, pero en este caso, se parte de datos de casos nuevos, que deben convertirse en casos acumulados para aplicar la función. Los parámetros iniciales, la tasa de crecimiento y el límite de saturación se definen según la dinámica del VIH-SIDA en México. Los usuarios deberán establecer sus propios parámetros iniciales y desviaciones estándar para el algoritmo genético.

**Preguntas clave:**  
- ¿Cuántos años faltan para que se alcance la saturación de casos acumulados?
- ¿Cuál es el valor de saturación de los casos de VIH-SIDA?
- Reflexión sobre si el VIH-SIDA sigue siendo un problema grave y si es necesario mejorar los programas de atención.

---

Estos proyectos utilizan técnicas de ajuste de parámetros mediante algoritmos genéticos para modelar fenómenos poblacionales en México, con un enfoque en el análisis de datos reales y la reflexión sobre los impactos sociales de estos problemas.
