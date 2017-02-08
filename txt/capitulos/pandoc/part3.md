
> ### Utilización
> Creamos un fichero md con código markdown 
> ![](../../imagenes/pandoc/pandoc3_1.png)
> Abrimos la consola de comando de windows, nos posicionamos donde esta el archivo
.md que hemos creado que en nuestro caso es **nuevo.md** y ejecutamos el 
siguiente comando  ```$ pandoc nuevo.md -o nuevo.html```.

> ![](../../imagenes/pandoc/pandoc3_2.png)

> Como vemos en la siguiente imagen se ha creado un archivo html que tendrá el siguiente aspecto.
> ![](../../imagenes/pandoc/pandoc3_3.png)

> Como vemos en la anterior imangen los caracter como la ñ no se visualizan 
para que estos carateres se puedan ver bien tenemos que coloacar la opcion -s en pandoc quedando asi el comando
```$ pandoc nuevo.md -s -o nuevo.html```, el html creado se relaizara de la siguiente manera.
> ![](../../imagenes/pandoc/pandoc3_4.png)

> ## Mas comandos

> Para pasar de markdown a pdf, el comando es el siguiente ```$ pandoc nuevo.md -s -o nuevo.html``` dando como 
  resultado la siguiente imagen:

> Para pasar de markdown a pdf, el comando es el siguiente ```$ pandoc nuevo.md -s -o nuevo.html``` dando como 
  resultado la siguiente imagen:


