# Descripción

Se creará una manera divertida y más completa de elegir el maridaje de una cerveza. Para ello: 
- se convertirá la columna maridaje en varias columnas por categorías de comida (Pescado, Carne, Ceviche, ...) y se asigna un 1 cuando el maridaje indica match entre la cerveza y esa categoría
- se entrenará un clasificador multietiqueta que predice el porcentaje de match entre una categoría de comida y una cerveza en función de las características de la cerveza (se testeará también con predictores extraídos de la descripción con NLP)
- se realizará una interfaz de usuario en la que el usuario elije una de las cervezas propuestas o disena su propia cerveza editando las características (ver imagen de prototipo de interfaz). Una vez elegida o disenada la cerveza, se muestra el porcentaje de match con varias categorías de comida.
