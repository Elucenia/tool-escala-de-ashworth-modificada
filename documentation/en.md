<!-- ELUCENIA technical documentation · escala-de-ashworth-modificada · en · no clinical/professional/rights approval -->

# Modified Ashworth Scale

[conditions, sources and permissions](https://elucenia.org/en/tools/escala-de-ashworth-modificada)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Resistance to passive movement (over approximately 1 second)

`grau`

- `0` — 0 – No increase in muscle tone
- `1` — 1 – Slight increase: catch and release or minimal resistance at the end of the range of motion
- `2` — 2 – More marked increase through most of the range, but the limb moves easily
- `3` — 3 – Considerable increase: passive movement difficult
- `4` — 4 – Limb rigid in flexion or extension
- `1p` — 1+ – Slight increase: catch followed by minimal resistance through less than half the range

## Method edition

Modified Ashworth/Bohannon–Smith 1987: 0/1/1+/2/3/4; specific grade 1+

## Documented formula

With the patient relaxed and supine, passively move the segment through its full range in about 1 second and select the resistance grade. Bohannon and Smith added grade 1+ to the original Ashworth scale.

## Limits and population

Clinical grading of resistance to passive movement, distinct from muscle strength. The original reliability study examined elbow flexors in patients with intracranial lesions. That performance cannot automatically be transferred to every joint or neurological condition.

## References

- [Bohannon RW, Smith MB. Interrater reliability of a modified Ashworth scale of muscle spasticity. Phys Ther, 1987.](https://doi.org/10.1093/ptj/67.2.206)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
