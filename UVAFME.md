---
layout: page
title: UVAFME 
subtitle: Individual tree-based modeling
---

My graduate and postdoctoral work focused on updating and applying an individual tree-based model called UVAFME (the University of Virginia Forest Model Enhanced). I am still the lead developer for UVAFME.

![UVAFMEAnimation](assets/img/UVAFME_Animation.gif){: .mx-auto.d-block :}

UVAFME simulates the annual establishment, growth, and mortality of individual trees on independent patches (i.e. plots) of a forested landscape. Through a Monte Carlo-style aggregation, the average of several hundred of these independent patches represents the average expected conditions of a forested landscape through time. As such, output from UVAFME is comparable to a statistically robust sampling of replicate forest inventory plots.

Individual tree growth for each year is calculated through optimal diameter increment growth, modified by available resources and species- and tree size-specific tolerances to temperature, and light, and soil conditions. Individual trees can thus compete with one another for above- and belowground resources. Establishment of seedlings and saplings is based on species-specific resources and environmental tolerances as well as plot conditions. Trees may die from age- or growth stress-related factors or by disturbances (i.e. fire, windthrow, or insect infestation). Trees that die, as well as annual leaf litter and coarse woody debris are transferred to litter cohorts for decomposition. 

Originally developed as FAREAST for use in boreal Eurasia
(see [Yan & Shugart 2005](https://www.jstor.org/stable/3566334?seq=1#page_scan_tab_contents)),
the model has since been updated for use in [boreal Russia](http://iopscience.iop.org/article/10.1088/1748-9326/aa5eed),
[the southern Rocky Mountains](https://www.sciencedirect.com/science/article/pii/S0304380016306482), [the eastern US](https://www.nature.com/articles/srep22133), as well as [boreal North America](https://www.sciencedirect.com/science/article/pii/S030438001930273X).

See the [UVAFME website](https://uvafme.github.io) or [GitHub page](https://github.com/UVAFME/UVAFME_model) for more information about the model.
<br>
<br>
# Recent papers using UVAFME

| Title                | Authors   | Journal | Year | 
| :------------------- |:--------- | :--- |:--------: | 
| [Bottom-up drivers of future fire regimes in western boreal North America](https://iopscience.iop.org/article/10.1088/1748-9326/ac4c1e)| Foster, Shuman, et al. | *Environmental Research Letters* | 2022 |  
|[ Bridging implementation gaps to connect large ecological datasets and complex models](https://doi.org/10.1002/ece3.8420) | Raiho, Nicklen et al.  | *Ecology and Evolution* |  2021 | 
| [Importance of tree- and species-level interactions with wildfire, climate, and soils in interior Alaska: Implications for forest change under a warming climate](https://www.sciencedirect.com/science/article/pii/S030438001930273X?via%3Dihub)  | Foster, Armstrong, et al.  | *Ecological Modelling* | 2019 | 
| [Modeling the interactive effects of spruce beetle infestation and climate on subalpine vegetation](https://doi.org/10.1002/ecs2.2437) | Foster, Shuman, et al.  | *Ecosphere* | 2018 | 
| [Fire disturbance and climate change: implications for Russian forests](https://iopscience.iop.org/article/10.1088/1748-9326/aa5eed)  | Shuman, Foster, et al.  | *Environmental Research Letters* | 2017 | 
| [Validation and application of a forest gap model to the southern Rocky Mountains](https://doi.org/10.1016/j.ecolmodel.2017.02.019)| Foster, Shuman, et al.  | *Ecological Modelling* | 2017 | 
