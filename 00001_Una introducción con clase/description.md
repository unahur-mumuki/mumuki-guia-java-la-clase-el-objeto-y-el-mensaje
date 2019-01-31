En Java _casi_ todo lo que escribimos se enmarca dentro de una clase, así que empecemos por lo fácil: ¡definamos nuestra primera clase!

```java
class Golondrina {
  int energia;
  void volarEnCirculos() {
    energia -= 100;
  }
}
```

¿Te acordás de la golondrina Pepita? Volvió, ¡en forma de clase Java! Comparémosla con su implementación en Ruby: 

```ruby
class Golondrina
  def volar_en_circulos!
    energia -= 100
  end
end
```

> ¿Qué diferencias saltan a primera vista? 
> En Java tenemos que...

