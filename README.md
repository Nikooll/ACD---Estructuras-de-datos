# ACD-Estructuras-de-datos

## UML

![ACD_EstructurasDatos](https://github.com/user-attachments/assets/dc534dcc-6528-4225-9669-28346277ff82)


## 1. Estructura General

Clase Abstracta 

**EstructuraDatos:**

Esta clase es la cual heredan otras clases que manejan estructuras de datos. 

## 2. Clase Nodo:


Representa un nodo, que es la unidad básica de muchas estructuras de datos.

## 3. Clases que Extienden Nodo:

**NodoSimple:** Tiene atributos izquierda y derecha.
**NodoDoble:** Tiene atributos de NodoSimple, también contiene siguiente y anterior, permitiendo recorrer la estructura en ambas direcciones.


## 4. Clase Lista:

Representa una lista, con atributos como cabeza (primer nodo), cola (último nodo), y tamano (número de elementos).
Métodos como recorrer(), vaciar(), y obtenerTamano() permiten manipular y obtener información sobre la lista.


## 5. Subclases de Lista:

ListaSimple: Permite obtener un elemento en una posición específica y agregar elementos después de otro.
ListaDoblemente: Extiende Lista para soportar operaciones como obtener el primer y último elemento de manera eficiente.
ListaEnlazadaSimple: Verifica si la lista está vacía con el método estaVacia().
ListaCircularSimple: Permite operaciones de lista circular como agregar al inicio, eliminar el último y recorrer circularmente.
ListaDoblementeCircular: Combina características de lista doblemente enlazada y lista circular.
ListaDoblementeEnlazada: Permite verificar si la lista está vacía.


## 6. Clase ArbolBinario:

Representa un árbol binario con atributos como raiz, altura, subizq, subder, niveles, y numeroRamas.
Métodos incluyen buscarValor(), varios métodos de recorrido (inOrden, postOrden, preOrden), y métodos para obtener características del árbol como altura, número de ramas, entre otros.


## 7. Subclases de ArbolBinario:

**ArbolAVL:** Contiene operaciones de rotación simple y doble para mantener el balance del árbol.
**ArbolRojoNegro:** Contiene rotaciones izquierda y derecha.


## 8. Clase Grafo:

Modela un grafo usando listas para nodos (nodo) y aristas (arista).
Métodos que incluyen agregarNodo, agregarArista, eliminarNodo, y eliminarArista.


## 9. Clase Arista:

Representa una conexión entre dos nodos, con atributos origen y destino.
Métodos que permiten establecer y obtener los nodos origen y destino.


## 10. Enum Color:

Define dos posibles valores: ROJO y NEGRO.
