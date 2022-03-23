<!-- .slide: data-background="images/index.jpg" data-state="dim-background" -->
## Accessible and scalable detection and identification of foodborne pathogens

<br>

Bérénice Batut

<small>University of Freiburg, Germany <br> She/her - <i class="fab fa-twitter"></i> <i class="fab fa-github"></i> [@bebatut](twitter.com/bebatut) - <i class="fas fa-envelope"></i> berenice.batut@gmail.com</small>

<br>

<small>EOSC-Life 3rd AGM - March 2022</small>


<small style="position: absolute; right: 0%; font-size: 0.2em; bottom: -20%;">Photo by [Monstera](https://www.pexels.com/@gabby-k?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels) from [Pexels](https://www.pexels.com/photo/cutout-paper-composition-of-bacteria-on-green-background-5841807/?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels)</small>


Note:
- First of all, I would like to thank the organizers and the committee for giving me the opportunity to give the talk here

---
### Foodborne outbreak

"*An incident in which two or more people develop the same disease or infection following the consumption of a common contaminated food*"

![](images/efsa_foodborne_outbreak.png) <!-- .element width="40%" -->

<small>[EFSA, 2021. Story map on foodborne outbreaks](https://multimedia.efsa.europa.eu/fbo-storymaps/index.html)</small>

Note:

A major burden on our society
(~ 600M people / year)

----
### Which causative agents?

![](images/efsa_outbreak_causative_agents.png) <!-- .element width="80%" -->

<small>[EFSA, 2019. Foodborne outbreaks - dashboard](https://www.efsa.europa.eu/en/microstrategy/FBO-dashboard)</small>

----
### Where food contamination may occur?

![](images/efsa_outbreak_cause.png) <!-- .element width="80%" -->

<small>[EFSA, 2019. Foodborne outbreaks - dashboard](https://www.efsa.europa.eu/en/microstrategy/FBO-dashboard)</small>

----
### Investigation of a foodborne outbreak

<div style="text-align: left; float: left; width:45%;" data-markdown>
Microbiological analysis of the probable responsible food at different point

**Goals**
- Detect the responsible pathogens
- Track the contamination source

</div>

<div class="right_column" style="width:45%;" >

![Past, present, and potential future workflows of pathogen detection by WGS and traditional subtyping techniques. Although times are approximate and vary according to the pathogen being analyzed, in all instances, WGS offers substantial time savings in comparison to traditional techniques. Future techniques using culture-independent metagenomic and high-throughput RNA sequencing technologies have the potential to offer faster detection times. SNV, SNP variation.](images/ronholm2016.jpeg) <!-- .element width="100%" -->

<small>Ronholm et al, 2016</small>
</div>

---
### Toward accessible and scalable detection and identification of foodborne pathogens

Funded by [EOSC-Life Digital Life Science Call for academia-industry collaborations](https://www.eosc-life.eu/industrycall/)

![](images/team.png) <!-- .element width="80%" -->

---
### Investigation of foodborne pathogen by Biolytix

![](images/overview_1.png) <!-- .element width="100%" -->

----
### Investigation of foodborne pathogen by Biolytix

![](images/overview_2.png) <!-- .element width="100%" -->

---
### Migration to a modern and open paradigm

![](images/overview_3.png) <!-- .element width="100%" -->

---
### Expected outcome

![](images/biolytix.png) <!-- .element width="30%" -->

- Knowledge to make bioinformatic pipelines
    - **FAIR**<!-- .element style="color:#1f8787" -->
    - sustainable
    - scalable
    - open
- Implementation of **better data and compute practices**<!-- .element style="color:#1f8787" -->

----
### Expected outcome

![](images/freiburg_galaxy.png) <!-- .element width="20%" -->

- Concrete use case to develop and **document**<!-- .element style="color:#1f8787" --> the process of using Galaxy to modernize and **FAIR**<!-- .element style="color:#1f8787" -->ify existing workflow
- Data, workflows and training **resources**<!-- .element style="color:#1f8787" -->
   - for the growing microbial and public health Galaxy communities
   - for **outreach**<!-- .element style="color:#1f8787" --> via the [Street Science community](https://streetscience.community/)
- Deep insight in foodborne pathogen identification and tracking

----
### Expected outcome for the community

**Accessible resources to detect foodborne pathogens via<br> direct food Nanopore sequencing**<!-- .element style="color:#1f8787" -->

1. **Direct and faster**<!-- .element style="color:#1f8787" --> detection and tracing methods

Note:
Foodborne pathogens and their impact on human health are a major problem in the food industry. Advanced detection and tracing beyond classical methods would have a tremendous impact in  large and small scale food production. The identification of the exact pathogenic strains and their genomic information in the food without isolation would lead to a new level of food security. The source of food contaminants could be faster identified and avoid outbreaks of foodborne illnesses. Future outbreaks of foodborne pathogens with all its hassles could be reduced.

----
### Expected outcome for the community

**Accessible resources to detect foodborne pathogens via<br> direct food Nanopore sequencing**<!-- .element style="color:#1f8787" -->

1. **Direct and faster**<!-- .element style="color:#1f8787" --> detection and tracing methods
1. 1st **open**<!-- .element style="color:#1f8787" --> pipeline for food analysis using public open and **modern**<!-- .element style="color:#1f8787" --> infrastructures
    1. Open source and state-of-the-art tools
    2. Bioconda packages and BioContainers for dependencies
    3. **FAIR**<!-- .element style="color:#1f8787" --> and easily **adaptable**<!-- .element style="color:#1f8787" --> Galaxy workflows
        - Available via on [Galaxy Europe](https://usegalaxy.eu/)
        - Annotated and shared on WorkflowHub
        - Automatically tested using LifeMonitor
    4. **Documentation**<!-- .element style="color:#1f8787" --> in the form of online [GTN](https://training.galaxyproject.org/) tutorials


----
### Expected outcome for the community

**Accessible resources to detect foodborne pathogens via<br> direct food Nanopore sequencing**<!-- .element style="color:#1f8787" -->

1. **Direct and faster**<!-- .element style="color:#1f8787" --> detection and tracing methods
1. 1st **open**<!-- .element style="color:#1f8787" --> pipeline for food analysis using public open and **modern**<!-- .element style="color:#1f8787" --> infrastructures
    1. Open source and state-of-the-art tools
    2. Bioconda packages and BioContainers for dependencies
    3. **FAIR**<!-- .element style="color:#1f8787" --> and easily **adaptable**<!-- .element style="color:#1f8787" --> Galaxy workflows
        - Available via on [Galaxy Europe](https://usegalaxy.eu/)
        - Annotated and shared on WorkflowHub
        - Automatically tested using LifeMonitor
    4. **Documentation**<!-- .element style="color:#1f8787" --> in the form of online [GTN](https://training.galaxyproject.org/) tutorials
2. ~30TB of **public FAIR**<!-- .element style="color:#1f8787" --> data to **test**<!-- .element style="color:#1f8787" --> similar pipelines

---
### Thank You!

![](images/eosclogo.png) <!-- .element width="40%" -->

---
### Accessible and scalable detection and identification of foodborne pathogens

![](images/overview_3.png) <!-- .element width="80%" -->
