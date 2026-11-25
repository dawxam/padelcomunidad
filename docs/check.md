## A1

1. No he encontrado cómo pasarlo a px. Los valores de clamp indican el mínimo de tamaño aceptado, el valor que queremos ponerle, y el máximo permitido del rango.
    --paso-0: clamp(1rem, 0.9583rem + 0.185vw, 1.125rem);

2. Indica que el texto debe tener el color que se ha agisnado a la variable --color-acento
    color: var(--color-acento);


## A2

Supongo que algún framework o librerías como bootstrap o uiverse. La principal ventaja y desventaja que he encontrado es la funcionalidad que trae ya implementada, ya que puede facilitar mucho el diseño de la página, pero en caso de que quieras cambiar algo que ya venía de serie en dichas tecnologías puede complicarse.

## A3

1. Pasa por las carpetas tokens, base, components, layout y utilities.
    --color-acento: light-dark(#001bcc, #99a8ff);
    @layer reset, tokens, base, layout, components, utilities;

2. Porque @import va a desaparecer de SaSS.

3. Verdadero.

## A4

4. No, ya que creo que tiene más sentido que las incidencias estén junto al resto de enlaces del footer.
