# Laboratorio 3 en Kotlin

Este proyecto es una aplicación de consola interactiva que implementa algoritmos de ordenamiento y recursividad en Kotlin. Está diseñado para practicar conceptos teóricos en escenarios prácticos mediante la creación de funciones eficientes y bien documentadas.

---

## **Contenido del Proyecto**

El programa presenta las siguientes funcionalidades:

### **1. Ordenar una lista usando Bubble Sort**
- Permite ingresar una lista de números separados por comas.
- Ordena la lista utilizando el algoritmo **Bubble Sort**.
- Muestra el tiempo de ejecución del algoritmo.

### **2. Ordenar una lista usando Quick Sort**
- Similar a la opción anterior, pero utilizando el algoritmo **Quick Sort**.
- Muestra el tiempo de ejecución.

### **3. Calcular el factorial de un número**
- Calcula el factorial de un número entero positivo ingresado por el usuario utilizando recursividad.
- Si el usuario ingresa un valor no válido, muestra un mensaje de error.

### **4. Resolver las Torres de Hanói**
- Resuelve el problema clásico de las Torres de Hanói para un número dado de discos.
- Muestra paso a paso los movimientos necesarios para completar la tarea.

### **5. Salir**
- Finaliza la ejecución del programa.

---

## **Requisitos del Sistema**

### **1. Software necesario**
- Kotlin Compiler ([Descargar](https://kotlinlang.org/)) o un IDE como IntelliJ IDEA ([Descargar](https://www.jetbrains.com/idea/)).
- Java JDK 8 o superior.

### **2. Configuración recomendada**
- Un entorno de desarrollo configurado con soporte para Kotlin.

---

## **Cómo Ejecutar el Proyecto**

### **Opción 1: Usando IntelliJ IDEA**
1. **Crear un proyecto nuevo:**
   - Abre IntelliJ IDEA y selecciona **New Project**.
   - Elige la plantilla **Kotlin/JVM**.
2. **Agregar el archivo de código:**
   - Crea un archivo llamado `LABORATORIO3.kt` dentro de la carpeta `src`.
   - Copia y pega el código fuente proporcionado.
3. **Ejecutar el programa:**
   - Haz clic derecho en el archivo `LABORATORIO3.kt` y selecciona **Run 'MainKt'**.
   - La aplicación se ejecutará en la consola del IDE.

### **Opción 2: Usando la línea de comandos**
1. **Guardar el archivo:**
   - Guarda el código en un archivo llamado `LABORATORIO3.kt`.
2. **Compilar el programa:**
   - Abre la terminal y navega al directorio donde guardaste `LABORATORIO3.kt`.
   - Compila el archivo con:
     ```bash
     kotlinc Main.kt -include-runtime -d Main.jar
     ```
3. **Ejecutar el programa:**
   - Ejecuta el archivo generado con:
     ```bash
     java -jar Main.jar
     ```

---

## **Instrucciones de Uso**
1. Al ejecutar el programa, aparecerá un menú interactivo como este:
   ```
   Seleccione una opción:
   1. Ordenar una lista usando Bubble Sort
   2. Ordenar una lista usando Quick Sort
   3. Calcular el factorial de un número
   4. Resolver las Torres de Hanói
   5. Salir
   ```
2. Ingresa el número de la opción que deseas ejecutar y sigue las indicaciones:
   - Para las opciones de ordenamiento, ingresa una lista de números separados por comas, por ejemplo: `8,3,5,1`.
   - Para el cálculo del factorial, ingresa un número entero positivo.
   - Para las Torres de Hanói, ingresa el número de discos (entero positivo).

3. El programa procesará tu entrada y mostrará los resultados correspondientes en la consola.

---

## **Notas Adicionales**
- **Manejo de errores:** El programa valida las entradas del usuario para evitar fallos.
- **Eficiencia:** Se implementaron algoritmos con una complejidad razonable para cada tarea.
- **Pruebas:** Se recomienda probar el programa con diferentes entradas para verificar su robustez.

---

## **Créditos**
Este laboratorio fue desarrollado como parte de ejercicio práctico de aprendizaje en Kotlin.

