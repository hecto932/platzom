# Platzom

Platzom es un idioma inventado para el [curso de fundamentos de javascript](htttps://platzi.com/js) de [Platzi](https://platzi.com).

## Descripción del idioma

- Si la palabra termina con "ar", se le quitan esas dos letras.
- Si la palabra inicia con Z, se le añade "pe" al final.
- Si la palabra traducida tiene 10 o mas letras, se le debe partir en dos por la mitad y unir con un guion medio.
- Por último, si la palabra original es un palíndromo, ninguna regla anterior cuenta y se le devuelve la misma palabra pero intercalando letras mayusculas y minusculas

## Instalación

```
npm install platzom
```

## Uso
```
import platzom from 'platzom'

platzom('programar') // Program
platzom('Zorro') // Zorrope
platzom('Zarpar') // Zarppe
platzom('abecedario') // abece-dario
platzom('sometemos') // SoMeTeMoS
```

## Créditos

- [Hector Flores](https://twitter.com/@hecto932)

## Licencia

[MIT](https://opensource.org/licenses/MIT)