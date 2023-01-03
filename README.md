# PR-CTICA-No.-4-TEOREMA-DE-SUPERPOSICI-N

Integrantes:

- Jose Joaquin Silva Escobar
- Pamela Elizabeth Montatixe Almachi
- Mauricio Joseph Taco Cabrera


1. OBJETIVOs

- Implementar el teorema de Superposición en un ejercicio práctico.
- Entender el teorema de superposición de manera experimental a través del simulador Tinkercad

2. MARCO TEÓRICO

TEOREMA DE SUPERPOSICIÓN
El teorema de superposición establece que en un circuito lineal con varias fuentes, la corriente y el voltaje para cualquier elemento en el circuito es la suma de las corrientes y voltajes producidos por cada fuente que actúa de manera independiente.

Para calcular la contribución de cada fuente de forma independiente, todas las demás fuentes deben eliminarse y reemplazarse sin afectar el resultado final. Al eliminar una fuente de voltaje, su voltaje debe establecerse en cero, lo que equivale a reemplazar la fuente de voltaje con un cortocircuito. Al eliminar una fuente de corriente, su corriente debe establecerse en cero, lo que equivale a reemplazar la fuente de corriente con un circuito abierto.
Cuando suma las contribuciones de las fuentes, debe tener cuidado de tener en cuenta sus signos. Es mejor asignar una dirección de referencia a cada cantidad desconocida, si aún no se ha dado.

El voltaje o corriente total se calcula como la suma algebraica de las contribuciones de las fuentes. Si una contribución de una fuente tiene la misma dirección que la dirección de referencia, tiene un signo positivo en la suma; si tiene la dirección opuesta, entonces un signo negativo.
Tenga en cuenta que si las fuentes de voltaje o corriente tienen resistencia interna, debe permanecer en el circuito y aún debe considerarse. En TINA, puede asignar una resistencia interna al voltaje de CC y las fuentes de corriente, mientras usa el mismo símbolo esquemático. Por lo tanto, si desea ilustrar el teorema de superposición y al mismo tiempo utilizar fuentes con resistencia interna, solo debe establecer el voltaje (o corriente) de la fuente en cero, lo que deja intacta la resistencia interna de la fuente. Alternativamente, puede reemplazar la fuente con una resistencia igual a su resistencia interna.
Para usar el teorema de superposición con corrientes y voltajes de circuito, todos los componentes deben ser lineales; es decir, para todos los componentes resistivos, la corriente debe ser proporcional al voltaje aplicado (satisfaciendo la ley de Ohm).
Tenga en cuenta que el teorema de superposición no es aplicable a la potencia, ya que la potencia no es una cantidad lineal. La potencia total entregada a un componente resistivo debe determinarse utilizando la corriente total o el voltaje total a través del componente y no puede determinarse mediante una simple suma de las potencias producidas por las fuentes de forma independiente.

Corto circuito

Se denomina cortocircuito al fallo en un aparato o línea eléctrica por el cual la corriente eléctrica pasa directamente del conductor activo a la fase neutro o tierra, entre dos fases en el caso de sistemas polifásicos en corriente alterna o entre polos opuestos en el caso de corriente continua.

El cortocircuito de produce normalmente por fallos en el aislante de los conductores, cuando estos quedan sumergidos en in medio conductor como el agua por contacto accidental entre conductores aéreos por fuertes vientos o rotura de los apoyos

3. EXPLICACIÓN DEL PROCEDIMIENTO

3.1 MATERIAL Y EQUIPO REQUERIDO

![image](https://user-images.githubusercontent.com/117045943/210023255-f99a5033-0149-48b9-b317-6a366005b8ca.png)

3.2 Arme el circuito que se muestra en la figura 4.1.

![image](https://user-images.githubusercontent.com/117045943/210023285-3d749178-8b9c-41a5-94e9-4dc9d4355087.png)

3.3 Con las dos fuentes conectadas, mida el voltaje VA y la corriente IX, respetando
tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote
el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/117045943/210029046-abb2a217-7e3c-4281-8e75-dd4e76b192b0.png)

3.4 Haga “cero” la fuente de voltaje de 3 V (V2) y mida el voltaje VA y la corriente IX,
respetando tanto la polaridad del voltaje como el sentido de la corriente que se
proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/117045943/210029676-e8c9bc94-f8e0-4e83-9dcb-dcbd78bf9719.png)

3.5 Haga “cero” la fuente de voltaje de 10 V (V1) y mida el voltaje VA y la corriente
IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se
proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/117045943/210029732-45327802-3187-4fa5-8dda-d7fb76757ad3.png)


4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

4.1. Medición de voltaje aplicando superposición

![image](https://user-images.githubusercontent.com/117045943/210030192-e8bd09f0-04ca-426e-9140-5ca8847b3e62.png)

4.2. Medición de corriente aplicando superposición

![image](https://user-images.githubusercontent.com/117045943/210030204-f1d2c685-ae27-4727-83e9-8bb0de25f4a4.png)

4.3 Calcular errores de las mediciones 

![image](https://user-images.githubusercontent.com/117045943/210031311-3e9fb9ed-057d-4a12-9683-e48ba2a679a0.png)

5. VIDEO

5.1 Calculos

https://drive.google.com/file/d/1xprbNgkmxy9d7ilNZ2S2OvpFzzpXu-Dq/view?usp=sharing

5.2 Circuito armado en thinkercard

https://drive.google.com/file/d/10VzfwMNfGud2X6F1dh8xxfxFGUCOALH6/view?usp=sharing

6. CONCLUSIONES

•	El método o teorema de superposición es de gran utilidad para analizar circuitos que tengan dos o más fuentes de suministro ya que al analizarlo fuente por fuente el análisis resultará mucho más sencillo de realizar.

•	Se comprobó que los resultados obtenidos mediante el método de superposición son similares a los datos obtenidos en la simulación del circuito considerando también la pérdida de decimales lo cual causará que los resultados calculados varían de forma mínima con los obtenidos en simulación.

•	Los circuitos lineales cumplen la propiedad de superposición. Esto es, en un circuito con varias fuentes (de tensión / corriente), la respuesta se puede hallar sumando la respuesta del circuito a cada una de las fuentes (independientes) por separado

•	En la aplicación el teorema de superposición permite un cálculo veloz, eficaz y fácil para el análisis de circuitos electrónicos de una rama, componente o línea de componentes

7. BIBLIOGRAFÍA

Floyd, T. L., Salas, R. N., González, L. M. O., & López, G. P. (2007). Principios de circuitos eléctricos. Pearson Educación.

Vass, H. (2007). Circuitos eléctricos III.
