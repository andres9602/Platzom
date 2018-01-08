# Platzi

Platzom es un idioma inventado  para el [Curso de Fundamentos de JavaScript](https://platzi.com/js) de [Platzi](https://platzi.com), el mejor lugar de educación online

## Descripción del idioma:

- Si la palabra terminar en "ar", se le quitan esos dos caracteres
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o mas letras, se debe partir a la mitad y unir con un guion
- Si la palabra original es un palindromo, ninguna regla anterior cuenta, y se devuelve intercalando mayusculas y minusculas

## Instalación:

```
npm install platzom
```

## Uso:

```
import platzom from 'platzom'

platzom('Programar') // Program
platzom('Zorro') // Zorrope
platzom('Zarpar') // Zarppe
platzom('abecedario') // abece-dario
platzom('sometemos') // SoMeTeMoS
```

## Créditos:

- [Andrés Aguirre](https://github.com/andres9602)

## Licencia:

[MIT](https://opensource.org/licenses/MIT)