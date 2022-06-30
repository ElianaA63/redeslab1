**Laboratorio 1**

_UTF-8 para **encoding** de caracteres especiales_ 
“UTF-8” es la abreviatura de “8-bit UnicodeTransformation Format” y designa a la codificación de caracteres más extendida. UTF-8 es una codificación de caracteres que le asigna una cadena de bits determinada, a cada carácter Unicode y que puede leerse como un número binario. Esto significa que UTF-8 asigna un número binario fijo a todas las consonantes, cifras y símbolos. Debido a esto podemos escribir nombres de dominios como: - [http://中文.tw/](http://中文.tw/) - [https://💩.la](https://💩.la)

El español es un lenguaje que posee caracteres especiales tales como tildes, ñ, diéresis (ü)…
Esto en HTML es un problema, pues no todo hay forma de mostrarlo más que con entidades HTML.

Una forma de estandarizar la visualización de este tipo de caracteres sin tener que escribir constantemente las entidades HTML que las definen es utilizar una codificación de caracteres.
Se entiende por codificación de una página Web a la tabla de caracteres que es utilizada en ella. Una tabla de caracteres es una lista de caracteres válidos; por ejemplo, una página en español necesita disponer de todas las letras del abecedario (incluida la ñ) así como tildes, interrogaciones, exclamaciones y demás caracteres característicos del idioma.
Al declarar una codificación en nuestra página web estamos, por decirlo de alguna manera, diciéndole al navegador cómo debe interpretar esos caracteres especiales que componen el texto; por lo que internamente el navegador hará las sustituciones de los caracteres especiales por las entidades HTML correspondientes de forma automática.
De forma resumida, nos permite escribir con total normalidad en nuestro documento HTML sin preocuparnos de las tildes, interrogaciones y demás caracteres especiales del lenguaje.