# CHALLENGE_01
Challenge 1 of CCOM4995

Para iniciar este proyecto, decidimos dividirlo en diferentes "fases" donde poco a poco fuimos formando la casa desde sus cimientos hasta llegar al techo, que en este caso seria la parte final. Para lograr este objetivo se usaron algunas de las herramientas disponibles en Unity como las herramientas de escala, rotación, reposición y el gizmos.

**Paso 1: Colocar pared trasera**

<p align="center">
  <img width="500" height="500" alt="Step 1" src="https://github.com/user-attachments/assets/56c7c29b-8f60-4fcd-a9b4-08b2bbfdf058" />
</p>

Para la pared trasera usamos un bloque que creamos en el origen, lo reposicionamos unas 3.5 unidades hacia atras y los achicamos en el eje de X a 1/2 unidad para que fuera más fino. Al mismo tiempo, lo estiramos hacia los lados en el eje de la Z a 7 unidades de manera simétrica, y lo levantamos unas 1.5 unidades en el eje de Y y lo estiramos a 3 unidades para darle a la pared trasera la altura necesaria que se ajuste a la casa.

**Paso 2: Colocar paredes laterales**

<p align="center">
  <img width="500" height="500" alt="Step 2" src="https://github.com/user-attachments/assets/49fdcfc1-400b-4482-9f70-36c32d5f7227" />
</p>
  
Para las paredes laterales, el proceso fue bastante similar a el de la pared trasera. Esta vez, en vez de crear un nuevo objeto de por si desde cero simplemente copiamos el objeto anterior que se uso para la pared trasera e invertimos los valores de escala y estiramiento para el eje de X y el eje de Z para que de esta manera estuviera perpendicular a la pared de atrás. Luego, se trasladó 3.5 unidades hacia la derecha. Ya puesta esta pared, nuevamente fue copiada y trasladada 7 unidades hacia la izquierda para que así, quedaran perpendiculares a la pared trasera, fueran paralelas a sí mismas y se fuera pareciendo más a una casa.

**Paso 3: Colocar pared frontal**

<p align="center">
  <img width="500" height="500" alt="Step 3" src="https://github.com/user-attachments/assets/9ab2c841-54aa-4b92-affa-13dfad1808be" />
</p>

Para la entrada principal usamos dos bloques hacia los lados con valores de X = 1/2, Y = 3 y Z = 3, ambos posicionados a X = 3.5, con la misma elevación en Y que el resto de la casa y uno posicionado a Z = 2 y el otro a Z = -2 para asegurarse que la casa tenga una entrada; y un bloque de X = 1/2, Y = 1 y Z = 1 posicionado en la misma X, Y = 2.5 y Z = 0 para que quede centrado en la casa para marcar la parte de arriba de la puerta. Debido a que cada cubo es un elemento individual tuvimos que reposicionarlos varias veces usando la herramienta de posición para asegurarse que la casa tenga una puerta. 

**Paso 4: Colocar techo**

<p align="center">
  <img width="500" height="500" alt="Step 4" src="https://github.com/user-attachments/assets/145a1df2-b168-4672-9431-b01de2d508fa" />
</p>

Por último, luego de tener las bases principales de la casa usando formas primitivas, nos enfocamos en hacer el techo. Para lograr esto, usamos un cubo, y lo estiramos en el eje de la X a 7 unidades, para luego achicarlo en el eje de la Y a 1/2 unidad. Lo elevamos una unidad arriba de el tamaño de las paredes y fue rotado unos 35 grados aproximadamente para que dé ese efecto de tejado. Luego, este mismo objeto fue copiado y fue rotado a -35 grados para que estos cubos fueran opuestos y quedaran en forma de triangulo.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Jeniel - Durante el transcurso de este proyecto más que nada aprendí a usar las herramientas básicas de Unity, como rotar, reposicionar, y aumentar de tamaño las figuras más primitivas que nos permitieron hacer la casa. Lo más que me intereso honestamente fue hacer la parte del "door frame" debido a que tuve que pensar por un momento como hacerlo correctamente debido a que no era simplemente colocar las primitivas como en los otros pasos, si no que requería una secuencias de pensamientos real para poder llegar al resultado que el objetivo pedía. A pesar de que ya tenía algo de conocimiento en Unity y sus herramientas fue bueno poder verlas nuevamente y recordar como manejar las diferentes interfaces que hacen de el trabajo uno mucho más facil.

Luis - Realizando este proyecto, me di cuenta de lo mucho que se puede aprender navegando el Unity engine, aunque sea para algo tan simple como diseñar una casa básica. Me ayudó a entender mejor cómo funciona Unity y cómo pequeñas modificaciones en cosas como tamaño, posición, escala, etc. pueden cambiar por completo el resultado. Además, aprendí la importancia de organizarse en diferentes fases, porque al dividir el trabajo en partes se hace más fácil recordar que falta y que se puede mejorar, y en general es mucho más organizado el proceso. Por último, aprendí lo útil y eficiente que es copiar y ajustar objetos en lugar de empezar de cero cada vez, lo cual ahorra mucho tiempo valioso. En general, pienso que fue un primer proyecto perfecto para ir familiarizándonos con Unity, aunque otro proyecto similar pudiera haber tenido el mismo resultado.

Gustavo - Al finalizar este proyecto, logré entender cuan tedioso es crear objetos en Unity con sólo las herramientas básicas de este programa, ya que muchas veces estos objetos dependen de una selección bastante limitada de figuras. Como estas figuras básicas son tan simples, tuvimos que usar más de un cubo para que la casa tenga una puerta, el cual no es muy eficiente. Luego, al hacer el techo, la simetría fue un aspecto muy importante que se tuvo que crear manualmente ya que, si se posicionaba con las herramientas de movimiento de arrastrar y soltar, podía quedar desbalanceado. Pero, pude mejorar mi entendimiento del Unity engine al tener que utilizar las herramientas de desplazar y escalar varias veces para obtener los resultados deseados. 
