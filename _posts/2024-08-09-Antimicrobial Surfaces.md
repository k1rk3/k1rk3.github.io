---
layout: post
title: Antimicrobial Surfaces
date: 2024-08-09
---
# Antimicrobial surfaces for pandemic prevention 

![dalle ams.webp](/assets/dalle ams.webp) 

Antimicrobial surfaces (AMSs) are surfaces which either **kill or inhibit the growth of microbes**, including bacteria, viruses and fungi. They might be a potentially useful technology for pandemic prevention due to reducing the spread of pathogens via surfaces which otherwise would act as reservoirs of contagious particles. I have spent 8 weeks researching antimicrobial surfaces part-time (around 10 hours each week), and based on that research, I will give my opinion on how useful I think AMSs are for pandemic prevention. I’ll also discuss what kinds of AMSs exist, how to classify them and the main shortcomings of the field of AMS.

## Summary

* Antimicrobial surfaces would be useful for pandemic prevention if fomite transmission was a significant mode of transmission for pandemic-relevant pathogens. At the moment, it seems that [fomite transmission is less important](#transmission-pathways-of-those-pathogens) than direct and airborne transmission. However, I am highly uncertain of this and think that more work could be done here to find out what we know and which experiments to run. (~70% certainty)
* My understanding of what makes a [good antimicrobial surface](#what-kinds-of-ams-do-we-want) is that it should be of comparable efficacy to traditional disinfectants especially against viruses, non-toxic, easily manufactured from cheap materials, and easy to apply. (~80% certainty)
* There are many ways to [classify antimicrobial surfaces](#what-kinds-of-ams-exist-in-the-literature) but a particularly nice way is via functional strategies: biocide-leaching, contact killing, and antifouling surfaces. (~90% certainty)
* Most of the work in the field focuses on [antibacterial surfaces meant to be used in healthcare](#focus-on-hais-and-antibacterial-surfaces), either on surfaces in hospital rooms, or on medical devices. These applications are not incredibly relevant for our goal of mitigating pandemic risks. (~80% certainty)
* There is a huge [lack of real world testing](#testing-both-short-and-long-term) of antimicrobial surfaces. Almost all the evidence for their effectiveness comes from _in vitro_ small scale experiments. A few trials have been run on copper surfaces in hospitals, kindergartens and retirement homes which show either no evidence or low quality evidence for these surfaces reducing infections. Overall, I would like to see more effort going into randomised _in situ_ trials of existing surfaces rather than developing more and more newer ones. (~90% certainty)
* [Materials that have received the most attention for use in AMS](#promising-examples) include (but are not limited to) copper, silver, titanium dioxide and quaternary ammonium compounds based surfaces. The [ontology writeup](https://docs.google.com/document/d/1BI_V_fSXWI1UydqXlzF0NjQUAddOu9NDQnypSut5TR0/edit) includes many more examples and resources to learn about different kinds of AMSs.

## How could AMSs help mitigate the risk from pandemics?

### Reducing the transmission of pandemic relevant pathogens?

Given huge variation in antimicrobial surface efficacy against different kinds of pathogens, the first question we need to answer to figure out whether antimicrobial surfaces could mitigate pandemic risks is: 

#### What kinds of pathogens do we care about?

Some pathogens are more likely to cause GCBR level pandemics than others. [A report](https://centerforhealthsecurity.org/sites/default/files/2022-12/180510-pandemic-pathogens-report.pdf) from the Center for Health Security at Johns Hopkins found that there are some characteristics that are likely common among higher-pandemic-risk pathogens:

1. Efficient human-to-human transmission.
2. Having **respiratory transmission** as a major mode of transmission.
3. Being contagious prior to symptom development.
4. The human population is immunologically naive to the pathogen.
5. The absence of an effective or available countermeasure.

They also point out RNA viruses as the most likely class of microorganisms to cause a catastrophic pandemic. 

#### Which pathogens do we not care as much about in the context of catastrophic pandemics?

[The same report](https://centerforhealthsecurity.org/sites/default/files/2022-12/180510-pandemic-pathogens-report.pdf) explains why the pandemic potential of some classes of pathogens is limited. For example, antibiotics make it much less likely that a bacterial disease will cause a pandemic. According to the report, although the number of multiple-drug-resistant bacteria is growing and their spread “threatens the entire practice of modern medicine”, these pathogens are largely unable to infect healthy non-hospitalised people. Therefore, I think that a good antimicrobial surface needs to be antiviral rather than antibacterial.

In the context of surfaces, other microbes that come to mind are, for example, moulds – fungal growths that can have adverse health effects –  and diarrhoeal diseases such as cholera, dysentery, polio, and parasite infections, which are related to poor sanitation, including that of surfaces in living areas. Although diarrhoeal diseases are horrible (around [500,000](https://www.who.int/news-room/fact-sheets/detail/sanitation) people die from diarrhoeal disease related due to unsafe sanitation), they are unlikely to cause catastrophic pandemics because there exists a clear way of halting the spread of these diseases – better sanitation. It might still be true that AMSd have high-impact applications in those circumstances, but not since it isn’t directly pandemic relevant, I don’t discuss this here.

#### Transmission pathways of those pathogens

The next question to address is: how do these diseases spread? [Here’s](https://images.nationalgeographic.org/image/upload/v1687451842/EducationHub/files/methods-disease-transmission.pdf) a picture describing different modes of disease transmission (see also [here](https://www.nature.com/articles/s41579-021-00535-6#Sec7) for discussion on different terminologies used). These are divided into direct, indirect, and vector-borne modes of transmission. For surfaces, the relevant group is _indirect_ transmission, and specifically, **fomite transmission** – transmission via an inanimate object which is contaminated with pathogens (a _fomite_) that then pass on to a person interacting with the object. Examples include doorknobs, water fountains, shared computer keyboards, etc. But what fraction of infections even occur via fomites? If that fraction is negligible and the most dangerous pathogens turn out to mainly spread via droplets or aerosols instead then the potential usefulness of AMSs is very limited. Unfortunately, this question seems largely **[unanswered](https://www.nature.com/articles/s41579-021-00535-6#Sec7)**. Although there is evidence that surface-mediated transmission _occurs _– lots of viruses and bacteria (often even in the form of biofilms that are hard to get rid of) [survive on](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1564025/) [common](https://journals.asm.org/doi/10.1128/aem.02051-06#F2) surfaces for days, it is unclear how frequent these events are, compared to for example droplet transmission. Additionally, virus viability on surfaces [varies a lot](https://journals.asm.org/doi/10.1128/aem.02051-06#F2) between different diseases and environmental conditions. 

[This paper](https://www.nature.com/articles/s41579-021-00535-6#Sec7) gives a good overview of the evidence on the relative importance of fomite transmission. I would also like to mention a [systematic review](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7181938/) on the effect of hand washing and surface cleaning on the transmission of influenza which found limited evidence for those interventions working in randomised control trials, which seems very surprising to me. Additionally, there seems to be an [association](https://link.springer.com/article/10.1007/s11908-018-0620-2) between environmental contamination in hospitals and hospital acquired infections. 

#### What is the effect of AMSs?

The idea of antimicrobial surfaces is to **reduce fomite transmission** via reducing surface contamination with pathogens. Given the big question mark regarding the extent to which the most scary pathogens spread via fomites, it seems that the impact of AMSs could range from basically useless to sort of useful. But if we do assume that fomite transmission is significant, then my guess for the most impactful use case for AMSs is targeting high-touch surfaces within public spaces and homes. Examples of these are handrails on public transport, doorknobs, elevator buttons, probably phone screens. Unfortunately, we don’t have any direct evidence that this use case of AMSs would have a significant effect on reducing disease transmission (see also [below](#gaps-in-the-fieldknowledge)). My guess that this is the best use case stems mostly from the fact that other uses seem even more constrained in their maximal impact: targeting hospitals only reduces infections in hospitals, for example. Using AMSs in hospitals to improve contamination levels is also what a large fraction of the antimicrobial surfaces field is focused on. There, the main aim is reducing [hospital acquired infections](https://en.wikipedia.org/wiki/Hospital-acquired_infection). These interventions at least have some, although limited, [evidence](https://www.ajicjournal.org/article/S0196-6553(15)00981-5/fulltext) [showing](https://www.cambridge.org/core/journals/infection-control-and-hospital-epidemiology/article/abs/role-played-by-contaminated-surfaces-in-the-transmission-of-nosocomial-pathogens/F11A873DDEA8B75C0C79AADC78180775) [that](https://pubmed.ncbi.nlm.nih.gov/32916212/) they work. 

#### What is the counterfactual?

Let’s try to think about the counterfactual impact of installing antimicrobial surfaces. Right now, we use disinfectants and antiseptics within regular cleaning routines. We know that these reliably reduce the microbial burden on the cleaned surface, at least temporarily (otherwise they wouldn’t pass regulatory controls). We also know that in general, cleaning in [hospitals](https://www.thelancet.com/journals/laninf/article/PIIS1473-3099(07)70241-4/abstract?isEOP=true) [reduces infections](https://link.springer.com/article/10.1007/s10096-011-1250-x). However, some authors argue that there is a [lack of understanding and systematic evidence](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8582915/) for disinfectant use in hospitals. Additionally, we [don’t](https://link.springer.com/article/10.1007/s10096-011-1250-x) [really](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10464435/) have any agreed upon standards for “clean” surfaces, even hospitals [vary widely](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10464435/) in terms of their cleaning routines and how contaminated the surfaces are. We don’t really know how many pathogens must be present on a surface to reliably cause an infection (the size of the [infectious](https://www.nature.com/articles/s41579-021-00535-6) [dose](https://journals.asm.org/doi/pdf/10.1128/aem.02051-06)). 

With that caveat in mind, there are also many surfaces in our environment that _are_ _clearly_ contaminated. Some surfaces don’t get regularly cleaned at all (for example, when did you last disinfect your phone?), and some are disinfected irregularly. It is possible that if some of those surfaces were by default antimicrobial, they’d end up cleaner overall, and thus have a lower microbial burden. Some evidence for this comes from studies like [this one](https://www.ajicjournal.org/article/S0196-6553(15)00981-5/fulltext) in hospitals where copper antimicrobial surfaces are [associated with lower concentrations](https://pubmed.ncbi.nlm.nih.gov/36842712/) of pathogens on randomly sampled surfaces. However, [not many trials](https://pubmed.ncbi.nlm.nih.gov/26463723/) have been run that test AMSs in the real world.

On the other hand, installing AMS might reduce the frequency and depth of cleaning the surfaces get due to people falsely thinking that the surface will do the cleaning for them. Some authors have noted that cleaning specialists probably have [no idea](https://www.sciencedirect.com/science/article/pii/S0195670118301440) how to adapt their routines to AMSs.

Therefore, overall it’s possible that in a world with AMSs applied to various high touch surfaces, the microbial burden in our environment would go down, but it is highly unclear by how much and how this would change things on the margin, due to possible changes in cleaning routines and the fact that the long term effectiveness of most AMSs is untested. 

Additionally, our current disinfection routines involve toxic (both to humans and to the natural environment) chemicals. By developing non-toxic AMSs, this problem could be reduced. Current antiseptics also induce development of antimicrobial resistance (AMR). This is a more difficult problem for AMSs to solve because analogously to antiseptics, we would be introducing selective pressures for microbes to evolve resistance to whatever kind of AMSs we deploy. Furthermore, there are concerns that in some cases, developing resistance to an antimicrobial used in an AMS could, _at the same time,_ lead to [resistance in traditional antimicrobials](https://www.sciencedirect.com/science/article/pii/S0195670120302917)[^1].

We currently also use non-chemical strategies for disinfection, like UV and heat, but less commonly and only in specific circumstances, so I won’t discuss the interaction between those and AMSs.

### Other ideas for pandemic relevant applications of AMSs

Here is some pure speculation. What if instead of using AMSs only for reducing the transmission of diseases once they have already established themselves as present in the population, we tried to target risk areas for spillover or lab leaks? I know almost nothing about the mechanism of lab leaks, so I don’t actually know if installing AMSs in labs would change anything. For the case of zoonotic spillovers, we might want to consider installing antimicrobial surfaces in factory farms or wet markets. I don’t expect any of this to actually work, but thought I’d throw these ideas out there. 

## What kinds of AMS do we want?

### Pandemic relevant features checklist

The field of AMS is full of countless examples of super specific surfaces from different labs all over the world with no clear, unified goal. Hundreds of labs create new surfaces all the time, and finding actually promising products within the unorganised field is very difficult. However, here is my proposed checklist for deciding whether a surface has potential to be relevant for pandemic prevention:

* Effective against viruses.
    * The reported effectiveness is at least 2 log<sub>10</sub> reduction within 2 hours.
* The authors address durability and toxicity. 
* The manufacturing process is relatively simple. This is as opposed to, for example, many nanotechnological methods which are not established as large scale production methods.
* The materials used are widely available. For example, copper > gold.
* Easy application: for example, spray coatings.
* Ideally: the surface has been tested on a longer time scale (at least a few months)
* Ideally: does not leach toxic chemicals to the surroundings.

## What kinds of AMS exist in the literature?

There are a lot of articles published every year on antimicrobial surfaces. Historically, the most explored options have been copper based. [This paper](https://onlinelibrary.wiley.com/doi/abs/10.1002/admi.202100118) from 2020 took a look at which types have the most publications and patents:

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfZXZ7zizdZHvJaCD66mdv2sKf08ZBhuRu1fjKihob6ktN-3rNfkUSiWiTb4Bk60E-xktXGDAr78jEXNGInWYy65OnCHOnhczmn_bqBHYz7QGQlbtNvKN0ef82OGMFjKrgwZK-6tiGhTb8bgoQa6TTuby4?key=mv3G02Ox6UbTQSUx7HXFrQ)**

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcKAACJ2wadGGhV0XRbGWw4X1CexpT-Vq90lq6XAS6zoRWJZadCUz5twruzuOhbTlJqGEYufj0tdmY8ZekeRKWRsRRcZ0CYl32sqFFvRkkBYtYv4MtXoT-TFnjz-DZIyd28SpOm6v6uZ5SG2oa_OEcOpKo?key=mv3G02Ox6UbTQSUx7HXFrQ)**

It is clear that metal based surfaces have been consistently among the most popular. Although photo-activated compounds are popular research topics, they don’t really show up in patents. I think that “Animated Compounds” is a typo of “Aminated Compounds” like [this one](https://www.sciencedirect.com/science/article/abs/pii/S2352940722002335), [ammonium compounds](https://en.wikipedia.org/wiki/Quaternary_ammonium_cation) and [chitosan](https://en.wikipedia.org/wiki/Chitosan).

 \
Despite the size of the field, there doesn’t seem to be an accepted classification system of all the antimicrobial surfaces that exist. Many review papers only consider a subset of the field and create a categorisation of that subset but fail to capture the structure of the entire field. I believe that this makes it quite difficult for outside readers to grasp how things fit together when they encounter specific examples of surfaces, or even review papers about AMS. This is a bit similar to what it would be like if we had no ontology for diseases – we wouldn’t have an obvious way of distinguishing between communicable and non-communicable diseases, for example. Since the type of disease is strongly associated with a particular strategy for dealing with the disease, having such a typology is highly useful. It’s probably true that some types of AMSs are more suitable for particular applications, and being able to predict that seems good.

Given this, I tried to identify ways of categorising different surfaces into a useful framework. See [here](https://docs.google.com/document/d/1BI_V_fSXWI1UydqXlzF0NjQUAddOu9NDQnypSut5TR0/edit) for a comprehensive writeup of different attempted classifications and for more sources. 


### Functional Strategies

Based on the [work](https://forum.effectivealtruism.org/posts/zLxFMdZ8i3FA6SeGx/antimicrobial-surfaces-for-pandemic-prevention) [of](https://doi.org/10.1002/admi.202100118) [other](https://doi.org/10.1016/j.biomaterials.2013.07.089) [authors](https://doi.org/10.1039/B818698G) [before](https://www.journalofhospitalinfection.com/article/S0195-6701(18)30062-8/fulltext#secsectitle0025), we think that one of the more informative categorisations is one based on the _functional strategies_ of antimicrobial surfaces. A _functional strategy _refers to the specific approach or tactic employed by an antimicrobial surface to achieve its antimicrobial effect. There are three fundamental functional strategies: biocide-releasing, contact-killing, and anti-adhesive strategies[^2]. Here are quick explanations of these terms, and examples from each category:


#### Biocide-releasing surfaces

Biocide-releasing surfaces are surfaces that gradually release antimicrobial agents into the surrounding environment. (See [here](https://pubmed.ncbi.nlm.nih.gov/26463723/) and [here](https://www.journalofhospitalinfection.com/article/S0195-6701(18)30062-8/fulltext#%20) for reviews.) The antimicrobial agents can be compounds traditionally used in disinfection: chlorines, [quaternary ammonium compounds](https://en.wikipedia.org/wiki/Quaternary_ammonium_cation) and antibiotics; or alternatively, metal ions such as **copper, silver, zinc**, or less established antimicrobials like antimicrobial peptides and plant oils.

One of the main issues with biocide releasing surfaces is that they are potentially more harmful to humans and the environment than non-biocide-releasing surfaces because active ingredients are continuously entering the surroundings. A lot of engineering work has gone into figuring out ways to incorporate antimicrobials into surfaces to slow down their release and prolong the lifetime of these surfaces. One example method is [layer-by-layer (LbL) deposition](https://en.wikipedia.org/wiki/Layer_by_layer) which seems like a very expensive method. 


#### Contact-killing surfaces

Contact-killing surfaces kill microbes upon contact with the surface, without releasing antimicrobial agents into the surroundings. (See [here](https://www.sciencedirect.com/science/article/abs/pii/S0079681616300181?via%3Dihub) and [here](https://link.springer.com/article/10.1007/s10853-021-06404-0#Sec7) for reviews.) These seem better because they should theoretically have longer lifetimes due to not depleting the active ingredient, and they should also contaminate the surrounding environment less. Different ways to make a contact-killing surface include immobilising antimicrobial compounds onto the surface, mechanical action (like nanopillars that pierce bacteria), and photocatalysts that promote the production of free radicals which are harmful for pathogens. The most developed example of a contact-killing surface uses titanium dioxide (see also [below](#titanium-dioxide)) as a photocatalyst.


#### Anti-adhesive surfaces

Anti-adhesive surfaces are surfaces that prevent microbes from attaching to the surface and/or inhibit biofilm formation. (See [here](https://www.sciencedirect.com/science/article/abs/pii/S1005030221005594) and [here](https://onlinelibrary.wiley.com/doi/full/10.1111/apm.12675) for reviews.) These surfaces don’t actually kill the microbes but remain uncontaminated themselves. Different methods to achieve this include [micropatterning](https://www.sciencedirect.com/science/article/abs/pii/S1005030221005594?via%3Dihub), and being hydrophobic or hydrophilic. A commonly mentioned example of an antimicrobial surface is one inspired by the natural surface of a [lotus leaf](https://pubs.rsc.org/en/content/articlehtml/2013/ra/c3ra40497h?casa_token=sDks9XMBmi4AAAAA:XkG6X_ZcWKtKJLGUF8u-ku05CRn11-MqzYiS3dpfzl-Kwmtj5CKpYn-Y9e8uOvEKp9WIVsnlIk6rZyeJ), which has a super-hydrophobic surface, causing water droplets to roll off and take microbes with them. Anti-adhesive surfaces seem to be less common than the other two types. 


### Gaps in the field/knowledge

I (and other authors) have identified multiple gaps in the field of antimicrobial surfaces. I will discuss some here.


#### Lack of standardisation

The field is huge and lacks standardisation in many ways. To address this and other issues, the European Commission funded [AMICI](https://www.tandfonline.com/doi/full/10.1080/21655979.2017.1323593), a 4-year initiative to establish a network of stakeholders. I’m unsure how exactly their work contributed to fixing the issues but they published some useful articles.


##### Testing (both short and long term)

There is a lot of variation in how the efficacy of AMSs are tested. See [here](https://www.tandfonline.com/doi/full/10.1080/1040841X.2021.1991271?src=recsys) for an extended discussion on the different testing standards currently used and the shortcomings of all of them. The authors of that article advocate for establishing a standardised procedure where the goal is to replicate the conditions in which the surfaces would be deployed. This means, for example, field studies where the surfaces are soiled with fats and oils found on skin, and then cleaned and disinfected over a longer time period. Most papers don’t even attempt to test the long term effectiveness of their surface and just publish the results from a specific short term in vitro test. Some exceptions to this include [this](https://www.cell.com/matter/fulltext/S2590-2385(22)00475-1?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2590238522004751%3Fshowall%3Dtrue).

Ideally, we would like to see randomised control trials where an antimicrobial surface is introduced to some environments and not to others, and then measure the infection rates of people in either environment. This has essentially not been done, the closest thing we have to this are trials in hospitals where AMSs (almost always copper) are introduced to some rooms and not to others ([here](https://pubmed.ncbi.nlm.nih.gov/32916212/), [here](https://www.ajicjournal.org/article/S0196-6553(23)00081-0/fulltext)). Larger scale studies where two similar groups of people are somehow subjected to varying levels of AMSs in their environment would be very informative. These could be analogous to the [studies](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7181938/) where hand washing, mask wearing and traditional surface cleaning are tested.


##### Safety

Currently, not many papers demonstrate or even address the safety of their antimicrobial surface. It is important that the surfaces don’t leach out chemicals that are toxic to humans or the environment in high enough doses to cause harm (for example, [quaternary ammonium compounds are concerning](https://pubs.acs.org/doi/10.1021/acs.est.2c08244)). Therefore, either the surfaces need to be safe by design – not meant to leach out anything – or tested in some way to be safe. The [AMICI](https://www.tandfonline.com/doi/full/10.1080/21655979.2017.1323593) initiative also attempts to address this issue. 

For clinical applications, the issue of stability, i.e. the ability to maintain its properties over time, is also a [crucial issue](https://pubmed.ncbi.nlm.nih.gov/26463723/) and remains overlooked. 


#### Focus on HAIs and antibacterial surfaces

The majority of the research focuses on applications within hospitals, specifically hospital acquired infections. Since those are mostly bacterial infections, the majority of antimicrobial surfaces are designed to be mainly antibacterial. Therefore, there is a divide between the goal of developing pandemic relevant AMSs, and the current focus of the field. 


#### Not much focus on cheap, scalable solutions

For some reason, the cost and ease of manufacturing is rarely mentioned in papers on AMS. Perhaps this is because most of them are insanely expensive and difficult to make on a large scale, so no one wants to talk about this? Some exceptions to this are papers on metal ion based surfaces where it is often pointed out that copper is cheaper than silver, and relatively widely available. Other examples where the authors emphasise the low cost or ease of manufacturing of their product are [this one based on cellulose](https://pubs.acs.org/doi/10.1021/acsami.2c23251).


### Promising examples

Here are quick descriptions of some surfaces that have received the most attention and research attention, and seem closest to large scale applications.


#### Copper surfaces

As mentioned before, copper based surfaces are the most researched and available, and there is a decent amount of evidence that they work. Although most of the evidence is mechanistic (tests where pathogens are inoculated on a piece of the material, and their survival quantified), there is some [low-quality evidence](https://pubmed.ncbi.nlm.nih.gov/32916212/) that copper surfaces reduce HAIs, and some higher quality evidence that they [reduce the microbial burden](https://pubmed.ncbi.nlm.nih.gov/36842712/) on surfaces. According to [antimicrobialcopper.org](https://www.antimicrobialcopper.org/faq#which_microbial_pathogens_can_copper_inactivate), the EPA has registered more than 450 copper alloy surfaces with public health claims. The mechanism by which copper surfaces work is not fully known, but it probably has to do with causing oxidative stress, binding to proteins and causing their inactivation, and making cell membranes leaky. Unfortunately, this is a biocide-leaching surface, and the health effects of large amounts of copper might also be not great[^3]. With that in mind, copper seems relatively safe for humans, given that we have been using it in cookware and dishes for centuries. However, it is not [well established](https://www.nss.nhs.scot/media/2199/1_antimicrobial-copper-surfaces-v-1-0.pdf) how these surfaces should be cleaned, and if regular polishing is required. 


#### Silver surfaces and nanoparticles

Similarly to copper, silver has been used for [thousands of years](https://www.mdpi.com/2073-4360/3/1/340) as an antimicrobial agent, most often in wound dressings. Nowadays, silver nanoparticles are one of the [most widely used](https://pubmed.ncbi.nlm.nih.gov/30658305/) nanoparticles. According to a [review from 2011](https://www.mdpi.com/2073-4360/3/1/340), it is unclear how silver kills bacteria. Although metallic silver has antimicrobial properties, those are strongly enhanced if the silver is instead in nanoparticle form, resulting in very effective antimicrobial agents. Silver-based surfaces have a few serious issues, though. Firstly, bacteria have been shown to become [resistant to silver](https://academic.oup.com/femsre/article/27/2-3/341/615473). Secondly, there’s reason to think that silver ions and nanoparticles are [toxic](https://www.tandfonline.com/doi/full/10.1080/21655979.2017.1323593), but the extent of the danger is unclear. Thirdly, silver is even more expensive than copper. 

There are quite many [commercially available](https://onlinelibrary.wiley.com/doi/abs/10.1002/admi.202100118) antimicrobial surfaces that use silver, and at the same time, there is no data available on these reducing infections in real world scenarios.


#### Titanium dioxide 

Titanium dioxide (TiO<sub>2</sub>) is a photocatalyser (see [here](https://www.researchgate.net/publication/304585461_Photocatalytic_antimicrobial_coatings) for a detailed explanation on what that means). Under particular wavelengths of light, it catalyses the production of free radicals, which go on to cause oxidative stress within microbes on the surface, eventually killing them. This also is the working principle of [self cleaning glass](https://en.wikipedia.org/wiki/Self-cleaning_glass#The_use_of_titanium_dioxide_in_self-cleaning_applications). One problem with TiO<sub>2</sub> is that in order to work well in visible light, it needs other [additives, like silver](https://pubs.aip.org/aip/apm/article/9/3/031112/892367/Fight-against-COVID-19-The-case-of-antiviral). The effectiveness of titanium dioxide based surfaces is very high, up to[ 6 log10 in 30 minutes](https://pure.ulster.ac.uk/en/publications/cu-doped-tio2-visible-light-assisted-photocatalytic-antimicrobial) for a copper-doped titanium surface. Others also see potential in this technology – the EU has given almost[ € 5 million](https://cordis.europa.eu/project/id/101058422) to a project developing antimicrobial coatings using TiO<sub>2</sub> nanoparticles.

and all the combos that it’s been put in. (there’s a million, check out the ISS review for example).


## Current state of real world AMS examples


### Regulations

Overall, there aren’t many rules for what counts as an antimicrobial surface. Here’s a list of the regulations and standards that do exist:



* In order to get EPA-approval for a **public health claim for a copper antimicrobial surface**, laboratory tests must have proven copper's ability to inactivate, **within 2 hours of contact time, more than[ 99.9%](https://www.epa.gov/sites/default/files/2016-02/documents/copper_and_copper-alloy_surface_protocol_revised_012916.pdf) (3+ log<sub>10</sub> reduction)** of the following disease-causing bacteria: Staphylococcus aureus, Enterobacter aerogenes, Escherichia coli O157:H7 (E. coli O157:H7), Pseudomonas aeruginosa, Vancomycin-resistant Enterococcus faecalis (VRE) and methicillin-resistant Staphylococcus aureus (MRSA). 
* EN 14561 is a European standard test method that evaluates the bactericidal activity of chemical disinfectants and antiseptics used to disinfect instruments in medical settings. The requirement for passing the test is a** 5+ log<sub>10</sub> reduction in an hour**.
* “Biocide-releasing surfaces are subjected to the Biocidal Products Regulation (BPR, Regulation (EU) 528/2012) and by the Regulation (EC) No. 1907/2006 of the European Parliament and of the Council on the Registration, Evaluation, Authorization and Restriction of Chemicals (REACH). This regulatory barrier makes it very expensive and time-consuming to bring antimicrobial coatings, of which the antimicrobial activity is related to biocidal release, to the market” from [here](https://www.journalofhospitalinfection.com/article/S0195-6701(18)30062-8/fulltext#%20).
* [ISO 22196:2011](https://www.iso.org/standard/54431.html) specifies a method of evaluating the antibacterial activity of antibacterial-treated plastics, and other non-porous surfaces of products (including intermediate products).


### Clinical trials and real world experiments

The extent to which AMSs have been tested in clinical trials, or even experiments replicating real world conditions, is very limited. Copper based surfaces are the most tested, having been installed in hospitals, and the effects of that measured in many ways, see [here](https://www.nss.nhs.scot/media/2199/1_antimicrobial-copper-surfaces-v-1-0.pdf) and [here](https://pubmed.ncbi.nlm.nih.gov/29605564/) for systematic reviews. I have not found much on clinical trials of other types of surfaces. 


### Challenges

There are some fundamental challenges that make antimicrobial surfaces difficult to establish. 



1. Although often AMSs are described as a solution to antimicrobial resistance, it is not a given that they don’t themselves induce AMR. Firstly, microbes will be subjected to evolutionary pressure to become resistant to the active agent in the surface. We know that microbes are capable of evolving [resistance to metals](https://doi.org/10.1038/nrmicro3028), and, for example, silver-resistant genes are common in bacteria in [Swedish healthcare facilities](https://www.sciencedirect.com/science/article/pii/S0195670117302311). There is reason to believe that the resistance development will be exacerbated if the surface continuously leaches small doses of antimicrobial agents into the surroundings, leaving the more resistant pathogens alive. Even worse, in some cases, resistance to the AMS [might induce resistance](https://www.sciencedirect.com/science/article/pii/S0195670120302917) to other antimicrobials as well. 
2. No building material that we widely use is particularly antimicrobial. And no antimicrobial surface is particularly cheap or widely used already. Copper is often mentioned as affordable, but even then, with a price of [~$10 per kilogram](https://www.marketindex.com.au/copper), it is more expensive than stainless steel [($2-3 per kg](https://businessanalytiq.com/procurementanalytics/index/stainless-steel-price-index/)) and aluminium ([$2.5 per kg](https://www.marketindex.com.au/commodities/aluminium)) – the materials it would most likely be replacing. I would also guess that some plastics-based surfaces would be cheaper to produce. Almost all other AMSs are made from even less common materials.
3. It is unclear how cleaning routines should be adapted to AMSs. Cleaning staff would probably have to be retrained once we have even figured out how to clean AMSs. 
4. The effectiveness of surfaces [varies](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6481088/) under different environmental conditions, like temperature, humidity, pH. This means that testing probably has to include different plausible scenarios in terms of environment variables.


### Good things



1. There is a lot of work going into antimicrobial surfaces. Even though a very small fraction of that work is focused on solving the same problems as we are, the sheer size of the field does still mean that there are corners in which very relevant work is being done. For example, the EU’s Horizon Europe Programme is currently (or has been recently) funding at least 8 projects on developing effective and safe AMSs to reduce disease transmission ([1](https://stop-pathogens.eu/), [2](https://eu-nova.eu/), [3](https://www.supreme-project.eu/), [4](https://reliance-he.eu/), [5](https://susaan-project.com/project/), [6](https://www.miriaproject.eu/), [7](https://nanobloc.eu/), [8](https://www.triple-a-coat.org/)).

## Appendix

### Commercially available examples

The most comprehensive list that I have been able to find comes from a paper on the applications of [AMSs on the international space station](https://doi.org/10.1002/admi.202100118). These are mostly based on silver and quaternary ammonium compounds. Here is a list of other ones we’ve found that aren’t mentioned in the ISS paper:

* Antimicrobial additives for polymers: [https://www.biocote.com/](https://www.biocote.com/) 
* [https://vitracoat.com/products/vitraguard-antimicrobial-coatings/](https://vitracoat.com/products/vitraguard-antimicrobial-coatings/) 
* [https://powdertechnology.com/antimicrobial](https://powdertechnology.com/antimicrobial) 
* [https://www.fisherbarton.com/industries/medical/](https://www.fisherbarton.com/industries/medical/) 
* [https://www.lekem.com/](https://www.lekem.com/) 
* [https://www.preventive-hygiene.com/](https://www.preventive-hygiene.com/)


## Notes

[^1]:
      For example, by reducing the uptake of metal ions, the microbes [also reduce the uptake of antibiotics](https://doi.org/10.1016/j.tim.2006.02.006) if both of those processes occur via the same pathway).

[^2]:
     Some surfaces use more than one of these strategies, and there probably exist examples that don’t clearly fit into these groups, but overall this is a pretty comprehensive classification.

[^3]:
     I have not looked into this at the time of posting.











