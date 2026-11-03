# Elevational diversity of Neotropical moths along an Amazon–Andes gradient

Data for: **Contrasting elevational diversity patterns across three Neotropical moth lineages along an Amazon–Andes gradient** (*Journal of Animal Ecology*, submitted).

![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-lightgrey.svg)


## Files

All files are comma-separated (UTF-8) and are linked by the column `Plot`.

| File | Content |
|---|---|
| `plots_environment.csv` | 26 plots: location, elevation and environmental variables |
| `abundance_Arctiinae.csv` | 52 samples (26 plots × 2 campaigns) × 497 morphospecies |
| `abundance_Saturniidae.csv` | 52 samples × 61 morphospecies |
| `abundance_Sphingidae.csv` | 52 samples × 31 morphospecies |
| `species_list.csv` | 589 morphospecies with lineage, clade and totals |

## Variables

### `plots_environment.csv`

| Column | Description |
|---|---|
| `Plot` | Plot code |
| `Locality` | Biological station or locality |
| `Latitude`, `Longitude` | Decimal degrees (WGS84) |
| `Elevation_m` | Elevation (m a.s.l.) |
| `ABERG` | Plot in the ABERG long-term monitoring network (yes/no) |
| `MAT_C` | Mean annual temperature (°C), TOMST loggers, Sep 2022–Dec 2023 |
| `MAP_mm` | Mean annual precipitation (mm), WorldClim 2.1 |
| `NPPleaf` | Leaf net primary productivity (Mg C ha⁻¹ yr⁻¹) |
| `NPPleaf_source` | `measured` (ABERG litterfall, n = 9) or `estimated` (GAM on elevation) |

### `abundance_<Lineage>.csv`

| Column | Description |
|---|---|
| `Sample` | Plot and campaign (e.g. `023-1`) |
| `Plot` | Plot code |
| `Campaign` | 1 or 2 |
| one column per morphospecies | Number of individuals (0 = not recorded) |

### `species_list.csv`

| Column | Description |
|---|---|
| `Lineage` | Arctiinae, Saturniidae or Sphingidae |
| `Clade` | Tribe, subtribe or informal clade (Arctiinae only) |
| `Taxon` | Morphospecies name and internal code |
| `Species_code` | Internal morphospecies code |
| `N_individuals` | Total individuals (both campaigns) |
| `N_plots` | Number of plots with records |

Morphospecies names are working hypotheses (*nr* = near, *sp* = undetermined species).

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please cite the dataset (Zenodo DOI) and the associated article.
