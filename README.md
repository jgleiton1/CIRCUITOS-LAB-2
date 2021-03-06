# CIRCUITOS-LAB-2

**1. Objetivos**


***
   **1.1. Objetivo General** 


Comprobar el cumplimiento de la técnica de análisis de mallas, mediante el análisis de los circuitos eléctricos, las simulaciones y las prácticas de laboratorio físicas, para afianzar los conocimientos adquiridos en clase.

  **1.2. Objetivos Específicos:**
   
-Resumir que es el análisis de mallas, la ley de Kirchhoff de Voltajes y la ley de la conservación de la carga, a partir de una búsqueda bibliográfica.
   
-Calcular las medidas de cada una de las corrientes de las mallas, mediante la construcción del circuito de forma física, simulador de Tinkercad y ecuaciones algebraicas aplicando el análisis de las mallas.

-Justificar el desarrollo del laboratorio, mediante la presentación de un video, en el que se explique el funcionamiento y la implementación del proyecto.

***

**2. Marco Teórico**

![WhatsApp Image 2022-05-26 at 8 47 46 AM](https://user-images.githubusercontent.com/94011974/170503573-9f2199ea-69e2-4acd-bd09-77208cd3f1c6.jpeg)

![WhatsApp Image 2022-05-26 at 8 48 13 AM](https://user-images.githubusercontent.com/94011974/170503616-725587dd-fdc5-4de9-8418-7388aee8509a.jpeg)

![WhatsApp Image 2022-05-26 at 8 48 34 AM](https://user-images.githubusercontent.com/94011974/170503676-6d3f92d3-eacd-49d0-8794-907554649f8c.jpeg)

![WhatsApp Image 2022-05-26 at 8 49 10 AM](https://user-images.githubusercontent.com/94011974/170503727-96f3cba0-d022-4ab9-8cf3-a52c94a3d935.jpeg)

![WhatsApp Image 2022-05-26 at 8 49 34 AM](https://user-images.githubusercontent.com/94011974/170503760-17543032-d15c-4857-a46a-0d33c1618c86.jpeg)

![WhatsApp Image 2022-05-26 at 8 49 58 AM](https://user-images.githubusercontent.com/94011974/170503858-4367fca0-1537-4539-8709-8693729a1ce2.jpeg)

***

**3. Requerimientos previos**

***

Análisis de mallas


![WhatsApp Image 2022-06-03 at 8 30 29 AM](https://user-images.githubusercontent.com/94011974/171864079-b005c0d4-4cd1-4d72-810e-c81d9d9dfd1d.jpeg)

Circuito armado

![WhatsApp Image 2022-05-26 at 9 08 11 AM](https://user-images.githubusercontent.com/94011974/170504633-5a0e060e-6e7c-4867-aa1d-aa5ac5eb236c.jpeg)

Circuito para el análisis de mallas

![image](https://user-images.githubusercontent.com/94011974/171923593-40278f6c-b813-4649-8ec7-63ff1fa5141c.png)

***

Medicion de corrientes en mallas 1,2 y 3

![image](https://user-images.githubusercontent.com/94011974/171923656-20a93ee4-35a8-43ed-b1c8-c969d551e6fa.png)


**4. Materiales y equipos requeridos**

![image](https://user-images.githubusercontent.com/94011974/142951161-85a7ecea-bf4d-45bb-81eb-164e07b5fcc8.png)

***

**5. Procedimiento**

**MALLA 1:** 

5V – V820 - V1000 = 0 

5 – 820.I1 - 1000.(I1 – I2) = 0  (1ra Ecuación)

**MALLA 2:**

- V1200 – V2200 – V1000 = 0

-1200.I2 - 2200.(I2-I3) - 1000.(I2-I1) = 0  (2da Ecuación)

**MALLA 3:**

-V390 -10 V - V2200 =0

-390I3 - 10 - 2200.(I3-I2) = 0  (3ra Ecuación)

Resolviendo los sistemas de ecuaciones con las ecuaciones (1) , (2) y (3).

Se obtuvieron los siguientes resultados:

![image](https://user-images.githubusercontent.com/94011974/171866873-641e62b8-8e0c-4255-8019-09d995faea97.png)
 
I1 =   1.1 mA

I2 =  -2.9 mA

I3 =  -6.3 mA

![image](https://user-images.githubusercontent.com/94011974/171923701-ee809471-288d-4a8c-abe1-37425117140f.png)

***

**6. Cálculo de error**

![image](https://user-images.githubusercontent.com/94011974/170057592-12d7c136-22cd-4cac-9532-0e92eb81f1b9.png)

***

**Malla  1**


![image](https://user-images.githubusercontent.com/105259459/171923106-79b3d6e1-e8f9-40c1-9188-521d956c643c.png)



**Malla 2**

![image](https://user-images.githubusercontent.com/105259459/171923172-4147a52c-f2d0-45d6-a504-f67cd14dac7b.png)



**Malla 3**

![image](https://user-images.githubusercontent.com/105259459/171923313-bebbb20a-d2d2-4d7a-9b9e-b2fbf8ca31b3.png)


***

**7. Vídeo**

https://www.youtube.com/watch?v=4IcsGD-T6jc

***

**8. Conclusiones**

-En base a las bibliografías investigadas, se concluye que, para el análisis de mallas, asigna y dibuja corrientes independientes en cada malla, es necesaria la segunda ley de Kirchhoff, la cual nos dice que la suma algebraica de los voltajes es una malla cerrada debe ser cero y se debe tener cuidado con la dirección de la corriente. Con respecto a la ley de la conservación de la carga los componentes ganan y pierden energía dependiendo del elemento.

-Usando el simulador de Tinkercad y armando un circuito electrónico físico, se midió las corrientes de cada malla. Mientras que para obtener el valor calculado se utilizan aplicaciones algebraicas, en este caso la técnica del análisis de mallas, que asigna corrientes independientes a cada malla al terminar su resolución.

-En el video realizado se explica la construcción del circuito físico y los componentes que se utilizaron, junto con la simulación de Tinkercad.  Se ubican las resistencias, los cables y las fuentes de voltaje que son los cargadores, para la fuente de voltaje de 10 V se unieron dos cargadores de 5 voltios. Se procede a medir las corrientes comprobando la ley de Kirchhoff y el análisis de mallas. 

***

**9. Bibliografía**

Floyd, T. (2007). Principios de circuitos eléctricos. PEARSON Educación. https://drive.google.com/file/d/15UCq2JrPEKKB8SwajlmtTcE07nMiowaK/view

10. Rubrica

![image](https://user-images.githubusercontent.com/94011974/169427061-265123c2-f557-4b9a-9ef6-5a545e89aff2.png)
