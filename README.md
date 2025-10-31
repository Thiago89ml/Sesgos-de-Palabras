# Sesgos-de-Palabras

CORPUS UTILIZADO

El corpus utilizado fue uno que trata sobre noticias españolas. Para ello, se asoció la variable dfnews a la columna news del archivo CSV, la cual contiene dichas noticias.

Las palabras utilizadas para la lista fueron:
prometedor, esfuerzo, costoso, calidad, extranjero, habitante, cantidad, viable y deficiente.

Estas palabras fueron seleccionadas porque, dentro del corpus, se asocian con ideas de negociación, oportunidades y riesgos, todas ellas enfocadas en ámbitos de inversión o de mercado.

La segunda razón para elegirlas fue evaluar si la IA es capaz de asociar o diferenciar dicha lista de palabras con situaciones de rentabilidad o riesgo, considerando además que muchas de ellas pueden funcionar como adjetivos entre sí.

El estereotipo tomado fue rentable y riesgoso, en función del enfoque previamente planteado hacia la inversión y el mercado.

MAPA OBTENIDO

<img width="733" height="548" alt="image" src="https://github.com/user-attachments/assets/5ebf6b6b-9b63-4f30-bc71-3f3385ff77ee" />

El mapa obtenido muestra una concentración de palabras hacia el polo “riesgoso”, como deficiente o costoso. Sin embargo, también aparece la palabra habitante asociada a ese grupo, lo cual puede considerarse un sesgo, ya que el modelo vincula al “habitante” con conceptos negativos como “deficiente” o “costoso”. A su vez, las palabras viable y prometedor se encuentran atraídas hacia esta misma agrupación, lo que genera cierta confusión en la interpretación.

En el otro extremo del mapa se observa que extranjero y esfuerzo aparecen asociadas, lo cual resulta un punto de vista interesante. En cambio, calidad y cantidad se muestran desplazadas de los subconjuntos mencionados anteriormente. Esta situación resulta llamativa, pues calidad no se agrupa con palabras con las que habitualmente se relaciona, como prometedor o costoso.

De esta forma, se concluye que la IA presenta limitaciones en la asociación semántica, ya que puede vincular palabras contradictorias, lo que impide que otras se agrupen correctamente con sus sinónimos o contextos esperados (como ocurre con calidad y prometedor).

El problema de los sesgos es un aspecto que debe corregirse en la medida de lo posible, ya que este tipo de errores interpretativos puede llevar a un objetivismo generalizado en el que muchas IAs se sustentan. Esto podría provocar que no se consideren los matices propios del mundo subjetivo que caracteriza la forma de pensar de las personas en la actualidad.
