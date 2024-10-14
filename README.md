fun numerosDesc(n= int) {
   if (n<=0)
   {
     return
   }
   print(n)
   numerosDesc(n-1)
}
fun main()
{
  val num=5
  mumerosDesc(num)
}


# Caso Base:

El caso base en recursividad es el caso más simple de un problema que se puede resolver directamente, sin necesidad de llamar a la función recursiva nuevamente. Es el punto de parada de la recursividad, donde la función deja de llamarse a sí misma.

El caso base es importante porque:

◈ Evita la recursividad infinita: sin un caso base, la función recursiva seguiría llamándose a sí misma indefinidamente, lo que provocaría un error de stack overflow.

◈ Proporciona una solución trivial: el caso base proporciona una solución directa para el problema más simple, lo que permite que la función recursiva se construya sobre esta solución.

◈ Permite la descomposición del problema: el caso base ayuda a descomponer el problema en subproblemas más pequeños, que se pueden resolver de manera recursiva.
