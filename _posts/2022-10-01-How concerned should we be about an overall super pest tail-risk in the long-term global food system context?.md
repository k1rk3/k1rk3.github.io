---
layout: post
title: How concerned should we be about an overall super pest tail-risk in the long-term global food system context?
date: 2022-10-01
---

In 2021, 9.8% of the global population were undernourished ([FAO](https://www.fao.org/3/cc0639en/cc0639en.pdf)). Although hunger has steadily decreased in the last decades (see [here](https://ourworldindata.org/hunger-and-undernourishment#undernourishment-by-world-region)), in the last few years it has instead grown (in percentage terms), including a sharp increase due to the COVID-19 pandemic in 2020. It has been estimated that globally, on average, around 20-30% of crop production is lost to agricultural pests and pathogens [(Savary et al 2019](https://www.nature.com/articles/s41559-018-0793-y#Sec3)). Every now and then, a particularly dangerous pest emerges that causes catastrophic damage within a particular region or to a particular species of plants. Examples include the [Colorado potato beetle](https://en.wikipedia.org/wiki/Colorado_potato_beetle#Potato_crop_pest), which in the absence of control measures often results in 100% yield losses (citation: [this fun website](http://www.potatobeetle.org/resistance/index.html)); _Hemileia vastatrix_, a fungus that causes coffee leaf rust, a disease which causes an estimated [worldwide yield loss](https://en.wikipedia.org/wiki/Hemileia_vastatrix) in coffee production of 15%; and many others, see [here](https://www.fao.org/3/cb4769en/cb4769en.pdf) for more examples. Additionally, we should expect that there is a real possibility of the emergence of a _globally_ catastrophic plant pathogen, either naturally or perhaps due to malicious actors creating an engineered pathogen. It’s possible to imagine a pesticide resistant pest which, by consuming many kinds of crops and spreading fast, could threaten our global food security. In fact, superpests[^1] have been identified as one of six crop-killing scenarios that could cause mass starvation or human extinction ([Denkenberg and Pearce 2014](https://allfed.info/images/pdfs/Feeding-Everyone-Futures-preprint.pdf)). There are a couple of insects we know of that we should be worried about, for example the [desert locust](https://en.wikipedia.org/wiki/Desert_locust), or the [diamondback moth](https://en.wikipedia.org/wiki/Diamondback_moth), and the [fall armyworm](https://en.wikipedia.org/wiki/Fall_armyworm). In this post, I’ll focus on the risk posed by the fall armyworm. 


# Fall armyworm (FAW)


**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXd1AHWmxQcirr4tYXANNpavCuZYEvN80hXD9L1BGK-K2gZqHSNg5YxbscXNUeATwxXkPHuykCMMkl-Ki__QhGL1bTPqNGeSoJ6SuRwmY0e_CBypcCSXV5x_aRnKoiIP9sNIqyl8QoJRGJ3JIWKRXWaGzcg?key=jz_Lj4q4c3TGnpbx2nJAhw)**

[https://en.wikipedia.org/wiki/Fall_armyworm#/media/File:Spodoptera_frugiperda.jpg](https://en.wikipedia.org/wiki/Fall_armyworm#/media/File:Spodoptera_frugiperda.jpg) 


## What makes this pest scary?

Fall armyworm (_Spodoptera frugiperda_) is a species of insects in the order Lepidoptera. It consumes **over 300 different species** of plants, including many that are of high agricultural importance: maize, rice, wheat, sorghum, etc. ([Ramsamy et al 2021](https://link.springer.com/article/10.1007/s10340-021-01411-1#Sec3)). Out of these, maize is both one of the primary targets of FAW ([du Plessis et al 2018](https://www.researchgate.net/publication/327423712_Spodoptera_frugiperde_-_CLIMEX_modelling_du_Plessis_van_den_Berg_Ota_Kriticos_2018_CSIRO-InSTePP_Pest_Geography_June_2018_Canberra)), and a major staple food in sub-Saharan Africa and America. Most of the damage that FAW does to crops occurs during its larval stage, and specifically during the last phase of the larval stage (lasting a few days starting at around day 8-10 since hatching ([Agboyi et al 2019](https://pdfs.semanticscholar.org/e14d/5085898046055a8418a60d2ffd42b64158e0.pdf))). During that phase it eats around 75% of the total consumption that occurs during its development. This means that FAW appears to cause huge damage overnight. It’s not uncommon for farmers to wake up and find their crops severely damaged due to the insect having reached its most destructive life stage in the night. 

FAW is native in the Americas, and present throughout the year in Florida and southern Texas. It lacks a [diapause](https://en.wikipedia.org/wiki/Diapause) mechanism, meaning that it can’t survive winters at higher latitudes where it gets colder. However, the FAW has an exceptionally good ability to migrate – during the summer, it consistently travels 2,000 km to make its way up to the Canadian border every year. This is thanks to its ability to fly up to an altitude of hundreds of meters and then get transported by winds – it can travel around 100 km during a single night. In the last 6 years, the FAW has also spread to Africa and parts of Asia. After being first sighted in Africa in 2016, it has now spread to over 40 countries, including most of sub-Saharan Africa ([Ramsamy et al 2021](https://link.springer.com/article/10.1007/s10340-021-01411-1#Sec3)).


## What could it do in the future?

Summary:
- We can use bioclimatic models to predict whether a geographic area is suitable for an insect.
- We expect climate change to affect the geographic distribution and abundance of insects.
- A literature review of climatic modeling studies shows that there are highly suitable habitats for the fall armyworm in tropical and subtropical areas on all continents. 
- Europe, USA, South Africa, China, Russia, Central Asia, Australia are all vulnerable to yearly fall armyworm migrations.
- The effects of climate change turn out to be not that clear: a few models suggest an increased suitable area for fall armyworm, while others predict a decrease.


### Predicting the spread of fall armyworm

The distribution of a species (i.e. where it lives) depends on a number of biotic and abiotic variables. For example, an area can be too cold or too dry for an insect. Host availability, soil type, competition due to other species and many more biotic variables would affect the habitat suitability as well. Of these, the climatic variables are the easiest to measure and use for providing estimates of the potential range of a species. One popular tool for bioclimatic species distribution modeling is [CLIMEX](https://www.hearne.software/getattachment/199e1f3e-460a-4ac8-8f7f-1eeee84110c7/Climex-v4-User-Guide.aspx). How does that model work? A fundamental assumption is that the suitability of a location is determined solely by its climate[^2]. The following steps are taken:


1. The model has parameters describing the climatic preferences of FAW, for example its upper and lower temperature thresholds, or optimal soil moisture. The initial values of these parameters  are usually chosen based on knowledge of the biology of the insect and on previous studies.
2. Based on these parameters, the model outputs a predicted spatial distribution of the species.
3. This output is compared to the current empirical distribution data of the species, preferentially only the data from the region in which it is native to[^3]. 
4. The parameter values are **iteratively adjusted** to increase the fit between the model output and known distribution data. 

One way to verify that the model is making good predictions is to only use the data of the native range of the species for the parameter fitting, and check that the predictions of the model also match for ranges where the species is invasive. In the case of fall armyworm, you would therefore use the native distribution data from America to fit the parameters, and use the data from recent invasions to Africa to verify the accuracy of the model. 

The distribution data used in Timilsena et al 2022:

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXehdzYml_DN8_sk9MooiNTrPBUJVcQdSu8s7xuAUyGcuEiYMDxojLFpvQAovd-2mJdcvlkqwRDSEaqlNqsHXz9bwNNALh1Im-GCQc9qqmgiHWhmUyGnuSGAc4ZZBObL0HO5XiXpX2rmmvMG3XI5wPyMWA?key=jz_Lj4q4c3TGnpbx2nJAhw)**



What are some results from papers using CLIMEX?

From Timilsena et al 2022:
**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe0yViu9rdjk18uVw0ntZB-2UpIymyTn1SBvH6LYnKkdQwP-9DJChl5XpPV0e5Ak74Fc7OM-W_rOW85GXnL84VW2P3P_1gJulwT-9Wog0hZEgKqD-nauSRPZML2DgpNpVfsGYAbEOiZUHoeW64onRBs6do?key=jz_Lj4q4c3TGnpbx2nJAhw)**

On the left we see the suitability for permanent habitats of the fall armyworm under two irrigation scenarios: a) rainfed only and 2) irrigation of 2.5 mm day<sup>−1</sup> for areas that are known to be irrigated. On the right, the potential areas for seasonal growth under the two irrigation scenarios are depicted. 

From du Plessis et al 2018: 
**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXd4I8-DW_M6S58PBzRL0zW44krRcra6H-V1Q-8TTRsridfwHzjDVlkWogCRPcc6CA9NfVKvWr1tZj9cnvVboiXjGArXyU9BPS4IiO3pktS9uf5Xlq5WJdizx58-BI1MiWdOPcpLHy_srbyBoKG7Lv5DOs8?key=jz_Lj4q4c3TGnpbx2nJAhw)**


These two models are roughly in agreement: in South America, almost everywhere except the Andes and Argentina is highly suitable for fall armyworm establishment. Similarly for West and Central Africa, India, South-East Asia and Indonesia. Seasonal populations could likely appear in the USA, eastern China, some parts of Europe, southern Africa and Australia. 

The other model that has been used a lot is called [MaxEnt](https://biodiversityinformatics.amnh.org/open_source/maxent/). “Maxent estimates the distribution (geographic range) of a species by finding the distribution which has maximum entropy (i.e. is closest to geographically uniform) subject to constraints derived from environmental conditions at recorded occurrence locations” ([Phillips et al 2017](https://onlinelibrary.wiley.com/doi/full/10.1111/ecog.03049)). This model is useful because it makes predictions based only on occurrence data, and does not require absence data ([Phillips et al 2006](https://www.sciencedirect.com/science/article/abs/pii/S030438000500267X?via%3Dihub)). See Elith et al ([2010](https://onlinelibrary.wiley.com/doi/10.1111/j.1472-4642.2010.00725.x)) for a detailed explanation of MaxEnt models.

An important step when using maximum entropy models is filtering the distribution data prior to running the model. This is necessary due to the systematic sampling bias where occurrence data includes more data points from locations that are better-surveyed ([Kramer-Schadt et al 2013](https://onlinelibrary.wiley.com/doi/pdf/10.1111/ddi.12096)). A few authors of the FAW distribution modeling papers have not made this explicit in their work.

Some results from recent papers using this model:
**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdbN4nLi5wrGH3xHmNuFLqkt-aTo1XOMicGA1bJCfhYpt81gZUoktsmcaKrxn1YGZ5uxYCdPuw0pmAQplEQQ6swidiWJH4YujUfhdoHTmuJ00cU1zfrDlSx356LTN7xPbLIR52GleJwa3_r9h-eKN7skn8?key=jz_Lj4q4c3TGnpbx2nJAhw)**


from Ramsamy et al 2021

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXc8icE5RLrrIhRd3QRmMFM5wkRjxWOgALRgurRqwaJfmRwU3Aqubx9tFExXszpos9ZrkCBSo0TzxjnghEwD47-a6ug3n4ZOKGSkCA3B1g7QGdzpxTtDgkL6mr4G8iNDumzXOg-m-fY7REOpBcjYLJAIMEk?key=jz_Lj4q4c3TGnpbx2nJAhw)**

from Zacarias 2020

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeTP5_XNNky60ZgtOtwh9uB_h_7OH3jrLjE7qn4wmlCi2fqywI7Rv_9hzipUi-wlrCg3Kai8z6JyujR6NVqHrK7d6ST7xUTsdAbYmddupKf_5ggBVCPqO0Wuc0RhVyW7AdNfYd1Ll0DTIXwSUUw6ENO19s?key=jz_Lj4q4c3TGnpbx2nJAhw)**

from Liu et al 2020.

There is more variability in the predictions here than for the two CLIMEX models. None of these studies also distinguished between permanent and migratory populations. Nevertheless, some general predictions still match the CLIMEX predictions: 



* western and central Africa are highly suitable
* a large portion of South America is suitable
* parts of Europe, India, China and Indonesia are vulnerable.

# How might climate change affect the distribution of FAW?

There are some general arguments/heuristics:
* higher temperatures increase the metabolic rate of insects
    * therefore they might increase their food consumption, the number of generations per year, decrease the development time, etc. (for example [Ziska and McConnell 2015](https://pubs.acs.org/doi/10.1021/jf506101h))
    * however, some populations already live in places where the ambient temperature is the optimal temperature 
        * for them, increased temperatures would decrease their number / damage they could do
* currently, the potential distribution boundaries are partly due to the too cold temperatures at higher latitudes 
* climate change will in general increase temperatures at mid-latitudes
* so seems plausible that the potential spread of FAW will become wider 

However, this isn’t very conclusive[^4] [^5] (see also [Lehmann et al 2020](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1002/fee.2160)). Fortunately, the same climatic models we used to predict the current potential distribution of FAW can be used to predict the distribution under different climate change scenarios. We just have to use the data from general circulation models as inputs instead of the current climate variables. Unfortunately, the different studies that have done this disagree quite significantly on the effects of climate change. Some authors find that the potential range will increase globally, some find the opposite (see table). 

| Paper<br>                 | Model used<br>                                              | dataset<br>                                                                                 | distinction between permanent and transient populations?<br> | change due to climate change<br>                                                                                                                             | notes<br>                                                                                                               |
| ------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| Ramsamy et al 2021<br>    | MaxEnt<br>                                                  | current distribution: WorldClim<br><br>2050 and 2070: BCC-CSM2-MR and MIROC6 from CMIP6<br> | yes<br>                                                      | increase of around 8.83% of global suitability<br>                                                                                                           | didn’t process distribution data<br>                                                                                    |
| Zacarias 2020<br>         | MaxEnt<br>                                                  | current: WorldClim<br><br>2070: CCSM4, MIROC-5 and GISS-E2-R<br><br>CMIP5<br>               | yes<br>                                                      | increase of around 14.20% of global land<br>                                                                                                                 | takes into account also the potential co-occurrence with host plants<br>                                                |
| Liu et al 2020<br>        | MaxEnt<br>                                                  | WorldClim<br>                                                                               | no<br>                                                       | decrease of around 13% globally<br>                                                                                                                          | explores the distribution patterns of fall armyworm under global land-use and different scenarios of climate change<br> |
| Fan et al 2020<br>        | MaxEnt<br>                                                  | WorldClim<br>                                                                               | no<br>                                                       | N/A<br>                                                                                                                                                      | didn’t process distribution data?<br>                                                                                   |
| Ramirez-Cabral 2017<br>   | CLIMEX<br>                                                  | CliMond<br>                                                                                 | no<br>                                                       | increase in North America and a marked reduction in South America by 2100<br>                                                                                | Americas only<br>                                                                                                       |
| du Plessis et al 2018<br> | CLIMEX<br>                                                  | The CliMond 1975H historical climate dataset<br>                                            | yes<br>                                                      | N/A<br>                                                                                                                                                      | unclear what distribution data was used<br>                                                                             |
| Baloch et al 2020<br>     | MaxEnt<br>                                                  | WorldClim<br>                                                                               | no<br>                                                       | N/A<br>                                                                                                                                                      | mostly focused on Central Asia;<br>                                                                                     |
| Timilsena et al 2022<br>  | CLIMEX<br>                                                  | current: CliMond<br><br>2030, 2050, and 2080: CSIRO-Mk3.0 GCM, and MIROC-H GCM<br>          | yes<br>                                                      | in Africa:<br><br>decrease in optimal areas of 11.6% or 7.2% <br><br>increase in unsuitable areas <br><br>(small changes in marginal and suitable areas)<br> | future projections in Africa only;<br><br>considered two irrigation scenarios<br>                                       |
| Tepa-Yotto et al 2021<br> | MaxEnt<br>                                                  | current: WorldClim<br><br>future: CMIP5<br>                                                 | yes<br>                                                      | decrease <br>                                                                                                                                                | also model FAW parasitoids’ habitats suitability<br>                                                                    |
| Early et al 2018<br>      | ensemble Species Distribution Model (that they created)<br> | CRU (New et al 2002)<br>                                                                    | yes, migratory data not used<br>                             | N/A<br>                                                                                                                                                      | <br>                                                                                                                    |



## How much yield loss does FAW cause directly?

This is quite hard to estimate. If a farm experiences a loss in yield due to a pest outbreak, it is difficult to know how much of the damage was due to the pest itself. However, there are some estimates in the literature. 

Reported yield losses in maize range from 11% to 67% (Gilioli et al). [Day et al (2017](https://www.invasive-species.org/wp-content/uploads/sites/2/2019/03/Fall-Armyworm-Evidence-Note-September-2017.pdf)) have estimated that “the arrival of fall armyworm in Africa has the potential to cause maize yield losses in a range from 8.3 to 20.6 million tonnes per annum” out of a 39 million tonnes of expected maize production for the continent. These estimates are based on extrapolating the estimates of yield losses by individual farmers in Ghana and Zambia to 10 other major maize producing countries in Africa. Overton et al ([2021](https://www.sciencedirect.com/science/article/pii/S0261219421001113)) have reviewed the different estimates of FAW caused yield loss. For maize, they report two numbers, **17.31 ± 0.90%** and **35.57 ± 2.45%** for experimentally derived yield losses and interviews/surveys of yield losses experienced by farmers, respectively. These numbers describe how much yield is lost on a particular field that is infested with FAW as compared to an uninfected field.

Additionally, FAW consumes other crops besides maize. Overton et al report the following yield losses: 25.88 ± 3.42 % for sorghum, 24.35 ± 6.28% for sweet corn, 4.82 ± 3.36% for rice, 12.82 ± 4.24% for bermudagrass.

In America[^6], where farmers have had to deal with FAW for centuries, chemical insecticides are commonly used to fight the pest. For example, in Brazil, an average of five sprays per maize cycle may be required [(Ribeiro et al)](https://www.cabi.org/ISC/FullTextPDF/2015/20153189617.pdf). However, repeated insecticide sprays are not something most smallholder farmers in Africa (and probably Asia) can afford [(Sisay et al)](https://onlinelibrary.wiley.com/doi/full/10.1111/jen.12534?casa_token=TlaGtzqMEz8AAAAA%3A8DkAgq4f0S4n9tC0nQG1GN-jWkfIZ4EnSbFYHgeBIeRh98BrZiYkH1TxqVqkUSaGR7XoJacbxQROcsU_). Therefore, FAW could spread relatively unmitigated throughout those regions and cause significant damage. 


## How much damage could FAW do?

We are interested in estimating the tail-end damage from FAW. In order to make an estimate for a worst-case scenario, we might make the following assumptions and simplifications:



* FAW has spread to and established permanent populations in all the regions where the bioclimatic models have predicted that there are suitable habitats.
* In those regions it infests every single field that grows a suitable crop.
* On those fields it causes yield losses of the order it has previously[^7]. 
* From these areas it spreads to nearby areas with 1) suitable climates for temporary populations and which 2) grow suitable host crops.
* FAW will cause yield losses of the same order in invaded regions as in permanent habitats[^8].
* Its primary target will be maize, or at least a major fraction of the damage FAW does will be on maize.[^9]

We used these simplifications to compute an estimate of the amount of damage FAW could do. We used the model outputs from Timilsena et al 2021 and [MapSPAM](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/PRFF8V) data on maize distribution around the world. See the methodology section for more details. Under the approximations that we made, **91.1% of the world’s maize production** takes place in a suitable area for FAW habitat (including the migratory areas). Therefore, whatever number we use for the yield loss in a region suffering from an outbreak, this model will return roughly the same number for the global yield loss. Using the 17.31% yield loss number, this would mean a** 16% global yield loss in maize**. If we only consider the areas where FAW can establish a permanent population, then the fraction of maize produced in that area drops to 24.7% and the global yield loss to 4.2%. If instead, the higher estimate of 35.57% was used, the respective global yield losses would be 32% and 8.7%.

However, here’s a reason why these numbers are not quite accurate: we have effectively assumed that the current yield loss to FAW is 0%, but this is not quite true – in reality, we are already “paying a fraction of the worst-case FAW tax”. Savary et al ([2019](https://rdcu.be/cVEs3)) report the global loss of maize yield to FAW as 2.85%. As this is small, it does not change the conclusions above by much (it’s certainly not the main source of uncertainty). But see Appendix 1 for an explanation of how to account for this, as well as some calculations.

We have not done the calculation for other crops, but our intuition says that the expected global damage to those would be between 0.5 - 1x that of maize. We expect the effect to be smaller mostly because of the large overlap between maize production areas and suitable regions for FAW. The overlaps aren’t as large for other crops.


# Complex effects

The following section is mostly just a series of random thoughts I have. Everything should be taken with a large grain of salt.

In order to make any conclusions on the extent of the danger from FAW, it is necessary to consider the risk in the context of the complex system of our interconnected world. It has been argued that in the future, most disasters will propagate through the global infrastructure network and thus will be cascading events ([Alexander and Pescaroli 2019](https://ucl.scienceopen.com/document/read?vid=fa7edca1-ed1e-4c79-9c3d-dc6c19abd54e)). On the scale of global food markets, the fact that distant food systems are linked together usually means reduced food insecurity in any one place. A global market can quickly compensate for deficiencies somewhere. However, it also creates new risks, such as multiple breadbasket failure[^10] or more rapid spread of plant pathogens ([Simpson et al 2021](https://www.sciencedirect.com/science/article/pii/S2590332221001792)). Recently, some people have made steps towards creating systematic frameworks for this type of complex systems oriented type of thinking, for example [Simpson et al](https://www.sciencedirect.com/science/article/pii/S2590332221001792#bib97) (2021) and [Richards et al](https://link.springer.com/article/10.1007/s10584-021-02957-w#Sec6) (2021) in the context of climate change and food security.

Climate change acts as a stressor on the food system, making disasters more likely and more frequent ([Tigchelaar et al 2018](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6042138/)). Under 4° of warming, the probability of a synchronous yield loss of more than 10% in the three largest maize producing countries rises to 69% compared to today’s virtually 0 probability (ibid). And this is just due to changed climatic variables, not taking into account pests and other climate related threats. Climate change is a driver of increased societal vulnerability and indirect stresses, such as loss of land, economic damage, and most importantly for this post, food insecurity. Those stresses could “coalesce into system-wide synchronous failures” ([Kemp et al 2022](https://www.pnas.org/doi/10.1073/pnas.2108146119#sec-6)), and thereby cause societal collapse. Recently, [Kemp et al (2022](https://www.pnas.org/doi/10.1073/pnas.2108146119#sec-6)) have argued that our knowledge about whether and how climate change could cause extinction or societal collapse is dangerously sparse. They provide a high-level causal loop diagram of the cascading effects of global warming, with food shortage as one of the nodes:

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfyO56qA_fLmCiClzDuo8tsDw3YLoRNWYO8NivwqE6rsGNrLp5LXSTegaJTLVqKbrAOFHFItrAZy5indPbOX27qUtRNFD8Nw5HxaKshX7SJl0RSrmef8g4OlWKyWTJHqRgIDolvkYEEOpmX0G78WGbuNaY?key=jz_Lj4q4c3TGnpbx2nJAhw)**
We are interested in exploring the interactions of food shortage with other nodes on a more fine scale. [Richards et al](https://link.springer.com/article/10.1007/s10584-021-02957-w) have compiled a [causal loop diagram](https://link.springer.com/article/10.1007/s10584-021-02957-w/figures/5) that characterizes the links between climate change, food insecurity and societal collapse based on 41 studies. This is still a high level view though. In this post I try to focus on the following questions:

* How do agricultural pests (as a type of food security risk) in particular fit into this system?
* How does FAW specifically fit into it?

I will first discuss some general interactions between food insecurity, climate change and societal collapse. I will then propose some ways in which pests and the fall armyworm interact with other factors in this complex system. This will by no means be a complete description.


## General food insecurity interactions with society

### Conflict

Increased food insecurity can trigger large migrations to areas with more food (TODO: examples). For example, in Ghana, migration was shown to be a typical strategy for dealing with reduced farm productivity (Rademacher-Schulz et al. 2014). Large migrations sometimes result in large refugee camps where people are crowded together in very bad living conditions, potentially even raising the risk of a disease rapidly spreading through the camp and spilling over into the rest of the world, i.e. increasing the risk of a pandemic. Relatedly, famines often cause domestic or international conflict, for example triggered by higher food prices, that can end up in violence ([Richards et al 2021](https://link.springer.com/article/10.1007/s10584-021-02957-w#Sec6)). It has been argued that a climate change driven spike in global food crises was a proximate factor behind the uprisings of Arab Spring ([Abel et al 2019](https://www.sciencedirect.com/science/article/pii/S0959378018301596?via%3Dihub)). Moreover, violent conflict is also a driver of migration. Mass emigration can decrease food security (and exert pressure on infrastructure in general) in the target region, due to the now larger concentration of people there. That can again lead to tensions. Conflict and political instability contribute to the risk of societal collapse due to institutional breakdown ([Richards et a 2021](https://link.springer.com/article/10.1007/s10584-021-02957-w#Sec6)).

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXd5Jtkw_pzrateiCsF_JSY2iNHTM5WCSx3laTdA7eR5Y6IwDtRU3EM_IWoUfkW7j6z0GTw-w5Gx6d6_4iuV9CWV4yEufOh7804GqiFsEI5vBvQDEI6GEp_mB0GieDYvs9rsoesWEZ_VyHCLlXZrDM7GUbw?key=jz_Lj4q4c3TGnpbx2nJAhw)**

### Alternative food sources

A significant reduction in one food source will force people to look for alternatives, which can sometimes have unpredictable consequences. For example, there was a decline in large mammal populations in West Africa during times of low fish supply (got it from [here](https://www.nature.com/articles/s41893-018-0210-1) but not the primary source). 

## Food insecurity due to pests

### Poverty and pesticides

In developing countries, the median crop growing farm is much smaller than one in the US, for example (average area of maize grown per maize growing farm in Africa was 0.88 ha compared to 77.18 ha in North America ([Erenstein et al 2021](https://www.sciencedirect.com/science/article/pii/S2211912421000675))). This means that once a pest invades, a large number of individual farmers are all left to make their own decisions on how to fight the threat. Quite often in the case of novel pathogens, the farmers have insufficient information for making these decisions (cite). From the point of view of a farmer, a reasonable course of action is to spray your maize field with a bunch of chemicals that will surely prevent the pest from eating all your corn. This is indeed often the main course of action ([cite](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8568106/#pone.0257736.ref018)), even though their access as poor African farmers to **pesticides**, and to information on which pesticide to use, is relatively limited ([Hu 2020](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7663108/)). FAW specifically has significantly increased insecticide use in the regions it’s invaded ([Abro et al 2021](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8568106/)). However, the pesticides used for fighting FAW also kill a good proportion of its natural predators ([Harrison et al 2019](https://www.sciencedirect.com/science/article/pii/S0301479719306097#bib102)). The insect will also develop **resistance** against the chemical that was used, making it even harder to fight it in the future. In fact, FAW has already developed resistance to many active ingredients of pesticides of different classes ([cite](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8568106/)). Additionally, insecticide overuse has negative effects on the environment and biodiversity in general (not just the pest predators), thereby further aggravating food insecurity ([cite](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8568106/)). Perhaps it is also possible that excessive pesticide use against a new pest could deplete the stores faster than in a regular year, meaning that there are fewer resources left for crops that were not threatened by FAW. But this is just a random guess by me.


### FAW specific effects

What are some ways in which a FAW outbreak differs from any generic pest outbreak? For now, FAW is a relatively new threat in countries outside of America, meaning that expertise in dealing with it has not yet developed. However, it is quickly becoming permanently established in many places. This could actually be a good thing in some sense, because a threat that is expected to plague you every year is less likely to cause a large shock to production. I think the intuition here is something like if you know that a pest will destroy some roughly constant fraction of your crops every year, you learn ways to adapt to this. If, however, the threat landscape is more like that from the desert locust that invades sporadically and very fast, you might lose a large fraction in one year (even if when averaged over multiple years the losses are roughly the same from the two pests), then the effect might be worse. However, this same argument could perhaps be made for countries that lie in the regions that are suitable for migratory populations of FAW (and not the permanent populations). We don’t expect the invasions to occur every year and with the same intensity, so there is an analogy to desert locust outbreaks. 

What are some compounding risks/factors that we expect to co-occur with FAW invasions?

It’s possible to imagine a pest that prefers dry conditions, and thrives in drought conditions. Then, a country devastated by drought and already quite low on food stores might be driven to catastrophic food insufficiency if the pest were to invade on top of that. Fortunately, however, it seems that FAW is not a particularly drought friendly pest. According to Timilsena et al (2022), the current suitable range of FAW in Africa is mainly expected to decrease due to increased heat and dry stress. But this general idea that there are some conditions that benefit the FAW which also enhance the success of some other stressor is still important. A better guess for what some of these might be is that many insects overlap in their preferred climatic conditions ([Lewis et al 2016](https://pubs.acs.org/doi/10.1021/acs.jafc.6b01320)). Therefore, if the conditions are right for FAW to invade, it’s possible that other pests are also having a good time and causing higher than average yield losses. The outcome might be especially dire if the different pests target different crops, devoting a region of many different food sources simultaneously. For example, if a country in Africa is experiencing both a desert locust and a fall armyworm outbreak, it is plausible that most of its main agricultural crops are affected. Ethiopia is one possible example – it has recently suffered a severe desert locust outbreak that caused damage to all sorts of crops, pasture and even trees ([Ilukor and Gourlay 2021](https://openknowledge.worldbank.org/bitstream/handle/10986/35605/Locust-Invasion-in-Ethiopia-Scope-and-Impact-Evidence-from-the-World-Bank-Supported-High-Frequency-Phone-Surveys.pdf?sequence=1)). 

Another possible scenario of this type depends on FAW needing water. Some models predict that the only suitable habitats in North Africa are ones that are irrigated. Therefore, if food production is under stress due to some reason that does not affect water availability (such as problems with fertilizer access/imports), then farms could increase their irrigation (or more area might be converted to irrigated farmlands) to compensate for the food losses. This would then however benefit the armyworm who prefers irrigation and might spread further than it would have previously, causing a lot of extra damage. This argument assumes that irrigation is currently at non-optimal levels for yield maximization, which I’m not sure is true.


### Aggregate risks

What are some ways in which (independent) risks might aggregate with the risk from pests? What would happen if other catastrophes occurred simultaneously to a major pest outbreak? 

Zimbabwe was hit by droughts and an unseasonal desert locust outbreak during June-September 2020. The situation was made even worse due to the social distancing measures imposed in response to COVID-19, because food distribution at communal points became much more difficult ([Simpson et al 2021](https://www.sciencedirect.com/science/article/pii/S2590332221001792#bib31)). Lockdowns will also stop people from going to work, and this includes farmers (who are of course needed to produce food). In some other cases, a pandemic might kill or weaken enough of the agricultural workforce that food production in general becomes much more difficult. This means that a pest outbreak can go undetected until it is too late and mitigation efforts will be smaller scale than otherwise, leading to an even larger yield loss to the pest than otherwise. That in turn further weakens the disease-ridden society, creating a positive feedback loop. 

International conflict disrupts global trade networks, making pest outbreak mitigation more difficult in regions that depend on pesticide imports. It will also likely cause large migrations which, as discussed earlier, contribute to the risk of societal collapse. Looking at general food insecurity, the situation is even worse in the case of a large nuclear conflict due to the possibility of a nuclear winter which is expected to severely disrupt food production. The effect of nuclear war on pest outbreaks is very unclear, however. It is possible that the colder climate will be unfavorable to many insects and will actually lessen their harmful impact on agriculture. But this is just one possibility, much more work needs to be done to determine whether this is true or not. 

There are ways in which global or local electricity supply could be severely disrupted for extended periods, such as cyber attacks, extreme solar storms (like the [Carrington event](https://en.wikipedia.org/wiki/Carrington_Event)), or a high-altitude electromagnetic pulse ([Denkenberg et al 2021](https://eujournalfuturesresearch.springeropen.com/articles/10.1186/s40309-021-00178-z)). In such cases, it seems likely that information would spread much more slowly, including that on outbreaks of pests in neighboring regions, and again, knowledge on how to mitigate them. A large-scale electricity failure would also stall pesticide production, and disrupt food distribution networks.


### Latent risks

If societal collapse has already happened, then a widely spread dangerous pest could make recovery much harder. In such a scenario, people wouldn’t have access to the large selection of pesticides that they do now, and would have to find ways to produce food without them, and with much less knowledge on alternative pest mitigation strategies than now. 


# Conclusion

Fall armyworm is an agricultural insect pest that is already causing significant damage to global food production. The damage is expected to increase in the future, mainly because there are regions with suitable climates that FAW has not yet spread to, but will likely do so. A simple calculation tells us that 91% of the world’s maize production takes place in areas that (according to a somewhat arbitrary definition of suitable) are suitable for FAW. Given that the yield losses in maize caused by FAW are on average either 17% or 35% (depending on the method used to estimate it), we would naively expect global yield losses of 16% or 32%.

In addition to direct yield damage, FAW risk interacts with all sorts of other risks, and thereby increases the chance of societal collapse by an unknown amount. 


# Acknowledgements

Thanks to Kaarel Hänni for figuring out the details of the model and writing the code for it. He also majorly contributed to the section on species distribution models. Thanks to Carson Ezell, Gideon Futerman, Nathan Barnard, Som Bagchi, Sarah Weiler, Peter Rautenbach, Herbie Bradley, Noah Wescombe, Hugo Eberhard for insisting that I shouldn’t give up. 


# Appendices


## Appendix 1. FAW tax

Accounting for the current “pest tax level” should change our understanding of the “worst-case FAW tax” in the following ways:



1. Making the reasonable assumption that all of the current yield loss due to FAW happens in areas suitable for FAW, and also the (maybe less reasonable) assumption that the production numbers reported in the data we used were post-FAW-tax, the fraction of the world’s pre-FAW-tax maize production in areas suitable for FAW should change slightly from 91.1% to $$ 0.911 \cdot (1-0.0285)+0.0285=91.4\%. $$ So this is not a large update. If we only look at areas where FAW can establish a permanent population, then it’s less clear how the current FAW tax payments are split between those areas and the rest of the world, but a calculation like the one above shows that the update of the world maize production in the susceptible area would be from 24.7% to between and 23.9% and 26.9%.
2. Actually, the 2.85% number from Savary et al ([2019](https://rdcu.be/cVEs3)) is out of some counterfactual total yield without any pests, but the calculation above assumes that it is the loss out of the counterfactual yield without FAW alone, and also computes the % of post-other-pests-[world maize production] susceptible to FAW, not the % of counterfactual production in a world with no pests. This is somewhat tricky to calculate. My vague guess that the update from taking this difference between counterfactuals into account or from choosing a different analogous quantity to calculate is probably less than 1% for each calculation.
3. We should also understand that the 16% yield loss claimed earlier (or better, updated to take the above considerations into account) is then out of some counterfactual total maize production. So this is not the same as docking 16% from current maize production, since “some tax is already paid”. The % loss compared to current production is better approximated by $$1- \frac{1-0.161}{1-0.0285}=13.5\%.$$And similarly for other proposed numbers.


## Appendix 2. Methodology

The FAW potential distribution dataset includes the Ecoclimatic Index (EI) and Growth Index (GI) for most locations (but not all) on Earth given for grid cells of size 10-arc minutes. For our modeling we used the irrigation scenario II data (see their paper for details).

For each integer pair (longitude, latitude), if there is some point in the FAW potential distribution dataset which is suitable (meaning EI>10 or GI>10)[^11] whose coordinates round to this pair, then we consider the pair to be suitable. Next, for those integer pairs not considered suitable, if there is a point in the moth data set with EI&lt;10 and GI&lt;10 whose coordinates round to it, then we consider the pair to be unsuitable. Having done this, there are many remaining integer pairs (longitude, latitude) which have neither been marked suitable nor marked unsuitable. We can think of these as points for which suitability for FAW is unknown. Fortunately, it turns out that nearly all of these are points in the ocean, with no maize production nearby. There are a few points with some maize production nearby, but places for which these points of unknown suitability are the closest integer points contribute less than 0.002% of world maize production.

Next, we look at the maize production data set. We sum the maize production from all those locations which round to an integer (longitude, latitude) point that we have marked as suitable for FAW. This gives us an estimate of the total maize production that comes from areas threatened by FAW. Almost all points in the maize production data set round to integer points which we had marked either suitable or unsuitable earlier, indicating that the FAW data provides good coverage of areas where maize is produced. Figure below shows the small number of points in the maize data set for which suitability is unknown in red. Black areas are suitable, yellow areas unsuitable.

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXehWV0Unvw5L_KeqVdGuFSg4nPb4lCX91TAHdW-NHvfzq0SIaXrqRCgBWgkf-MHRiVPGaI1bAld7gfJ0RyfAR1fOv5wE5zLPjH5inu68D0EipgcoogVwJoW24pe9EmKAmiDHUHDGR1i6fkyTESwSe4FsQ?key=jz_Lj4q4c3TGnpbx2nJAhw)**

# Notes

[^1]:
     A super pest is a pest that has developed resistance to pesticides ([Saigo 2000](https://www.cbd.int/doc/articles/2002-/A-00478.pdf)). This is analogous to [superbugs](https://en.wikipedia.org/wiki/Antimicrobial_resistance), i.e. microbes that are resistant to antimicrobials. However, we care more generally about pests that could cause significant damage to our agricultural yields.

[^2]:
     This implies that we are assuming that the same intensity of biotic constraints (such as competition from other species) as those in the species native habitat will exist in new environments, and only climatic variables determine the spread. Although this is a gross assumption, using this model as a first step still has informational value. Read more about the basis for CLIMEX [here](https://www.hearne.software/getattachment/199e1f3e-460a-4ac8-8f7f-1eeee84110c7/Climex-v4-User-Guide.aspx).

[^3]:

    The reason for training on native regions only is this: if we are trying to train our model to predict the settled distribution of FAW, it would be be bad to try to get it to fit the current non-settled (i.e. areas where FAW is still in the process of invading) distributions. Exceptions are the parts of the invasive region in which the distribution has already become pretty settled. This is what I think Timilsena et al did when they chose Americas + “a recently invaded range in East Africa” as the training data, and eight African countries (Burkina Faso, Ghana, Madagascar, Malawi, Mozambique, Liberia, Sudan, and Zambia), Asia, and Australia as an independent validation set. I am not entirely sure though that this was their reasoning as well. 

[^4]:
     Here one could also wonder why would climate change benefit the pest more than for example its natural predators or host plants? Assuming that’s even true, one possible explanation has to do with pests generally being more adaptable to changing environments than crops that we’ve bred to succeed in a very narrow range of environments. Another factor is that FAW is highly mobile, and often reaches new environments. There it makes sense that the newly invasive species has no natural predators because there’s no reason for them to be there.

[^5]:
     One might also want to consider the effect of increased CO2 levels on plant physiology. It is predicted that higher CO2 levels will cause plants to increase their biomass, but also become less nutritious per unit of mass in terms of nitrate and phosphate content. Therefore one could also make the argument that some pests will need to eat more to compensate for the lower nutritional value. Meanwhile, this effect would compete with the effect from increased plant biomass. Once again, everything is uncertain and inconclusive.

[^6]:
     It would be good to know what the annual yield loss is in the US for example, to get an idea of how destructive it is in developed countries with a long history of dealing with this pest. This is very difficult to estimate, which is probably the reason why I have not found information on this. 

[^7]:

    Ideally, we would use lower losses in developed countries where mitigation measures are more accessible, and higher losses in developing countries, i.e. the losses found for Africa in Day et al. Since there is very little data available, we have just used a single number for all countries.

[^8]:

    This is perhaps justified if the invaded regions have a single harvest time at the end of the summer. Then it is plausible that the insect will invade during the summer and cause losses to that single harvest. Considering that the invaded regions are generally at temperate regions, this should make sense.

[^9]:

    It is true that maize is one of FAW’s primary targets. There are other reasons to focus on maize: of all crops, we have the most information on FAW’s effects on it; it is a major food source in the affected regions. 

[^10]:
     Global markets can cause food production to become more concentrated to certain regions where it is most economical; a production failure in one such region could knock out a significant fraction of global food production, potentially increasing risk compared to the case where we have global markets together with a more even distribution of production.

[^11]:
     Timilsena et al have (arbitrarily) set the cutoff between suitable and unsuitable habitats at EI = 10 (with EI>10 being suitable). Analogously for GI, where GI>10 means that an area is suitable for FAW growth, meaning that there is a possibility of temporary populations in that area.
