---
title: Predictive modelling of plant communities
description: ""
ratio: "16:9"
themes:
- apron
- descartes
- adirondack
classes:
- feature-math
- feature-nohighlight

---
class: fullbleed, math
background-color: black

![](plant3.JPG# absolute ofv w-9-12th h-7-12th)
![](plant6.JPG# absolute ofv w-3-12th h-3-12th t-0 l-9-12th)
![](plant9.JPG# absolute ofv w-2-12th h-9-12th t-3-12th l-9-12th)
![](plant7.JPG# absolute ofv w-1-12th h-5-12th t-3-12th l-11-12th)
![](plant8.JPG# absolute ofv w-1-12th h-4-12th t-8-12th l-11-12th opr)
![](plant2.JPG# absolute ofv w-5-12th h-5-12th t-7-12th l-0)
![](plant4.JPG# absolute ofv w-4-12th h-3-12th t-7-12th l-5-12th)
![](plant5.JPG# absolute ofv w-4-12th h-2-12th t-10-12th l-5-12th)

.absolute.w-100pct.pa-2.center.t-40pct.ba.bw-0.br-0.bg-white-80pct[
## <b>Predictive modelling of plant communities</b> <br> Challenges for a dynamical approach
]

---
layout: true
.footer[
<!-- - @DrIsaBlg -->
- <i class="fab fa-github"></i>iboulangeat
<!-- - isabelle.boulangeat@irstea.fr -->
- april 2019, ECOVEG 14, Toulouse
<!-- - ![logo](/img/logo.jpg) -->
]
<!--  -->

---

class:
# Prediction in community ecology

.absolute.l-4.t-4[**Why?**]
--
.absolute.l-10pct.t-5[climate change<br>habitat fragmentation<br>land-use changes<br>changes in disturbances<br>changes of human practices]

--
.absolute.r-6.t-4[**What?**]
--
.absolute.l-50pct.t-5[species composition<br>species diversity (taxonomic, functional, phylogenetic)<br>community-level attributes (annual biomass production, canopy height, ...)]


---

class:
# Modelling approach

![Image](modelling.png# w-80pct)

---

class:
# From explanatory to anticipatory models
.absolute.r-2.b-2[<sub><sup><sup>Mouquet et al. 2015, JAE</sub></sup></sup>]

Why ? more data, more tools

--

<b>Explanatory</b> : theoretical expectations and tests (hypothetico-deductive)

<b>Anticipatory</b> : predictions\* conditionnal to hypotheses (models) <br>
\*forecasts, projections

--

but necessity for theoretical frameworks to build models in both cases


---

class:
# Coexistence theories

#### What explain the presence of a species in a particular place?
--
![Image](grinnell.png# relative t-1 w-70pct)

--
![Image](hutchinson.png# relative w-70pct)

--
![Image](pulliam.png# relative w-70pct)

--
![Image](soberonVenn.png# absolute h-40pct r-2 b-4)


--
![Image](hubbell.png# relative w-70pct)


<!-- ========================================================================== -->


---
class: title, smokescreen, no-footer
background-image: url(abandon_static.png)
# Static approaches and their limits
---

class:
# The SDM framework

![Image](NBmodels.png# absolute l-5 h-70pct)
---


class:
# Explain with SDM

![Image](hierarchicalNiche2.png# absolute h-70pct t-4 l-3)

--
.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2012, EcoLet</sub></sup></sup>]

![Image](ecoletModel.png# h-60pct absolute l-6 b-4)


--

![Image](ecoletResults.png# h-60pct absolute r-1 b-4)


---
class:
# Anticipate with stacked-SDM

![Image](ccDiv.png# w-33pct r-0 b-0)
![Image](ccInv.png# w-33pct r-0 t-0)
![Image](ccTOL.png# w-33pct fr l-0)
--
<br><br><br>
Stack of multiple single-species SDM
--
<br> -> no species interactions


---
class:
# Including species interactions
1. Biotic elements as explicative variables (dominant species, community attribute, ...)
--

2. Joint modelling (jSDM) : conditional presence
.absolute.r-2.b-2[<sub><sup><sup>Pollock et al. 2014, MEE</sub></sup></sup>]

![Image](pollock2014.jpg#db w-80pct)


---
class: img-left
# Integrating stacked-SDM and assembly rules
![Image](SESAM.png# h-80pct)

.absolute.r-2.b-2[<sub><sup><sup>D'Amen et al. 2015, JOB and GEB</sub></sup></sup>]
--
<br>Historical and evolutionary constraints
<br><sup>-> potential species pool ("Dark diversity")</sup>
--
<br>Abiotic constraints
<br><sup>-> ex. SDM</sup>
--
<br>Macroecological constraints
<br><sup>-> species richness and/or trait space</sup>
--
<br>Species interactions (assembly rules)
<br><sup>-> random selection, MaxEnt, ...</sup>


---

class: fit-h1
# Predicting ecological communities : an overview
.absolute.r-2.b-2[<sub><sup><sup>D'Amen et al. 2017, Biol.Rev.</sub></sup></sup>]
![Image](DAmen2017.png# db)


<!-- ========================================================================== -->


---
class: title, smokescreen, no-footer
background-image: url(abandon.gif)
# Towards a dynamic perspective

---
class:
# Limit of a static approach

![Image](leading-trailing-edge.png# w-40pct)

--
.fixed.bg-white-80pct.t-50pct.l-50pct[->colonisation credit]
.fixed.bg-white-80pct.t-80pct.l-50pct[->extinction debt]

---
class:
# Origin of lags

--
#####Rapid <br> global changes
![Image](temperature.png# db h-60pct)
![Image](population.png# h-60pct)

<sub><sup><sup>IGBP and resilience center</sub></sup></sup>

--
![Image](perturbation.png# absolute r-3 t-4 h-30pct)

--
![Image](3facts.png# absolute w-70pct b-3 r-2)

---
class: fit-h1
# Consequences for multi-species modelling
<br>
Static approaches **infer** biotic interactions (and resulting community assembly) from species' co-occurrences
--
<br><br>-> Hypothesis of equilibrium

--
<br>
- May be a problem for calibration
- Is limiting for prediction of transient states
--

<br><br>Dynamic approaches can **simulate** species interactions

.absolute.r-2.b-2[<sub><sup><sup>Dormann et al. 2018, GEB</sub></sup></sup>]



<!-- ========================================================================== -->

---
class: title, smokescreen, no-footer
background-image: url(dandelion.jpg)
# Models based on metapopulation dynamics
---

class:
# From niche to neutral theories

![Image](coexistenceTheories.png# relative center h-80pct w-80pct)

---

class: fit-h1
# Models based on metapopulation dynamics

| STATES| **presence**| **absence**|
| ------| ---------| --------|
| **presence**| 1-p(e) | p(e) |
| **absence**| N.p(c)  | 1-N.p(c) |
 .absolute.fr.r-10pct.t-20pct.ofc.w-5-12th[e=extinction ; c=colonisation ; N=regional prevalence]
--

![Image](STM_PA.png# relative center h-70pct w-70pct)
---

class: fit-h1
# Models based on metapopulation dynamics

![Image](ex_talluto_nee.png)

.absolute.r-2.b-2[<sub><sup><sup>Talluto et al. 2017, Nature Ecology and Evolution</sub></sup></sup>]

---

class:
# Integrating biotic interactions
1. Biotic elements as explicative variables (dominant species, community attribute, ...)

2. Regroup species

3. Multi-species model
---

class:
# Integrating biotic interactions
Community level: 2 ~species
.absolute.r-2.b-2[<sub><sup><sup>Vissault et al., in revision</sub></sup></sup>]
![Image](stm_classif.png# h-60pct absolute b-3 l-2)

--
![Image](stm_succession.png# w-40pct absolute l-6 b-3)
![Image](colo4states.png# w-20pct absolute r-30pct t-60pct)

--
![Image](stm_colo.png# w-40pct absolute l-6 b-3)
--
![Image](stm_exclu.png# w-40pct absolute l-6 b-3)
--
![Image](stm_disturbance.png# w-40pct absolute l-6 b-3)
--

---


class:
# Predictions: a simulation approach
.absolute.r-2.b-2[<sub><sup><sup>Vissault et al., in revision</sub></sup></sup>]
<br>

![Image](STM_spatial.png# absolute w-50pct)
--

![Image](stm_simuCC.png# absolute w-70pct b-3)


<!-- ========================================================================== -->


---
class: title, smokescreen, no-footer
background-image: url(melezein_ubac_freaux2.JPG)
# Dynamic vegetation models (DVM)
---
class:
# The interest of DVM
.absolute.r-2.b-2[<sub><sup><sup>Snell et al. 2014, Ecography</sub></sup></sup>]

1. Multi-species!
--

2. Dynamic (simulation models) : transient states and lags
--

3. Process-based interactions : potential to predict non-analog communities
--

4. Multi-scale : individual to landscape processes
--

5. Spatially explicit

--
<br><br>
Processes of interest: reproduction, establishment, growth, mortality

---
class: compact
# Dynamic vegetation models
![Image](forestGapModel.png# absolute w-30pct t-3 r-2)
**Forest gap models (stand models)**
<br><sub><sup><sup>JABOWA (Botkin 1972), FORET (Shugart 1884), ZELIG (Smith 1988),
SORTIE (Deutschmann 1997)</sub></sup></sup>
<br>Aim : optimize **wood production** for harvest
<br>Principle : indiv. based models based on **competition for light**
--
<br><br>
**Forest Landscape Models (FLM)**
<br><sub><sup><sup>
LANDIS (He 1999), LANDCLIM (Schumacher 2004),
TreeMig (Lischke 2006), LANDIS II (Scheller 2007)
</sub></sup></sup>
<br>Aim : account for landscape processes (fire, seed dispersal)
<br>Principle : upscaling stand models
  - Cohorts, height classes, PFT, representative cells, ...
  - Aggregate spatial and temporal scales
<br>


---
class: compact, fit-h1
# Dynamic vegetation models
![Image](quillet2010.png# absolute r-2 t-3 w-40pct)
.absolute.r-2.b-5[<sub><sup><sup>Quillet et al. 2010, Env. Rev.</sub></sup></sup>]

**Dynamic Global Vegetation models (DGVM)**
<br>
<sub><sup><sup>LPJ (Sitch 2001), MC1 (Bachelet 2001)</sub></sup></sup>
<br>Aim : simulate **Net Primary Productivity**
<br>Principle : **Photosynthesis** ~ light + CO2 + temperature

--
<br><br>
**Combined DGVM and forest models**
<br>
<sub><sup><sup>LPJ-GUESS (Smith 2003), LM3-PPA (Weng 2015)</sub></sup></sup>
<br>Aim : improve the simulation of transitions between biomes
<br>Principle : model coupling (Hybrid-DGVM)

May include:
  - height-structured competition for light
  - within-PFT variation

---
class:
# A scaled overview

![Image](scale-2.png# w-70pct)

---
class: compact, img-left
# Beyond forest focus: an exemple with FATE-HD
FATE-HD among DVMs
<br><br>
![Image](FATE-among.png)
.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2014, GCB</sub></sup></sup>]

--

A landscape model dealing with **forest and non-forests**

- Response to climate (via Habitat model)
- Vegetation diversity (PFG)
- Simpified population dynamics (competition for light, dispersal, demography)
- Semi-quantitatif (easy to parameterize)
- Disturbances (fire, grazing, mowing)


---
class:
# FATE-HD model
.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2014, GCB</sub></sup></sup>]

![Image](FATE_pixel.png# absolute w-20pct l-60pct t-40pct)

--
![Image](FATE_demo.png# absolute w-20pct l-40pct t-40pct)
.absolute.r-4.t-3[<sub><sup><sup>Germination <br> Recruitment<br> Growth<br>Survival<br>Fecundity</sub></sup></sup>]


---
class:
# FATE-HD model
.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2014, GCB</sub></sup></sup>]
![Image](FATE_demo.png# absolute w-20pct l-40pct t-40pct)
.absolute.r-4.t-3[<sub><sup><sup>Germination <br> Recruitment<br> Growth<br>Survival<br>Fecundity</sub></sup></sup>]

![Image](FATE_abiotic.png# absolute w-20pct r-6 t-1)
--
![Image](FATE_biotic.png# absolute w-30pct l-4 t-5)
--
![Image](FATE_disp_all.png# absolute w-50pct r-4 b-10pct)

---
class:
# FATE-HD model
.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2014, GCB</sub></sup></sup>]
![Image](FATE_demo.png# absolute w-20pct l-40pct t-40pct)

![Image](FATE_abiotic.png# absolute w-20pct r-6 t-1)

![Image](FATE_biotic.png# absolute w-30pct l-4 t-5)

![Image](FATE_disp.png# absolute w-20pct r-6 b-10pct)

![Image](FATE_dist.png# absolute w-33pct r-3 b-40pct)

---
class:
# Parameterization : functional Groups
![Image](paramPFG.png#)
.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2012, GCB</sub></sup></sup>]
---
class:
# Is it enough to represent biodiversity?
![Image](commMeasures.png# w-80pct)
--

![Image](PFG_comp.png# w-80pct)
---
class:
# Is it enough to represent biodiversity?
<br><br>
![Image](PFG_comp_graphs.png# absolute l-20pct w-80pct)

---
class:
# Parameterization : data
![Image](paramData.png# w-80pct)
.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2014, Ecography</sub></sup></sup>]
---
class:
# FATE-HD vs SDM (at equilibrium)
Refine PFGs distribution inside their habitat limits
![Image](FATE_SDM.png# w-80pct)

---
class:
# Scenarios
![Image](scenariosPNE.png# db w-80pct)
.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2014, Ecography</sub></sup></sup>]

---
class:
# Scenarios
![Image](legend_anim.png# absolute t-10pct r-20pct h-20pct)

.absolute.l-4.t-30pct[Intensification]
![Image](intens.gif# fixed b-2 l-4 w-34pct)
<!-- .fixed.b-2.l-4[<video height="400" autoplay><source src="intens.mp4" type="video/mp4"></video>] -->
.absolute.r-5.t-30pct[Abandonment]
![Image](abandon.gif# fixed b-2 r-4 w-34pct)
<!-- .fixed.b-2.r-4[<video height="400" autoplay><source src="abandon.mp4" type="video/mp4"></video>] -->
.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2014, Ecography</sub></sup></sup>]

---
class:
# Changes in regional diversity

![Image](div_LU.png# w-80pct)
.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2014, Ecography</sub></sup></sup>]

---
class:
# Changes in regional diversity
.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2014, Ecography</sub></sup></sup>]

![Image](div_LU2.png# absolute w-40pct center)
--

.absolute.l-3.t-5[additive effects]
--

.absolute.r-3.t-5[multiplicative effects]

---
class:
# Change in local diversity
![Image](div-local.png# w-90pct)
.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2014, Ecography</sub></sup></sup>]

---
class:
# Diversity decomposition
- change in **composition**
- change in **abundances**
.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2014, Ecography</sub></sup></sup>]

--

\\[
^2D = ^0D \times EF
\\]

--
\\( ^0D = \\) richness -> beta = compositional turnover

\\( EF =\\) evenness factor -> beta = abundances re-arrangement


---
class: fit-h1, no-footer
# Changes over time, elevation and diversity dimensions
![Image](div-decomp.png)
.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2014, Ecography</sub></sup></sup>]

---
class: fit-h1
# Main highlights about the changes in functional diversity

.absolute.r-2.b-2[<sub><sup><sup>Boulangeat et al. 2014, Ecography</sub></sup></sup>]
--
<br>
**Effet of human land-use:**
Heterogeneity (beta) in average decreases in case of tree colonization but increases in case of habitat loss

**Effect of different PFG assemblages:**
The diversity response depends on elevation

**Interaction between drivers:**
Multiplicative effects are found when land abandonment is combined with climate change

---

class:
# Limits of DVMs

--

1. Difficult to parameterize
2. Difficult to evaluate error propagation
3. Limited to communities for which there is enough knowledge about constitutive species

--

Mechanisms with limited knowledge
- mortality and climate change induced mortality
- climate change impact on growth or water-use efficiency
- seeds (germination)
- phenology and shifts
- soil processes


<!-- ========================================================================== -->

---
class: title, smokescreen, no-footer
background-image: url(polarbear.png)
# Challenges and perspectives
---
class: fit-h1
# Scaling issues

--
- **space** : modelling dispersal and landscape disturbances
--

- **time** : from daily to annual processes
--

- **organisational levels** : represent the whole communities <br>(individuals->cohorts->populations->PFG->PFT->community attributes)

--
.absolute.r-2.b-30pct[_Biodiversity vs explicit processes,<br> a necessary trade-off_]
![Image](compromise.png# w-60pct)
.absolute.r-2.b-2[<sub><sup><sup>Gallien et al. 2010, DID</sub></sup></sup>]

---

class:
# Modelling dispersal
#### Upscaling from individual processes to landscape levels
indiv. demography -> pop. demography -> metapopulation dynamics
--

1. Continuity in space and time for model calibration
<br> -> inverse modelling/metamodel, resampling, remote sensing data, ...
--

2. Resolution vs extent
<br> -> heterogeneity and spread within a cell <sub><sup>see Snell et al. 2014, Ecography</sub></sup>
--

3. Dispersal kernels
<br> -> A trait-based parameterisation <sub><sup>see Tamme et al. 2014, Ecology</sub></sup>
<br> -> Landscape properties that affect seed dispersal
<br> -> Vegetative reproduction

---

class:w
# Species interactions

- Dimension reduction
<br>-> Functional groups, using networks to reduce the dimension of interactions

--
- Ontology
<br>-> A mix between functional groups and age classes?
--

- Phenology
<br>-> May impact competition for light
--

- Interactions (competition and facilitation) via soil ressources (incl. water)
<br>-> necessary to improve herbaceous species modelling
--

- Trophic interactions
<br> ex. plant-pollinisator
<br> ex. effect of grazers on seed dispersal and nutrient enrichment

---

class:
# Response to global changes

<br>

**Climate change** : impacts on demography
<br> -> hybrid approach or inverse modelling?

--

**Human practices** : retroactions
<br> -> a prospective approach combining stories and simulations?

---

class:
# Conclusion

#### Necessary trade-offs
- Species number (or ecological scale) vs explicit processes
- Resolution vs extent (space and time)

#### Solutions
- Multi-scale model integration <sub><sup>see Clark et al. 2009, Ecological Monograph ; Talluto et al. 2016, GEB</sub></sup>
- Hybrid approaches (implicit and explicit processes) <sub><sup>see Gallien et al. 2010, DID</sub></sup>



---

class: no-footer
background-image: url(marais_acide_lautaret.JPG)
# Thanks
![Image](irstea300.jpg# absolute b-3 r-3 w-10pct)


<br><br><br><br><br><br><br><br><br>
Slides can be found at http://iboulangeat.github.io/Slides/
<br>
Contact: isabelle.boulangeat@irstea.fr
