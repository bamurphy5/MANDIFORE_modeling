# MANDIFORE_modeling




# Units

## Mandifore

Fix | Description 
-------|------------
MMEAN | Monthly Average
PY | Polygon-level averages
SI | Site-level averages
PA | Patch-level averages
CO | Cohort-level averages


## Site Level

 Column Name   |   ED Name  |  Long Name |  Unit  |  Notes  | 
---------------|-------------------|-------------|-------------|-------------|
tair | MMEAN_ATM_TEMP_PY | Air Temperature |  K
precipf | MMEAN_PCPG_PY | Precipitation | kg/m2/mo
lwdown | MMEAN_ATM_RLONG_PY | Longwave radiation: Atmosphere | W/m2
swdown | MMEAN_ATM_RSHORT_PY | Shortwave radiation: Atmosphere | W/m2
qair | MMEAN_ATM_SHV_PY | Specific humidity: Atmosphere |kg/kg
psurf | MMEAN_ATM_PRSS_PY | Air pressure: Atmosphere | Pa
wind | MMEAN_ATM_VELS_PY | Wind speed: Atmosphere | m/s
CO2 | MMEAN_ATM_TEMP_PY | | umol/umol
basal.area.tree | BASAL_AREA_PY | Basal area | cm2/m2
density.tree | NPLANT_PY | Plant density | plants/m2
agb | AGB_PY | Above-Ground biomass | kgC/m2
gpp | MMEAN_GPP_PY | Gross primary productivity | kgC/m2/mo
npp | MMEAN_NPP_PY | Net primary productivity | kgC/m2/mo
nee | MMEAN_NEP_PY | Net Ecosystem productivity | kgC/m2/mo
cwd | MMEAN_CWD_C_PY | Coarse woody debris | kgC/m2
soil.c.fast | MMEAN_FAST_SOIL_C_PY | Soil Carbon (Fast pool) | kgC/m2
soil.c.slow | MMEAN_SLOW_SOIL_C_PY | Soil Carbon (Slow pool) | kgC/m2
soil.c.struc | MMEAN_STRUCT_SOIL_C_PY | Soil Carbon (Structural pool) | kgC/m2
albedo.short | MMEAN_ALBEDO_PY | Albedo | ---
par.ground | MMEAN_PAR_GND_PY | PAR absorbed by ground | ---
soil.moist.surf | MMEEAN_SOIL_WATER_PY | Soil water content: surface| m3/m3 
soil.moist.deep | MMEEAN_SOIL_WATER_PY | Soil water content: deep| m3/m3
soil.moistpot.surf | MMEAN_SOIL_MSTPOT_PY | Soil matric potential: surface | m
soil.moistpot.deep | MMEAN_SOIL_MSTPOT_PY | Soil matric potential: deep | m
soil.temp.surf | MMEAN_SOIL_TEMP_PY | Soil temperature: surface | K
soil.temp.deep | MMEAN_SOIL_TEMP_PY | Soil temperature: deep | K
runoff.surface | MMEAN_RUNOFF_PY | Water runoff | kg/m2/mo
runoff.subsurf | MMEAN_DRAINAGE_PY | Water runoff | kg/m2/mo
transp | MMEAN_TRANSP_PY | Leaf transpiration | kg/m2/mo
snow.depth | MMEAN_SFCW_DEPTH_PY | Depth - temporary water layer | m
swe | MMEAN_SFCW_MASS_PY | Water mass - temporary water layer | kg/m2
lai | MMEAN_LAI_PY | leaf area index | m2leaf/m2

## Patch Level

 Column Name   |   ED Name  |  Long Name |  Unit   
---------------|-------------------|-------------|-------------|
age | AGE | time since last disturbance  |  Years
area.patch | AREA | patch area (relative to the total SITE area) | No metadata available
n.cohorts | PACO_N | The number of cohorts in each patch | ----
patch.co.start | PACO_ID | The global index of the first cohort in all patches | ----

## Cohort Level

 Column Name   |   ED Name  |  Long Name |  Unit   
---------------|-------------------|-------------|-------------|
pft | PFT | Plant Functional Type | 5=grass; 9=early hard; 10=mid hard; 11=late hard
dbh | DBH | Diameter at Breast Height | cm
ba | BA_CO | Basal Area | cm2/tree
carbs | CB | Carbon Balance | scale 0 to 1; 1 = not stressed
stress | CBR_BAR | Running mean relative carbon balance | scale = -1 to 1
height | HITE | Height | m
lai | LAI_CO | Leaf area index | m2leaf/m2
agb | AGB_CO | Above-Ground biomass |  kgC/tree
dens.pch | NPLANT | plant/m2 | trees/m2

