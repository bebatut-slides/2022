<!-- .slide: data-background="images/title.jpg" data-state="dim-background" -->
## Accessible and scalable detection and identification of foodborne pathogens

<br>

Bérénice Batut

<small>University of Freiburg, Germany <br> She/her - <i class="fab fa-twitter"></i> <i class="fab fa-github"></i> [@bebatut](twitter.com/bebatut) - <i class="fas fa-envelope"></i> berenice.batut@gmail.com</small>

<br>

<small>EOSC-Life 3rd AGM - March 2022</small>


<small style="position: absolute; right: 0%; font-size: 0.2em; bottom: -20%;">Photo by [Elena Mozhvilo](https://unsplash.com/@miracleday?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) </small>


Note:
- First of all, I would like to thank the organizers and the committee for giving me the opportunity to give the talk here

---
### Foodborne pathogen contaminations

<div style="text-align: left; float: left; width:45%;" data-markdown>

A major burden on our society
(~ 600M people / year)

**Investigation of a foodborne outbreak**:
Microbiological analysis of the probable responsible food

Goals
- Detect the responsible pathogens
- Track the contamination source

</div>

<div class="right_column" style="width:45%;" >

![Past, present, and potential future workflows of pathogen detection by WGS and traditional subtyping techniques. Although times are approximate and vary according to the pathogen being analyzed, in all instances, WGS offers substantial time savings in comparison to traditional techniques. Future techniques using culture-independent metagenomic and high-throughput RNA sequencing technologies have the potential to offer faster detection times. SNV, SNP variation.](images/ronholm2016.jpeg) <!-- .element width="100%" -->

<small>Ronholm et al, 2016</small>
</div>

---
### Biolytix pipelines

---
### Migration to a modern and open paradigm


---
### FAIRness for all resources

- Data
- Workflows
- Training material

---
### Impact of the project

**Accessible resources** to detect foodborne pathogens via direct metagenomics Nanopore sequencing **for everyone**

1. **Open** and **modern** pipelines
    1. Open source tools
    2. Bioconda packages and BioContainers
    3. Workflows
        - Available via Galaxy (web interface and also API)
        - Annotated and shared on WorkflowHub
        - Automatically tested using LifeMonitor
        - Easily **adaptable**
    4. **Documentation** in the form of online tutorials on the Galaxy Training Network
2. ~30TB of **public FAIR** data with extended metadata to **test** new and updated pipelines


Foodborne pathogens and their impact on human health are a major problem in the food industry. Advanced detection and tracing beyond classical methods would have a tremendous impact in  large and small scale food production. The identification of the exact pathogenic strains and their genomic information in the food without isolation would lead to a new level of food security. The source of food contaminants could be faster identified and avoid outbreaks of foodborne illnesses. Future outbreaks of foodborne pathogens with all its hassles could be reduced.

---
### Expected value

With this particular project, ALU-FR will have a concrete use case to develop and document the process of using Galaxy to modernize and FAIRify existing workflows. The available workflows will be useful to support the growing microbial and public health Galaxy groups in which ALU-FR is highly involved. The data, workflows and training generated within this project could also be directly used in the Street Science project, organized by ALU-FR, which organizes workshops in schools. Moreover, ALU-FR will gain a deep insight in foodborne pathogen identification and characterization, food analysis, and their current limits. This project will help make connections with existing projects like IRIDA and open the door to new developments and projects on subjects like GMO detection, allergen detection, food microbiology or any outbreak surveillance and tracking.

Biolytix is currently lacking deep knowledge about leveraging bioinformatic pipelines to make them sustainable, cloud-native and scalable. In collaboration with the ALU-FR, Biolytix will learn how to develop and to maintain such a workflow over the years and use the European Cloud for their use-cases in order to implement better data and compute practices in the company.

The envisaged project would be the first open pipeline for food analysis using public open infrastructures to our knowledge. It would be an example for development of the further needed workflows for food fraud that could follow.
