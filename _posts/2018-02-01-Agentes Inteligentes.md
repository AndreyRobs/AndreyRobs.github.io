---

layout: post

title: Agentes Inteligentes

---


Un agente es cualquier cosa capaz de percibir su medioambiente con la ayuda de sensores y actuar en ese medio utilizando actuadores.

El t�rmino percepci�n se utiliza para indicar que el agente puede recibir entradas en cualquier instante. La secuencia de percepciones de un agente refleja el historial completo de lo que el agente ha recibido.

En general, un agente tomar� una decisi�n en un momento dado dependiendo de la secuencia completa de percepciones hasta ese instante.

En t�rminos matem�ticos se puede decir que el comportamiento del agente viene dado por la funci�n del agente que proyecta una percepci�n dada en una acci�n.

Hacer lo correcto es mejor que hacer algo incorrecto, pero �qu� significa hacer lo correcto? Como primera aproximaci�n, se puede decir que lo correcto es aquello que permite al agente obtener un resultado mejor. Por lo tanto se necesita determinar una forma de medir el exito.

Las medidas de rendimiento incluyen los criterios que determinan el �xito en el comportamiento del agente. Cuando se sit�a un agente en un medio, �ste genera una secuencia de acciones de acuerdo con las percepciones que recibe. Esta secuencia de acciones hace que su h�bitat pase por una secuencia de estados. Si la secuencia es la deseada, entonces el agente habr� actuado correctamente.

Racionalidad

La racionalidad en un momento determinado depende de cuatro factores:

La medida de rendimiento que define el criterio de �xito.
El conocimiento del medio en el que habita acumulado por el agente.
Las acciones que el agente puede llevar a cabo.
La secuencia de percepciones del agente hasta este momento.

Esto nos lleva a la definici�n de agente racional:

En cada posible secuencia de percepciones, un agente racional deber� emprender aquella acci�n que supuestamente maximice su medida de rendimiento, bas�ndose en las evidencias aportadas por la secuencia de percepciones y en el conocimiento que el agente mantiene almacenado.

42