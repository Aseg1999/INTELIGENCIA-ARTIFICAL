# INTELIGENCIA-ARTIFICAL
# Proyecto de Grafos en Python: BFS y DFS con Animación

## Autor
Ángel Santiago Estupiñán Gómez

---

## 1. Descripción general del proyecto

En este proyecto se desarrolló un programa en Python para trabajar con **grafos**, aplicando dos algoritmos de recorrido muy importantes en informática:

- **BFS (Breadth-First Search)**, también llamado búsqueda en anchura.
- **DFS (Depth-First Search)**, también llamado búsqueda en profundidad.

El objetivo principal fue **mostrar de forma visual y práctica cómo funciona cada algoritmo**, utilizando **dos grafos diferentes**, de manera que el recorrido de uno no se pareciera al del otro.

Además, el programa no solo muestra el resultado en texto, sino que también presenta una **animación lenta y paso a paso**, donde se puede observar cómo cada algoritmo va recorriendo su respectivo grafo.

---

## 2. Objetivo del trabajo

El objetivo de este proyecto fue:

- Implementar el algoritmo **BFS**.
- Implementar el algoritmo **DFS**.
- Usar **dos grafos diferentes** para observar mejor sus diferencias.
- Mostrar el recorrido de cada algoritmo de forma visual.
- Explicar automáticamente qué hace cada grafo y qué algoritmo se aplicó.
- Subir el desarrollo a **GitHub** como evidencia del trabajo.

---

## 3. Herramientas utilizadas

Para desarrollar este proyecto se utilizaron las siguientes herramientas:

- **Google Colab**: para escribir y ejecutar el código en Python.
- **Python**: lenguaje de programación usado en el proyecto.
- **GitHub**: para almacenar y compartir el proyecto.
- **NetworkX**: librería para trabajar con grafos.
- **Matplotlib**: librería para dibujar los grafos.
- **IPython Display**: para mostrar la animación paso a paso en Colab.

---

## 4. Explicación paso a paso de lo que se hizo

### Paso 1: Crear el proyecto en Google Colab
Primero se abrió un cuaderno en Google Colab para escribir y ejecutar el código del proyecto.

Allí se instalaron e importaron las librerías necesarias para:

- construir grafos,
- dibujarlos,
- recorrerlos,
- y mostrar la animación paso a paso.

---

### Paso 2: Definir dos grafos diferentes
Se crearon **dos grafos** con estructuras distintas:

#### Grafo 1
Este grafo fue diseñado para aplicar **BFS**, ya que su forma permite observar claramente cómo el algoritmo visita primero los nodos más cercanos al nodo inicial.

#### Grafo 2
Este grafo fue diseñado para aplicar **DFS**, ya que su forma permite observar cómo el algoritmo profundiza por una rama antes de regresar.

La razón de usar dos grafos diferentes fue que el profesor pidió comparar comportamientos, y si ambos grafos fueran muy parecidos, el recorrido también podría verse parecido.

---

### Paso 3: Implementar el algoritmo BFS
Luego se programó el algoritmo **BFS (Breadth-First Search)**.

Este algoritmo funciona con una **cola**, lo que significa que recorre el grafo **por niveles**.

Su comportamiento es:

1. Empieza en el nodo inicial.
2. Visita primero los nodos vecinos más cercanos.
3. Después pasa al siguiente nivel.
4. Continúa hasta recorrer todo el grafo.

En este proyecto, BFS se aplicó al primer grafo.

---

### Paso 4: Implementar el algoritmo DFS
Después se programó el algoritmo **DFS (Depth-First Search)**.

Este algoritmo funciona con una **pila**, lo que significa que se va **profundizando por un camino** antes de regresar.

Su comportamiento es:

1. Empieza en el nodo inicial.
2. Sigue una rama lo más profundo posible.
3. Cuando ya no puede avanzar, retrocede.
4. Luego explora otra rama.

En este proyecto, DFS se aplicó al segundo grafo.

---

### Paso 5: Guardar los estados del recorrido
Mientras cada algoritmo recorría su grafo, el programa fue guardando cada paso realizado.

Esto se hizo para que luego se pudiera mostrar la animación de forma progresiva, es decir:

- primer nodo visitado,
- luego segundo nodo,
- luego tercero,
- y así sucesivamente.

Gracias a eso, la animación no se ve de golpe, sino paso a paso.

---

### Paso 6: Dibujar cada grafo
Después de obtener los recorridos, se dibujó cada grafo en pantalla.

Para esto se usaron posiciones fijas de los nodos, con el fin de que:

- el grafo se viera ordenado,
- fuera fácil de entender,
- y la animación se apreciara mejor visualmente.

Durante la animación:

- el **nodo actual** aparece resaltado,
- los **nodos ya visitados** cambian de color,
- y el recorrido realizado aparece escrito en la parte inferior.

---

### Paso 7: Mostrar la animación lenta
Una parte importante del proyecto fue hacer que la animación fuera **lenta y por separado**.

Primero se reproduce el recorrido del **grafo BFS**.  
Cuando termina, se pasa al **grafo DFS**.

Esto permite observar mejor la diferencia entre ambos algoritmos, en lugar de mostrar los dos al mismo tiempo.

---

### Paso 8: Mostrar una explicación final automática
Al terminar las animaciones, el programa imprime una explicación en texto donde se indica:

- qué algoritmo se usó en cada grafo,
- cuál fue el recorrido obtenido,
- y cuál es la diferencia entre BFS y DFS.

Esto se hizo para que el programa no solo funcione, sino que también explique el resultado de forma automática.

---

## 5. Qué hace cada algoritmo

### BFS (Breadth-First Search)
BFS significa búsqueda en anchura.

Su principal característica es que recorre el grafo **por niveles**, es decir:

- primero el nodo inicial,
- luego sus vecinos más cercanos,
- después los vecinos de esos vecinos,
- y así sucesivamente.

Este algoritmo usa una **cola**.

#### Ventaja
Sirve mucho cuando se quiere explorar primero lo más cercano al punto de inicio.

---

### DFS (Depth-First Search)
DFS significa búsqueda en profundidad.

Su principal característica es que recorre el grafo **profundizando por una rama** antes de regresar.

Este algoritmo usa una **pila**.

#### Ventaja
Sirve mucho cuando se quiere explorar completamente un camino antes de probar otro.

---

## 6. Diferencia entre BFS y DFS

La diferencia principal entre ambos algoritmos es la forma en que recorren el grafo:

### BFS
- Recorre por niveles.
- Usa una cola.
- Explora primero lo más cercano.

### DFS
- Recorre en profundidad.
- Usa una pila.
- Explora primero una rama completa.

En este proyecto esa diferencia se puede observar claramente porque se usaron **dos grafos distintos**, diseñados para que el comportamiento no se pareciera.

---

## 7. Resultado del proyecto

El programa permite observar tres cosas importantes:

1. **El recorrido en texto** de cada algoritmo.
2. **La animación paso a paso** del recorrido.
3. **La explicación final automática** sobre lo que hace cada uno.

De esta forma, el proyecto no solo cumple con ejecutar BFS y DFS, sino que también permite entenderlos visualmente.

---

## 8. Estructura del repositorio

Dentro del repositorio se encuentran archivos como los siguientes:

- `grafos_bfs_dfs.ipynb` → archivo principal del proyecto hecho en Google Colab.
- `README.md` → documento explicativo del proyecto.
- Otros archivos generados si se descargan imágenes o resultados adicionales.

---

## 9. Cómo ejecutar el proyecto

Para ejecutar este proyecto se deben seguir estos pasos:

### 1.
Abrir el archivo `.ipynb` en **Google Colab**.

### 2.
Ejecutar todas las celdas del cuaderno.

### 3.
Esperar a que el programa muestre primero el recorrido de **BFS**.

### 4.
Observar la animación lenta del primer grafo.

### 5.
Esperar a que el programa cambie automáticamente al segundo grafo.

### 6.
Observar la animación lenta de **DFS**.

### 7.
Leer la explicación final generada por el programa.

---

## 10. Conclusión

Este proyecto permitió implementar y comprender los algoritmos **BFS** y **DFS** mediante el uso de grafos y animaciones.

La parte más importante del trabajo fue que no se usó un solo grafo para ambos casos, sino **dos grafos diferentes**, con el fin de que el recorrido de cada algoritmo se viera diferente y fuera más fácil de analizar.

Gracias a esto, el proyecto muestra de manera clara que:

- **BFS** recorre por niveles,
- **DFS** recorre en profundidad,
- y ambos algoritmos, aunque sirven para explorar grafos, lo hacen de manera distinta.

Además, la animación lenta y la explicación automática hacen que el proyecto sea más didáctico, entendible y completo.

---

## 11. Observación final

Este trabajo fue desarrollado en Google Colab, descargado posteriormente y subido a un repositorio en GitHub, junto con este archivo README, como evidencia del proceso realizado y del funcionamiento del programa.
