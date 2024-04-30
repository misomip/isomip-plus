## Hackathon To-Do List

1. Discuss draft figures (see [Figure_outline.md](https://github.com/misomip/isomip-plus/blob/main/Figure_outline.md) ), identify any missing analyses
2. Check data - some assumptions were made when assigning the data paths e.g. versions. Please check [this list](https://github.com/misomip/isomip-plus/blob/main/notebooks/file-pointers/DataInformation.md). 
3. Model description for each model/group (including references), following MOM6 Example that Gustavo wrote. Potentially the same models submitted by different groups can have some common sections.
    1. COCO
    2. FVCOM -> Qin
    3. MITgcm-BAS - Yoshi
    4. MITgcm_BAS_Coupled - Yoshi
    5. MITgcm-JPL - Yoshi Nakayama (coordinate with Jim Jordan)
    6. MOM6-layer - done
    7. MOM6_SIGMA_ZSTAR - done
    8. MPAS-Ocean - Xylar
    9. NEMO-UKESM1is -> Robin + Nico
    10. NEMO-CNRS -> Robin + Nico
    11. POP2x - Xylar
    12. ROMS-UTAS - Mike Dinniman
4. Finalise figures e.g. checking code, dealing with NaNs, proper time periods of averaging, use of subplots. There are some notebooks with draft versions of the figures, plus Xylar's code in the `general-plotting` folder (if the notebook you desire doesn't exist please make a new one!).
    1. [Experimental design](https://github.com/misomip/isomip-plus/issues/2)
    2. [Ocean0 temperature structure ](https://github.com/misomip/isomip-plus/issues/12) -> Ocean1 -> Dave Gwyther
    3. [Melt rate spatial distribution for Ocean0](https://github.com/misomip/isomip-plus/issues/3) -> Ocean1 -> Xylar Asay-Davis
    4. [Tuning parameters for each model in a table or bar chart](https://github.com/misomip/isomip-plus/issues/4) + [top layer thickness/flux distribution](https://github.com/misomip/isomip-plus/issues/11)
    5. [Warming area-averaged ocean melt rates and overturning stream function as a function of time, showing timescales for the change (line plots)](https://github.com/misomip/isomip-plus/issues/5)
    6. [Warming end state overturning and barotropic streamfunctions (all experiments?)](https://github.com/misomip/isomip-plus/issues/6) -> Chris Bull (barotropic only)
    7. [Cooling area-averaged ocean melt rates and streamfunction strength (line plots, like in the warming)](https://github.com/misomip/isomip-plus/issues/5)
    8. [Cooling end state overturning and barotropic streamfunctions (all experiments?)](https://github.com/misomip/isomip-plus/issues/6) -> Chris Bull (barotropic only)
    9. [Scaling between melt and circulation strength for warming and cooling? Scatter plots where each data point is one time](https://github.com/misomip/isomip-plus/issues/7) -> Nico Jourdain
    10. [Thermal or haline forcing at ice front vs melt rate - quadratic scaling?](https://github.com/misomip/isomip-plus/issues/8) -> Gustavo Marques
    11. [Melt rate feedbacks - thermal/haline driving and friction velocity beneath ice shelf and contribution to melt rate](https://github.com/misomip/isomip-plus/issues/9) -> Claire 
    12. [A figure to show variation of models with their “typ” values/usage](https://github.com/misomip/isomip-plus/issues/10) -> Robin Smith + Chris
  
    13. [melt rate vs u* and melt rate vs DT](https://github.com/misomip/isomip-plus/issues/15) -> Qin Zhou and Dave Gwyther
    14. [TYP vs COM for the same model](https://github.com/misomip/isomip-plus/issues/16) -> Robin Smith,
    15. [focus on boundary layer cross section (y axis = distance from ice rather than ocean depth) -> can see temperature structure (to 5m grid resolution)](https://github.com/misomip/isomip-plus/issues/17) -> Dave Gwyther
    16. [Thermal/haline/u* in supplementary](https://github.com/misomip/isomip-plus/issues/18) -> Xylar Asay-Davis
  
        Ideally submitted back by pull request by end of June.
6. Write descriptions about each of the figures on Overleaf for the results section, especially figures that won't qualitatively change
7. Discuss the results, give feedback
8. Someone to write the Introduction?
