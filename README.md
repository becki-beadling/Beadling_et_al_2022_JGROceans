# southern_ocean_fafmip

Code and scripts associated with fafmip faf-stress, faf-antwater, and faf-antwater-stress simulations and analysis of results as documented in Beadling et al. 2021, JGROceans

These simulations are part of the Flux-anomaly-forced model intercomparison project (FAFMIP).

From fafmip.org:
"FAFMIP is an atmosphere-ocean general circulation model intercomparison project of CMIP6. It addresses aspects of the Earth system response to forcing, and is of particular relevance to the WCRP Grand Challenge on sea level rise and regional impacts. Its goal is to explain the model spread in AOGCM projections of ocean climate change forced by CO2 increase."

Protocol: A prescribed set of surface flux perturbations are applied to the ocean water surface. The perturbations are obtained from the ensemble-mean changes simuatled at the time of doubled CO2 by CMIP5 models under the 1 percent per year CO2 scenario (1pctCO2), such that they are representative of projected anthropogenic climate change.

faf-stress: 
perturbation in the surface zonal and meridional momentum flux, i.e., wind stress, according to the zonal and meridional wind stress fields (tauu, tauy) from the CMIP5 ensemble mean (see above). Stress perturbation added to the momentum balance of the ocean water surface.

faf-antwater-stress: 
Simulataneously applies the momentum flux perturbation (faf-stress), and a freshwater flux of 0.1 Sv in total applied uniformly
(in time) around the coast of Antarctica, in whichever way is most suitable in the model. Our method applies a temporally-uniform freshwater flux in regions of observed ice shelf melting according to Paolo et al. (2015) and Shepherd et al. (2018), scaled to a total of 0.1 Sv. 

faf-antwater: A temporally-uniform freshwater flux applied in regions of observed ice shelf melting according to Paolo et al. (2015) and Shepherd et al. (2018), scaled to a total of 0.1 Sv. This experiment is not part of the standard fafmip protocol but was done in conjuction with the faf-stress and faf-antwater-stress experiments described above to separte the effects of wind and meltwater.



