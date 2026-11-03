Data for: Contrasting elevational diversity patterns across three Neotropical moth lineages
along an Amazon–Andes gradient (Journal of Animal Ecology, submitted). Licence: CC BY 4.0.

STUDY DESIGN
Arctiinae, Saturniidae and Sphingidae were sampled with one LepiLED light tower at 26 forest
plots (245–3,588 m a.s.l.) in southeastern Peru, one night (18:00–21:00) per plot in each of
two campaigns: 1 = September–November 2022; 2 = April–June 2023. Morphospecies were delimited
by morphology and DNA barcodes (COI).

FILES (comma-separated, UTF-8; linked by Plot)
plots_environment.csv      26 plots: location, elevation, environmental variables
abundance_Arctiinae.csv    52 samples (26 plots x 2 campaigns) x 497 morphospecies
abundance_Saturniidae.csv  52 samples x 61 morphospecies
abundance_Sphingidae.csv   52 samples x 31 morphospecies
species_list.csv           589 morphospecies with clade and totals

VARIABLES
plots_environment.csv
  Plot, Locality      Plot code and station
  Latitude, Longitude Decimal degrees (WGS84)
  Elevation_m         m a.s.l.
  ABERG               Plot in the ABERG long-term monitoring network (yes/no)
  MAT_C               Mean annual temperature (°C), TOMST loggers, Sep 2022–Dec 2023
  MAP_mm              Mean annual precipitation (mm), WorldClim 2.1
  NPPleaf             Leaf net primary productivity (Mg C ha-1 yr-1)
  NPPleaf_source      measured (ABERG litterfall, n = 9) or estimated (GAM on elevation)
abundance_<Lineage>.csv
  Sample, Plot, Campaign, then one column per morphospecies (number of individuals; 0 = absent)
species_list.csv
  Lineage, Clade (Arctiinae only), Taxon, Species_code, N_individuals, N_plots
  Names are working hypotheses ("nr" = near, "sp" = undetermined).
