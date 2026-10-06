<!-- ELUCENIA technical documentation · escala-de-ashworth-modificada · fr · no clinical/professional/rights approval -->

# Échelle d’Ashworth modifiée

[conditions, sources et autorisations](https://elucenia.org/fr/outils/escala-de-ashworth-modificada)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Résistance au mouvement passif (sur environ 1 seconde)

`grau`

- `0` — 0 – Aucune augmentation du tonus musculaire
- `1` — 1 – Légère augmentation : accrochage puis relâchement, ou résistance minimale en fin d’amplitude
- `2` — 2 – Augmentation plus marquée sur la majeure partie de l’amplitude, mais le segment se mobilise facilement
- `3` — 3 – Augmentation considérable : mobilisation passive difficile
- `4` — 4 – Segment rigide en flexion ou en extension
- `1p` — 1+ – Légère augmentation : accrochage suivi d’une résistance minimale sur moins de la moitié de l’amplitude

## Édition de la méthode

Ashworth modifiée/Bohannon–Smith 1987 : 0/1/1+/2/3/4 ; degré 1+ spécifique

## Formule documentée

Patient détendu en décubitus dorsal : mobiliser passivement le segment sur toute son amplitude en environ 1 seconde et choisir le degré de résistance. Bohannon et Smith ont ajouté 1+ à l’échelle originale.

## Limites et population

Cotation clinique de la résistance au mouvement passif, distincte de la force musculaire. L’étude originale de fiabilité a examiné les fléchisseurs du coude chez des patients présentant une lésion intracrânienne. Cette performance ne peut pas être automatiquement extrapolée à chaque articulation ou affection neurologique.

## Références

- [Bohannon RW, Smith MB. Interrater reliability of a modified Ashworth scale of muscle spasticity. Phys Ther, 1987.](https://doi.org/10.1093/ptj/67.2.206)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Pas d’augmentation du tonus


### 2

Légère augmentation du tonus sur moins de la moitié de l’amplitude du mouvement


### 3

Augmentation importante du tonus : mouvement passif difficile

