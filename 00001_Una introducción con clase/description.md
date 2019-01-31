En Java _casi_ todo lo que escribimos se enmarca dentro de una clase, así que empecemos por lo fácil: ¡definamos nuestra primera clase!

```java
class Golondrina {
  int energia;
  String nombre;
  
  void volarEnCirculos() {
    energia -= 100;
  }
  
  boolean puedeVolar() {
    return energia > 0;
  }
}
```

¿Te acordás de la golondrina Pepita? Volvió, ¡en forma de clase Java! Comparémosla con su implementación en Wollok: 

```wollok
class Golondrina {
  var energia
  var nombre
  
  method volarEnCirculos() {
    energia -= 100
  }
  
  method puedeVolar() {
    return energia > 0
  }
}
```

> ¿Qué diferencias saltan a primera vista? 
> En Java tenemos que...

