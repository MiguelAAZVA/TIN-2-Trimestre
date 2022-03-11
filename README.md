# TIN-2-Trimestre
El enunciado pide  que encontremos si dos números enteros declarados por teclado están en un vector dimensión 15 determinado por el usuario.
Perimero declaramos todas las variables, en dato entero aunque declararemos dos en bool (nos permite establer un valor como verdadero (true) o falso (false)
Como tenemos que permitir que el usuario declarar el vector , creamos un for o bucle el cual inialice el vector en la posición 0 y lea el dato que pongamos por teclado
Esto proceso se repetirá hasta que el vector quede completo y en este caso , el contador del bucle no sea mayor a 15.
Para comprobar si existe o no en el vector el primer y el segundo número que introducimos para que se busque
recorremos el vector con un bucle for en el cual anidamos dos if , cada uno por cada dato que deseamos buscar 
y le indicamos como condición a estos if que sean verdaderos cuando el varlor del dato buscado se encuentre en cualquiera de las 
posiciones del vector y cambie el valor de la variable bool a y/o b a true 
Al salirnos del bucle para comprobar si no han aparecido usamos las variables bool en un if por cada dato buscado , los cuales tendrán como condición que a y/o b se mantengan como falsos  y si no se mantienen como falsos no mostrarán nada.

Bibliografía:
https://www.aprenderaprogramar.com/index.php?option=com_content&view=article&id=899:tipos-de-datos-en-c-declarar-variables-enteras-int-long-o-decimal-float-double-char-inicializacion-cu00510f&catid=82&Itemid=210 
https://www.it.uc3m.es/pbasanta/asng/course_notes/input_output_function_scanf_es.html
https://docs.microsoft.com/es-es/cpp/c-language/for-statement-c?view=msvc-170  

videos vectores→
https://youtu.be/tVYngeh7zUc (de forma acumulativa)
https://www2.eii.uva.es/fund_inf/cpp/temas/9_vectores/vectores_c.html 
https://docs.microsoft.com/es-es/cpp/standard-library/vector?view=msvc-170 
http://cuartas.es/c/arrays/
const
https://www.tutorialesprogramacionya.com/cya/detalleconcepto.php?punto=61&codigo=61&inicio=60 
stdbool.h
https://pubs.opengroup.org/onlinepubs/009695399/basedefs/stdbool.h.html 
bool
https://docs.microsoft.com/es-es/dotnet/csharp/language-reference/builtin-types/bool 
