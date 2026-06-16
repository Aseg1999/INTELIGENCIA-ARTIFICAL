# Taller No. 3 - Análisis Estadístico Descriptivo y Visualización de Datos

## Descripción del Proyecto

Este proyecto tiene como objetivo aplicar técnicas de estadística descriptiva para analizar la variable **Apps Descargadas** a partir de una muestra de 50 observaciones. Para ello se utilizaron herramientas de organización, representación gráfica e interpretación de datos, permitiendo identificar patrones y tendencias dentro de la información analizada.

El desarrollo del trabajo incluye la construcción de una tabla de distribución de frecuencias agrupadas, la aplicación de la Regla de Sturges para determinar el número de clases y la elaboración de gráficos estadísticos que facilitan la comprensión de los resultados obtenidos.

## Objetivos

### Objetivo General

Aplicar métodos de estadística descriptiva para organizar, representar e interpretar un conjunto de datos relacionados con la cantidad de aplicaciones descargadas por los usuarios.

### Objetivos Específicos

* Identificar las características principales de la variable estudiada.
* Calcular medidas básicas necesarias para la agrupación de datos.
* Construir una tabla de distribución de frecuencias.
* Elaborar representaciones gráficas de la información.
* Analizar e interpretar los resultados obtenidos.

## Estructura del Repositorio

```text
├── Taller_destadistica_descritiva-frecuencias_Santiago.xlsx
├── INFORME.docx
└── README.md
```

### Taller_destadistica_descritiva-frecuencias_Santiago.xlsx

Este archivo contiene el desarrollo completo de los cálculos estadísticos realizados durante el taller:

* Datos originales de la muestra.
* Cálculo del rango.
* Aplicación de la Regla de Sturges.
* Determinación del número de clases.
* Cálculo de la amplitud de clase.
* Tabla de frecuencias.
* Frecuencia absoluta.
* Frecuencia acumulada.
* Frecuencia relativa.
* Frecuencia relativa acumulada.
* Marcas de clase.
* Gráficos estadísticos.

### INFORME.docx

Documento que presenta la interpretación y análisis de los resultados obtenidos, incluyendo:

* Introducción.
* Datos generales.
* Explicación de la tabla de frecuencias.
* Análisis del histograma.
* Análisis del polígono de frecuencias.
* Análisis de la ojiva.
* Interpretación de resultados.
* Conclusiones.

## Metodología

### Paso 1. Identificación de la variable

La variable analizada corresponde a la cantidad de aplicaciones descargadas por cada usuario.

Tipo de variable:

* Cuantitativa discreta.

### Paso 2. Obtención de datos básicos

Se trabajó con una muestra de 50 observaciones.

Datos obtenidos:

| Concepto     | Valor |
| ------------ | ----- |
| Valor mínimo | 30    |
| Valor máximo | 132   |
| Rango        | 102   |

El rango fue calculado mediante:

```text
Rango = Valor máximo - Valor mínimo
Rango = 132 - 30
Rango = 102
```

### Paso 3. Aplicación de la Regla de Sturges

Se utilizó la fórmula:

```text
K = 1 + 3.322 log(n)
```

Sustituyendo:

```text
K = 1 + 3.322 log(50)
K ≈ 6.64
```

Por aproximación:

```text
K = 7 clases
```

### Paso 4. Cálculo de la amplitud

La amplitud se calculó utilizando:

```text
A = R / K
```

Sustituyendo:

```text
A = 102 / 7
A ≈ 14.57
```

Se tomó una amplitud de:

```text
A = 15
```

### Paso 5. Construcción de la tabla de frecuencias

Con los intervalos definidos se construyó la tabla de distribución de frecuencias, calculando:

* Frecuencia absoluta.
* Frecuencia acumulada.
* Frecuencia relativa.
* Frecuencia relativa acumulada.
* Marca de clase.

### Paso 6. Elaboración del histograma

El histograma permitió visualizar la distribución de las observaciones.

Resultado principal:

* El intervalo entre 60 y 75 aplicaciones presentó la mayor frecuencia.

### Paso 7. Elaboración del polígono de frecuencias

Esta gráfica permitió observar la tendencia general de los datos y evidenciar la concentración de observaciones en los intervalos centrales.

### Paso 8. Elaboración de la ojiva

La ojiva permitió analizar el comportamiento acumulado de la distribución.

Resultados observados:

* Aproximadamente el 46% de los usuarios descargó menos de 75 aplicaciones.
* Aproximadamente el 80% descargó menos de 105 aplicaciones.

## Resultados

| Indicador                              | Resultado |
| -------------------------------------- | --------- |
| Número de observaciones                | 50        |
| Valor mínimo                           | 30        |
| Valor máximo                           | 132       |
| Rango                                  | 102       |
| Número de clases                       | 7         |
| Amplitud                               | 15        |
| Intervalo de mayor frecuencia          | 60 - 75   |
| Usuarios con menos de 105 aplicaciones | 80%       |

## Conclusiones

* La estadística descriptiva permitió organizar y analizar adecuadamente la información obtenida.
* La Regla de Sturges facilitó la construcción de una distribución de frecuencias apropiada para el estudio.
* El intervalo entre 60 y 75 aplicaciones registró la mayor concentración de usuarios.
* La mayoría de las observaciones se encuentra ubicada en los intervalos centrales de la distribución.
* La ojiva permitió determinar que el 80% de los usuarios posee menos de 105 aplicaciones descargadas.
* Los resultados muestran una tendencia hacia valores intermedios y una menor presencia de observaciones extremas.

## Autor

Ángel Santiago Estupiñán Gómez

Programa de Ingeniería de Sistemas

Universidad del Pacífico

## Docente

Wilman Andrés Quiñónez Valencia

## Asignatura

Inteligencia Artificial – Corte II – 2026-1
