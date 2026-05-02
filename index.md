<div align= "center">

  <img src= "https://redi.cedia.edu.ec/members/UNL.png" width= "230px"/> <br>
  # UNIVERSIDAD NACIONAL DE LOJA  
  ## FACULTAD DE LA ENERGÍA, LAS INDUSTRIAS Y LOS RECURSOS NATURALES NO RENOVABLES 
  ## CARRERA DE COMPUTACIÓN 
  <br> <br>
  ### ASIGNATURA 
  ### TEORÍA DE LA PROGRAMACIÓN 
  <br> <br>
  ### CICLO 
  ### 1er CICLO "A" 
  <br> <br>
  ### PERÍODO ACADÉMICO 
  ### 2026 <br>
  <br> <br>
  ### DOCENTE 
  ### ING. LISSETE LÓPEZ 
  <br> <br>
  ### ESTUDIANTE 
  ### CAMILA ANABEL BELTRÁN RAMÍREZ 
  <br> <br>
  ---
</div>

<br> <br> <br>

<div align="center">
  
## SECCIONES DEL PORTAFOLIO
  
[![Unidad 1](https://img.shields.io/badge/UNIDAD_1-4CAF50?style=for-the-badge)](#unidad-1) <br>
[![Unidad 2](https://img.shields.io/badge/UNIDAD_2-F44336?style=for-the-badge)](#unidad-2)<br>
[![Unidad 3](https://img.shields.io/badge/UNIDAD_3-4CAF50?style=for-the-badge)](#unidad-3)<br>
[![Coclusiones Generales](https://img.shields.io/badge/CONCLUSIONES_GENERALES-F44336?style=for-the-badge)](#conclusiones-generales)<br>
[![Bibliografía](https://img.shields.io/badge/BIBLIOGRAFÍA-4CAF50?style=for-the-badge)](#bibliografía)<br>
[![Declaración_uso_de_IA](https://img.shields.io/badge/DECLARACIÓN_USO_DE_IA-F44336?style=for-the-badge)](#declaración-uso-de-ia)<br>


</div>

<br><br>

# Unidad 1
## ***1. Contenidos Teóricos***
>### ***A. Algoritmo*** 
- #### Un algoritmo es una secuencia de pasos lógicos, definidos y finitos que deben seguirse para realizar una tarea y resolver un problema determinado.
<div align="center">
  Ejemplo: <p>
  <img src="https://capiremov.org/wp-content/uploads/2021/07/algoritmo.jpg" width= "400px"/> 
</div>

>### ***B. Pseudocódigo***
- #### El pseudocódigo es una forma de representar un algoritmo mediante una mezcla del lenguaje coloquial (español o ingles) y las estructuras de programación, permitiendo planificar la lógica y simplificar los pasos que un algoritmo debe seguir.
<div align="center">
  Ejemplo: <p>
  <img width="679" height="380" alt="Image" src="https://github.com/user-attachments/assets/1d027a2a-0aa9-458d-8f5e-a981a5cb50de"/>
</div>

>### ***C. Diagrama de Flujo***
- #### El diagrama de flujo es una herramienta gráfica que nos permite analizar y visualizar la lógica de un codigo mediante símbolos geométricos que muestran la secuencia de pasos lógicos. 
<div align="center">
  Ejemplo: <p>
  <img width="452" height="672" alt="Image" src="https://github.com/user-attachments/assets/8f578b07-977b-4863-a8cd-89f4f1e9aafb"/> 
</div>

>### ***D. Prueba de Escritorio***
- #### Las pruebas de escritorio son ejercicios manuales que nos permiten comprobar lógicamente un algoritmo, detectando errores en la lógica o dentro de los cálculos matemáticos y verificando el comportamiento del código paso a paso. 
<div align="center">
  Ejemplo: <p>
  <img width="605" height="244" alt="Image" src="https://github.com/user-attachments/assets/f0280685-398e-47dc-a400-25817be55f19"/>
</div>

>### ***E. Lenguajes de Programación*** 
#### Los lenguajes de programación son herramientas que nos permiten mediante la comunicación entre el pensamiento lógico y el hardware de un computador. Dentro de los lenguajes de programación hay varios niveles:
- Lenguajes de pseudocódigo: Se enfocan en facilitar la comprensión para quien maneja el lenguaje, en esta sección es donde se utiliza "PSeInt", que nos permite estructurar la lógica que esta dentro del algoritmo mediante un pseudocódigo y diagramas de flujo.
- Lenguajes de programación estructurada: Son lenguajes que nos permiten un control más directo sobre el sistema. Durante esta unidad se trabajo con "C", un lenguaje de nivel medio que exige el manejo de librerías, tipos de datos y una sintaxis estricta.

>### ***F. Programación por Bloques***
- #### La programación por bloques es un método visual diseñado para principiantes y niños que consta en crear software arrastrando y ensamblando piesas lógicas (bloques) en lugar de escribir el código por texto. 
<div align="center">
  Ejemplo: <p>
  <img src= "https://formacion.intef.es/aulaenabierto/pluginfile.php/6032/mod_book/chapter/6589/imagen%20%2810%29.png" width= "350px"/> 
</div>

---

## 2. Ejercicio con Estructura Secuencial

>### ***A. Planteamiento del problema***
- #### ***Problema:*** "Se requiere diseñar un algoritmo para una estación de servicio que automatice el cobro de combustible. Debido a que los surtidores miden el volumen en galones, pero el precio oficial está regulado por litro ($0.72 USD), el sistema debe solicitar la cantidad de galones despachados y realizar la conversión técnica necesaria (1 galón = 3.785 litros) para emitir una factura con el total a pagar por el cliente."

>### ***B. Análisis del problema***
#### ***1. Datos de Entrada:*** 
- #### Cantidad de galones ingresados por el usuario.<p>
#### ***2. Procesos:*** 
- #### Conversión de galones a litros (Litro = Galón * 3.785). <p>
- #### Calcular el monto total a pagar (Precio = Litro * 0.72). <p>
#### ***3. Salida:*** 
- #### La cantidad de galones convertida a litros y el valor total a cancelar por cada litro en dólares. <p>

>### ***C. Diseño del algoritmo***

#### ***1. Pseudocódigo***
- ##### ***Pseudocódigo en PSeInt:***
<div align="center">
  <img width="782" height="609" alt="Image" src="https://github.com/user-attachments/assets/409e71fc-e9b7-4a3f-9850-e4fddab35dc0"/>
</div>

#### ***2. Diagrama de Flujo*** 
<div align="center">
  <img width="474" height="675" alt="Image" src="https://github.com/user-attachments/assets/2bd1a890-e029-4a32-934a-099274ba661e"/>
 </div>

>### ***D. Codificación***
#### ***1. Codificación en C***
<div align="center">
  <img width="965" height="673" alt="Image" src="https://github.com/user-attachments/assets/7b96231d-6125-4825-9eb2-f290bf58e60a"/>
</div>

>### ***E. Validación***
- #### Para comprobar el correcto funcionamiento del pseudocódigo elaborado mediante pseint y c, realizamos la siguiente prueba de escritorio:
<div align="center">
  <img width="537" height="442" alt="Image" src="https://github.com/user-attachments/assets/bae10b52-dbc7-4748-8ec7-ed983b7e8d82"/>
</div>

---

## 3. Reflexión Crítica
- #### Durante el proceso de esta primera unidad he podido comprender que para poder programar necesito mejorar mi análisis lógico para poder resolver problemas mediante algoritmos de forma eficiente y rapida. Además durante el transcurso de la unidad 1, logré conocer varios lenguajes de programación que son muy utilizados, herramientas como PSeInt son muy esenciales cuando estamos empezando dentro del mundo de la programación ya que nos permite analizar el algoritmo mediante el pseudocódigo y el diagrama de flujo, permitiendo descomponer problemas complejos en pasos secuenciales faciles de seguir. Posteriormente, al migrar hacia el lenguaje C he adquirido aún más conocimientos sobre las miles de funciones que tiene este lenguaje, desde la declaración de variables hasta las diferentes librerias que existen y que resuelven muchos problemas. Para finalizar, esta unidad me ha llamado mucho la atención y me ha permitido familiarizarme con los lenguajes de programación (PSeInt y C) logrando transformar mi perspectiva al mejorar mi comprensión lógica para resolver problemas mediante algoritmos.

<br>

<div align="center">
  
[![Secciones del portafolio](https://img.shields.io/badge/SECCIONES_DEL_PORTAFOLIO-4CAF50?style=for-the-badge)](#secciones-del-portafolio) <br>
</div>

<p><p>
  
---
  
# Unidad 2
## NO APLICA
<br><br>

---

# Unidad 3
## NO APLICA
<br><br>

---

# Conclusiones Generales
## NO APLICA
<br><br>

---

# Bibliografía
#### [1] P. Novara, "PSeInt: Intérprete de pseudocódigo," 2024. [En línea]. Disponible en: http://pseint.sourceforge.net/
#### [2] Microsoft, "Visual Studio Code," v. 1.88, 2024. [En línea]. Disponible en: https://code.visualstudio.com/
#### [3] Google Mind, "Gemini: Modelo de lenguaje de gran escala," 2024. [En línea]. Disponible en: https://gemini.google.com/
<br><br>

<div align="center">
  
[![Secciones del portafolio](https://img.shields.io/badge/SECCIONES_DEL_PORTAFOLIO-4CAF50?style=for-the-badge)](#secciones-del-portafolio) <br>
</div>

---

# Declaración uso de IA
- #### Para el desarrollo de este portafolio digital, se ha utilizado la ayuda de la inteligencia artificial "Gemini" como herramienta de soporte técnico, apoyandome durante el proceso para ordenar los contenidos y el diseño estético mediante el uso de Markdown, como el uso de etiquetas de html para centrar textos, la integración de imágenes y el diseño de botónes funcionales dentro de mi portafolio digital. 
<br><br>

<div align="center">
  
[![Secciones del portafolio](https://img.shields.io/badge/SECCIONES_DEL_PORTAFOLIO-4CAF50?style=for-the-badge)](#secciones-del-portafolio) <br>
</div>

---
