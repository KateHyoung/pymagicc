PLANT_POOL: Pg C > Plant carbon pool
DETRITUS_POOL: Pg C > Detritus carbon pool
SOIL_POOL: Pg C > Soil carbon pool
TOTALDEAD_POOL: Pg C > Total dead carbon pool (detritus + soil)
ATMOS_POOL: Pg C > Atmosphere carbon pool
NETCUMUL_EMIS: Pg C > Net cumulative terrestrial and fossil emissions
NOFEED_PLANT_POOL: Pg C > Plant carbon pool without CO2 or temperature feedbacks
NOFEED_SOIL_POOL: Pg C > Soil carbon pool without CO2 or temperature feedbacks
NOFEED_DETRITUS_POOL: Pg C > Detritus carbon pool without CO2 or temperature feedbacks
GROSSDEFO_EMIS: Pg C yr-1 > Gross deforestation emissions
REGROWTH_PLANT_FLUX: Pg C yr-1 > Flux to plant carbon pool due to regrowth of deforested land
REGROWTH_DETRITUS_FLUX: Pg C yr-1 > Flux to detritus carbon pool due to regrowth of deforested land
REGROWTH_SOIL_FLUX: Pg C yr-1 > Flux to soil carbon pool due to regrowth of deforested land
REGROWTH_TOTAL_FLUX: Pg C yr-1 > Total flux to terrestrial biosphere due to regrowth of deforested land
TERRBIO_AND_FOSSIL_EMIS: Pg C yr-1 > Net flux of fossil emissions and terrestrial biosphere emissions to atmosphere
NETHUMAN_CO2EMIS: Pg C yr-1 > Net flux to fossil emissions and land-use emissions to atmosphere (excludes feedbacks on terrestrial biosphere)
AIR2OCEAN_FLUX: Pg C yr-1 > Atmosphere to ocean flux of carbon
AIR2LAND_FLUX: Pg C yr-1 > Atmosphere to land flux of carbon
NETECOEXCH_FLUX: Pg C yr-1 > Net terrestrial biosphere flux to atmosphere excluding land-use and permafrost
CURRENT_GPP: Pg C yr-1 > Net primary productivity
PLANTRESPIRATION: Pg C yr-1 > Plant respiration additional to the NPP - GPP (added for additional freedom to fit data)
FACT_FERTILIZATION: UNITLESS > CO2 fertilization factor on plant growth
GPP_TEMPFEEDBACK: UNITLESS > Temperature feedback on plant growth
RESP_TEMPFEEDBACK: UNITLESS > Temperature feedback on plant respiration
DETRITUS_TEMPFEEDBACK: UNITLESS > Temperature feedback on detritus carbon pool
SOIL_TEMPFEEDBACK: UNITLESS > Temperature feedback on soil carbon pool
TURNOVERTIME_PLANT: Years > Turnover time of plant carbon pool
TURNOVERTIME_DETRITUS: Years > Turnover time of detritus carbon pool
TURNOVERTIME_SOIL: Years > Turnover time of soil carbon pool
TOTALRESPIRATION: Pg C yr-1 > Total respiration of terrestrial carbon pools
DELTA_TERRPOOLS: Pg C yr-1 > Net change in plant, detritus, and soil pools from year to year
CO2I_INVERSE_EMIS: Pg C yr-1 > Overall change in carbon budget
CH4_2CO2_OXIDISATION_EMIS: Pg C yr-1 > Flux of carbon to atmosphere due to methane oxidation
PF_TOT_TOT_POOL: Pg C > Total permafrost carbon pool
PF_TOTPLUSEMIS_POOL: Pg C > Total permafrost carbon pool plus accumulated permafrost emissions (remains constant)
PF_MS_AREATHAWED: Fraction of mineral soil permafrost carbon > fraction of mineral soil carbon thawed
PF_PEAT_AREATHAWED: Fraction of peat permafrost carbon > fraction of peat carbon thawed
PF_TOT_AREATHAWED: Fraction of total permafrost carbon > fraction of total permafrost carbon thawed
N_LIMIT_FACTOR: UNITLESS > nitrogen feedback factor on CURRENT_GPP
N_POOL: Pg N > Mineral nitrogen pool
FN_PLANTUPTAKE: Pg N yr-1 > Plant uptake flux from mineral nitrogen pool
FN_RECYCLING: Pg N yr-1 > Net re-mineralization flux of carbon to mineral nitrogen pool
FN_LOSSES: Pg N yr-1 > Loss flux of mineral nitrogen due to leaching and gaseous processes

CURRENT_GPP is a bit of a funny one. It's definitely not GPP. It's
closer to the ecological definition of NPP but does not account for some
annual fraction of plant respiration (accounted for by
PLANTRESPIRATION)
