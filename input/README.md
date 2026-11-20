# input

Raw plate reader exports (OD over time, one column per well) and plate layouts.

| File | What it is |
|---|---|
| `20251125_ScCgPireentry.csv` | Growth curves, S. cerevisiae and C. glabrata reentry |
| `20251126_Kl_Ca_reetnry.csv` | Growth curves, K. lactis and C. albicans reentry |
| `20251125_plate_layout_Kl_Ca.csv` | Plate layout for the K. lactis / C. albicans plate |
| `20251126_plate_layout_Sc_Cg.csv` | Plate layout for the S. cerevisiae / C. glabrata plate |
| `20260109_PPX1_PPN1_reentry.csv` | Growth curves, wildtype and PPX1,PPN1 KO reentry (`.xlsx` is the original export) |
| `20260109_plate_layout.csv` | Plate layout for the 20260109 plate |

Layout files have columns `Well`, a strain or genotype column, and the starvation
time before reentry. Wells not listed in a layout are empty.
