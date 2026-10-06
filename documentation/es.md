<!-- ELUCENIA technical documentation · escala-de-ashworth-modificada · es · no clinical/professional/rights approval -->

# Escala de Ashworth modificada

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/escala-de-ashworth-modificada)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Resistencia al movimiento pasivo (en aproximadamente 1 segundo)

`grau`

- `0` — 0 – Sin aumento del tono muscular
- `1` — 1 – Aumento leve: enganche y liberación o resistencia mínima al final del recorrido
- `2` — 2 – Aumento más marcado en la mayor parte del recorrido, pero la extremidad se mueve con facilidad
- `3` — 3 – Aumento considerable: movimiento pasivo difícil
- `4` — 4 – Extremidad rígida en flexión o extensión
- `1p` — 1+ – Aumento leve: enganche seguido de resistencia mínima en menos de la mitad del recorrido

## Edición del método

Ashworth modificada/Bohannon–Smith 1987: 0/1/1+/2/3/4; grado 1+ específico

## Fórmula documentada

Con el paciente relajado en decúbito supino, mueva pasivamente el segmento en todo su recorrido en aproximadamente 1 segundo y elija el grado de resistencia. Bohannon y Smith añadieron 1+ a la escala original.

## Límites y población

Graduación clínica de la resistencia al movimiento pasivo, distinta de la fuerza muscular. El estudio original de fiabilidad examinó los flexores del codo en pacientes con lesión intracraneal. Ese rendimiento no puede trasladarse automáticamente a todas las articulaciones o condiciones neurológicas.

## Referencias

- [Bohannon RW, Smith MB. Interrater reliability of a modified Ashworth scale of muscle spasticity. Phys Ther, 1987.](https://doi.org/10.1093/ptj/67.2.206)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Sin aumento del tono


### 2

Aumento leve del tono en menos de la mitad del arco de movimiento


### 3

Aumento considerable del tono: movimiento pasivo difícil

