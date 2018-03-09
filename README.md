# Platzom

Platzom es un idioma inventado para el [Curso de fundamentos de JavaScript de Platzi](https://platzi.com/js)

## Descripción del idioma

-si la palabra termina en "ar", se le quitan esas dos letras
-Si la palabra inicia con Z, se le añade "pe" al final
-Si la palabra tiene 10 o más letras se debe partir a la mitad y unir con un guión
-Si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma plabra intercalando mayúsculas y minúsculas

## Instalación
```
npm isntall platzom
```

## Uso

```
import platzom from "platzom"

platzom ("Programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS

```

## Créditos

- [Dante Fernández]

## License

[MIT](https://opensource.org/licenses/MIT)
