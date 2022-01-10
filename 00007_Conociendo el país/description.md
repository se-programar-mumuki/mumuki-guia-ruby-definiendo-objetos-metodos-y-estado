Hasta ahora los métodos que vimos solo producían un efecto. Si bien solo pueden devolver una cosa, ¡pueden producir varios efectos!

Solo tenés que poner uno debajo del otro de la siguiente forma:

``` ruby
def self.comprar_libro!
	@plata -= 300
	@libros += 1
end
```

Como te dijimos, `Pepita` podía volar a diferentes ciudades. Y cuando lo hace, cambia su ciudad actual, además de perder `100` unidades de energía. Las distintas ciudades vas a poder verlas en la **Biblioteca**.

Con esto en mente: 

> * Creá un atributo `ciudad` en `Pepita`: la ciudad donde actualmente está nuestra golondrina.
> * Hacé que la `ciudad` inicial de pepita sea `Iruya`.
> * Definí un método `volar_hacia!` en `Pepita`, que tome como argumento otra ciudad y haga lo necesario.