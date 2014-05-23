Las naciones a lo largo del mundo cuenta con un acerbo lingüístico, la cantidad de palabras que utiliza cada una varia de acuerdo al idioma que utilicen pero se sabe que esta cantidad es finita, las personas por una u otra razón cuentan con alguna cuenta dentro de algún sistema informático, las cuentas son registradas en las bases de datos y es muy común que para que una persona tenga acceso a estos sistemas se firmen como el ente dueño de dicha cuenta.

Cuando un usuario se registra en el sistema, este por norma debe mandar los datos referentes a la contraseña cifrados con el fin de que aún cuando un usuario pueda ver estos datos dentro de la base de datos del sistema no pueda entenderlos un ejemplo de esta transformación sería la siguiente: 

La contraseña es holaAtaqueDiccionario 
Y el dato almacenado en la base de datos se presentaría : VHzoezH2QxiVOr2mgAzTccCd7gRcmfJxiQu

El  problema a simple vista parecería solucionado pero..... no es así 
un programador realiza una función para que cuando un usuario registre su cuenta este dato se altere antes de enviarse y llegue con el formato distinto, cuando el usuario intenta acceder a su cuenta no escribe “VHzoezH2QxiVOr2mgAzTccCd7gRcmfJxiQu” él escribe  “holaAtaqueDiccionario” y el proceso es simple este dato escrito por el usuario para acceder al igual se modifica y se compara con la de la base de datos si son igual, el sistema da pie a que el usuario pueda acceder sin problema alguno.

El ataque diccionario prácticamente  hace una conversión igual al proceso explicado anteriormente, se descarga un diccionario con todas las palabras del idioma y se compara si el programa encuentra similitudes este indica en texto claro la contraseña del usuario, este método  o tipo de ataque golpea al 90% de las posibles contraseñas que puede tener un individuo.

El principal desperfecto de este tipo de ataque es que suele ser lento y no garantiza la obtención de la contraseña.

Twitter  @arithgrey
mail: arithgrey@gmail.com
