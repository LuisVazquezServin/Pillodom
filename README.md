#PILLODOM

Pillodom es una practica para el curso de [Fundamentos de JS de Platzi](https://platzi.com/js)

## Descripcion del idioma
- Si la palabra termina en "ar", se le quitan esos dos caracteres
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir a la mitad y unir con un guión del medio
- Si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra intercalando mayúsculas y minúsculas

## Instalación 

``` 
npm install pillodom
```

## Uso
```
import pillodom from "pillodom"
platzom("Programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS

```


## Licencia
[MIT](https://opensource.org/licenses/MIT)