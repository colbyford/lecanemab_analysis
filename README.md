# Lecanemab Analysis

<h3 align="right">Colby T. Ford, Ph.D.</h3>

Protein interaction analysis of Lecanemab, an amyloid beta-targeting antibody used to treat Alzheimer’s Disease.

Companion repo for: https://medium.com/@colbyford/predicting-the-molecular-interactions-of-lecanemab-the-new-fda-approved-monoclonal-antibody-for-94441d6a8a24

![](docking/haddock_2.4/cluster1_1_version1.png)

## Structures
- Amyloid Beta: [structures/amyloid_beta/8azs.pdb](structures/amyloid_beta/8azs.pdb)
- Lecanemab Fab: [structures/lecanemab/lecanemab_fab.pdb](structures/lecanemab/lecanemab_fab.pdb)

## Docking Assessment
- HADDOCK Results [docking/haddock_2.4](docking/haddock_2.4)

|          **Metric**         | **Score (+/-)** |
|:---------------------------:|:---------------:|
| HADDOCK score               | -110.7 +/- 2.9  |
| Van der Waals energy        | -93.7 +/- 0.4   |
| Electrostatic energy        | -101.2 +/- 11.7 |
| Desolvation energy          | -22.3 +/- 2.1   |
| Restraints violation energy | 256.1 +/- 29.0  |
| Buried Surface Area         | 2332.0 +/- 37.7 |

## References
- KEGG Entry: https://www.kegg.jp/entry/D11678
- DrugBank Entry: https://go.drugbank.com/drugs/DB14580
- Stern et al., 2023: https://doi.org/10.1016/j.neuron.2023.04.007
