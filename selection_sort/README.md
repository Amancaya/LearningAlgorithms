# SELECTION SORT

#### Apuntes

   - Toma O(n^2) de tiempo en la ejecucion
   - Se ordena recorriendo uno por uno cada item
   
   Para poder comprender este algoritmo se deben entender los conceptos de Array y linked list
   
   ##### Arrays
   
   - Se conoce la posicion de cada item
   - Los items de un array se guardar de forma continua en memoria
   - Al tratar de insertar mas items que espacios libres en memoria, es necesario que todo el completo se mueva a un lugar 
   en memoria en el que pueda entrar.
   
   
   ##### Linked List
   
   - Los items en una linked list pueden estar en diferentes partes de la memoria
   - Para insertar un item es necesario recorrer uno por uno los items conociendo su posicion para insertar en la posicion correcta.
   - Para saber la posicion de un item se debe saber la posicion del item previo a este.
   
   *Tiempos de ejecucion de Arrays y Linked list en sus diferentes operaciones*
   
   
   Operaciones | Arrays | Lists 
   ------------|--------|-------
   Lectura | O (1) | O (n)
   Insercion | O (n) | O (1)
   ELiminacion | O (n) | O (1)
   