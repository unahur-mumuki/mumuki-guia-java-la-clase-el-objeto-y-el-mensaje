Muy lindo declarar clases, pero ¿cómo las usamos? ¿Y los objetos? ¿Y los mensajes? ¿Y Candela? :fearful:

¡Vamos por partes! 

```java
// En Java podemos instanciar nuestras clases 
// mediante el operador `new`: 
Golondrina pepita = new Golondrina();

// y podemos enviar mensajes a nuestros objetos 
// mediante el operador `.`:
pepita.volarEnCirculos();

// Como caso particular, los strings también son objetos (de la clase `String`),
// pero los creamos de forma literal, no escribiendo `new` : 
String frase = "Todavía sirve, todavía sirve";
frase.contains("sirve");
```

> Veamos si se entiende: dentro del método `main` que te dejamos, instanciá a una golondrina `anastasia`, dale de comer 50 gramos de alpiste y hacela volar en círculos. 
> 