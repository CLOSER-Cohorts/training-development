## Archived information for each unit
---

## Unit 1.0

>[!NOTE]
>Need to review case study example. Should we just have independent examples in each unit OR do something like below where there is a narrative and we use the same fictional example to base the practice activities on?

**Case study example**

Congratulations! You’re the newest member of a longitudinal research team at University College London.

The research is funded by UK Department for Young people and the Economic and Social Research Council. The research is looking into the impacts of social media on young people in England.

They have already completed two waves of data collection, collecting data from 437 participants aged 11-16 years old using questionnaires. Wave 1 was completed in 2021 and Wave 2 was completed in 2023. 

You will conduct the next wave of data collection in two months time. 

---

## Unit 1.1

---

## Unit 1.2

To be added back in when we go through with train the trainer materials.

:mortar_board: Trainer: give 5-10 minutes for people to discuss what common examples of bad data management is before moving on. Invite people to share their ideas with the group.

:mortar_board: Trainer: give 5-10 minutes for people to discuss what data management is before revealing the definition. Invite people to share their ideas with the group.

<details>
<summary><b>Who is impacted by poor research data management?</b></summary>
<p></p>

Poor research data management impacts both the data owner and other researchers trying to find and understand their data. 

<b>Data owners</b>


If you don’t keep track of your data properly, it’s easy to forget what you collected and why. Later on, you might waste time trying to re-oragnise data or lose parts of it altogether. Poorly managed data is especially risky if your data is sensitive and needs to be kept secure. Poorly managed data is also harder for others to find, understand, and trust. That means fewer people will use or cite your work, which can limit its impact. In the long run, this could affect your chances of getting future funding or support.

<b>Other researchers</b>


If a research project isn’t well managed, other people will struggle to understand the data or figure out if it’s useful for their own work. Missing information and unclear research processes make the data harder to trust and use. As a result, valuable data might be overlooked, and researchers could end up repeating work that’s already been done as they can't find existing data or make sense of it.

<b>Research as a whole</b>


If research data is managed well, a single dataset can be used by mutliple researchers to support a variety of research purposes. This saves time and resources in collecting data. However, if research data is poorly managed, data can't be easily re-used, meaning more time and money will be spent creating similar datasets. 

</details>

---

## Unit 1.3

>[!NOTE]
>**BO - do we want to say "as researchers", if the audience also includes data managers and funders? We could say "What can we do to enact these principles?" and have some examples for researchers and others for data managers? Or if they're the same there's no need to specify** <P></p>
> :large_blue_diamond: KR Great point re different audiences. When referring to 'other researchers' finding data, should I generalise that to 'other people' so to capture that it might be researchers, funders, policy makers etc.

## FAIR Data assessment list

If you have a dataset, use the [ARDS online FAIR dataset assessment tool](https://ardc.edu.au/resource/fair-data-self-assessment-tool/) to determine how FAIR your data is.

>[!NOTE]
>**Should this activity come later as it references/asks questions about a person's metadata level? Or could do the test now and ask participants to do it again after the course?**
>**BO - I think later to have a better understanding of the questions.**

::: notes 
[FAIRAire](https://www.openaire.eu/how-to-make-your-data-fair) -- has checklist
Jones, S. & Grootveld, M. (2017, November). How FAIR are your data? Zenodo. http://doi.org/10.5281/zenodo.1065991

:::

## Old content

- Helps demonstrate the impact of research when people re-use and cite your dataset, so you get credit for all your outputs
- Scientific journals and funders now require scientists to share data
- Increases your visibility as a researcher
- Improves the quality of your data and accuracy of your research results
- Provides proof of transparent and valid conduct
- Improves our confidence in data and research

## FAIR unit summary

- **F**indable, **A**ccessible, **I**nteroperable, **R**e-usable
- Aims to optimise and make reuse of data easier
- Infrastructures are best placed to implement FAIR for the benefit of users
- Data producers and users need to contribute to create FAIR data

>[!NOTE]
>**BO - Do we say the second point before the summary? If not we should, as the summary should include key points from the previous content.**

---

## Unit 2.1

>[!NOTE]
> BO - Similar to a comment on another unit, we'll want to go through the ILOs in all the units and make sure they're in the same format i.e. Understand..., Be able to explain..., Be able to identify... etc. Here we need to add something before "...Benefits of creating and using metadata" and "...Metadata's role in FAIR".


>[!NOTE]
> KR Followed definition that structure of the metadata = element and the content = field <br>
> KR to update with CoData RDM terminology once complete
> BO - Yes, but we could maybe use more plain language instead of or alongisde this. The way I think about metadata elements is that they're the type of metadata, it's like a label for the metadata. We can see this clearly in the Discovery screenshot and your examples in your definition. The way I think about metadata fields is what you've written - it's a space to input the content. Could we add an example to metadata fields, like you've done for elements? You could say something like e.g. only numeric values may be permitted. <br>
> :large_blue_diamond: KR Updated, does this read better?

As well as external factors, metadata is helpful for your future self, to help you understand your data later down the line, and be able to share it in a meaningful way with others.

If we didn't have data level metadata and only had high level metadata, we would have to guess about what the dataset contains or contact someone for further details. We may then access the data and find that 

Equally, if we only had data level metadata, we wouldn't know important information about who produced the data, when it was produced and where. 

**Defining metadata terms**
You may have come across metadata before, or this may be your first time. As such, you might be coming across new terms or revisiting knowledge of metadata concepts.

**Old Table**

|          | N662   | N545  | N1171  | N2REGION | N1112  | N1261 |
|----------|--------|-------|--------|----------|--------|-------
|          | N662   | N545  | N1171  | N2REGION | N1112  | N1261 |
| 1        | 2      |  4    | 6      | -2       | 1      | 1            
| 2        | 1      |  4    | -1     | 1        | 1      | 1        
| 3        | 1      |  4    |  4     | 10       | 1      | 1 
| 4        | 1      |  4    |  4     | 4        | 1      | 1  


**Benefits of strucutre and machine-actionability**

 -  For metadata to be machine readable, it must be structured according to a specific set of rules
    - Standardises the content and structure of documentation, making it easier for computers to extract information from the metadata
    - Tells a computer what something is, how it relates to other things (“objects”), and what to do with it

- Makes data management for researchers easier and more efficient, saving time and imrpvoing accuracy
    - Allows researchers to quickly discover, understand and access data
    - Helps your future self to understand your past research, preserving your data for continued use

- Organise our metadata into useful collections of information. For example, in the previous example, groups of metadata were organised into tabs: Sweep description, Coverage, Funding, Kind of Data, Dataset and Questionnaires.

- Store our data in data repositories
  
- Search data repositories/archives
  [screenshot of filters in a repository]
  
- Compare studies

**Metadata and FAIR [Written out]**

FINDABLE makes it easier to discover and understand data.
- F1. (Meta)data are assigned a globally unique and eternally persistent identifier.
- F2. Data are described with rich metadata.
- F3. Metadata clearly and explicitly include the identifier of the data they describe
- F4. (Meta)data are registered or indexed in a searchable resource.

ACCESSIBLE makes it easier to understand how to access the data. 
- A1. (Meta)data are retrievable by their identifier using a standardised communications protocol (open, free, universally implementable, allows for an authentication and authorisation procedure where necessary)
- A2. Metadata are accessible, even when the data are no longer available
- _Note: data does not need to be open but metadata should be accessible._

INTEROPERABLE allows you to combine datasets for further research.
- I1. (Meta)data use a formal, accessible, shared, and broadly applicable language for knowledge representation.
- I2. (Meta)data use vocabularies that follow FAIR principles.
- I3. (Meta)data include qualified references to other (meta)data.

RE-USABLE enables re-use of your own data and re-use for others.
- R1. (Meta)data are richly described with a plurality of accurate and relevant attributes
    - (Meta)data are released with a clear and accessible data usage license.
    - (Meta)data are associated with their provenance.
    - (Meta)data meet domain-relevant community standards.
  

::: notes
https://www.go-fair.org/fair-principles 
:::


**Snippets from other trainings**

Below are snippets from other trainings that may be useful to include here. For now they are not included in the main structure in order to avoid repetition.

Benefits of metadata for you as a researcher:
- Increases research efficiency
- Maximises potential of your data, leading to secondary research, data citations and cross study comparison
- Improves data quality and FAIRness

**Finding information about research projects**

Where would you find the answers to these questions? Where would you look? Who would you contact?

**Finding information about research projects**

You may find the information online on sites like data repositories or data catalogues (more information about data respositories and catalogues in unit 2.4). For example:

**Screenshot 

**Summary**

- Metadata is information that describes data
- Metadata is based on a structure that can be processed by a computer 
- Metadata is important for your future self and others to discover, understand and (re)use data
- Metadata allows researchers to use data effectively because it includes the important information needed to exploit the full potential of data


For example, the two tables below could both be labelled as health data in children conducted in 1969 across England, Scotland and Wales. However, they contain different data. If we don't have metadata to describe what the dataset contains, we'll have to go through a lengthier process of accessing the data files in order to assess whether they're relevant for us.

|          | Age    | Gender| Weight | Height    | BMI  
|----------|--------|-------|--------|-----------|------
| 1        | 2      |  4    | 6      | -2        | 1                  
| 2        | 1      |  4    | -1     | 1         | 1              
| 3        | 1      |  4    |  4     | 10        | 1      
| 4        | 1      |  4    |  4     | 4         | 1      
| 5        | 1      |  4    |  4     | 4         | 1      


|          | Age    | Gender | Visual impairment | Hearing impairment | Use of accessibility equipment
|----------|--------|--------|-------------------|--------------------|---------------------------
| 1        | 2      |  4     | 6                 | -2                 | 1          
| 2        | 1      |  4     | -1                | 1                  | 3         
| 3        | 1      |  4     |  4                | 10                 | 1     
| 4        | 1      |  4     |  4                | 4                  | 2      
| 5        | 1      |  4     |  4                | 4                  | 2      


- **Who** collected the data? 
- **What** data did they collect? 
- **When** was the data collected? 
- **Where** was the data collected? 
- **Why** was the data collected? 
- **How** was the data collected?

Depending on how you engage with research, you may be _using_ metadata or _creating_ metadata. Often if you're conducting research yourself, you'll be doing both. 

By being structured, metadata organises our documentation into useful collections of information. In the previous example, groups of metadata were organised into tabs: Sweep description, Coverage, Funding, Kind of Data, Dataset and Questionnaires. This helps both other people and our future selves to understand our resource or research, preserving it for continued use and improving resource management.

A **metadata field** is the input area for a metadata element.
-
Sometimes there are rules that dictate what values are allowed in a metadata field in order to make sure metadata is clean.
  - e.g. for the 'Date' metadata field, there may be a specification to format the information as dd/mm/yyyy


We can also store our resources on centralised platforms alongside other resources. These centralised platforms can read a resource's metadata and allow people to search and filter a huge range of resources. 

In research, these platforms could be data repositories, data catalogues or data archives (more information about these plaforms in unit 2.4 Using metadata). This helps us to quickly discover, understand, access and compare different resources. As we use computers to do this, we save time and improve the accuracy of resource management.


FAIR AWARE tool The FAIR Aware Tools consists of 10 questions that will take between 10-30 minutes to complete. Using the answers you provide, the tool assess your awareness level, as well as providing tailored tips relevant to your role on how you can further improve your FAIR skills.

The tool is designed for researchers, policy makers, funders, publishers and research support personnel (e.g. data stewards, curators, data managers, librarians).


## In short ...

Metadata allows you to realise the full potential of your data, increasing its value and making it go further.

Metadata is ...
- Information that describes data which can provide a roadmap of your data
- Based on a structure that can be read and actioned by a computer 
- A note for your future self
- A tool to help others discover, understand and (re)use your data
- A tool for collaboration with others
- A hallmark of data management best practice and transparency
- Information that helps us maximise the full potential of data


---

## Unit 2.2

>[!NOTE]
> KR I feel the tone in this unit talks more to metadata creators (master students, researchers and data managers). For example, I use 'you should ...' or 'your data .../your research ...' etc. <p></p>
> Should I generalise it so it speaks also to funders and people who will not be directly involved in the metadata creation process? <p></p>
> BO - I quite like using phrases like your data/your research etc, as I think it fits in with the more personal/colloquial tone. I think the main audience will be individuals wanting to learn more about metadata, so I think it's fine.


**Metadata terms**

You may have come across metadata before, or this may be your first time. As such, you might be coming across new terms or revisiting knowledge of metadata concepts.

As an evolving field, terminology around metadata can vary depending on the source you are using. The same term can be used or interpreted by people to mean slightly different things. 

In this module we will define different metadata concepts and terms as we go along. Outside of this module, using a glossary or terminiology bank can be a useful way to identify a single source of truth so you can be consistent in your metadata processes.
  
For example, you could use [CoData RDM Terminiology bank](https://codata.org/initiatives/data-science-and-stewardship/rdm-terminology-wg/). Alternatively, there might be key organisations in your discipline who provide similar resrouces.

>[!NOTE]
> Should we/can we include other metadata glossaries/terminology? **BO - depends how consistent they are with one another, it might create confusion if different gloassaries are conflicting but if they're complementary it might be ok. But it might be more helpful and less confusing to have one thing we constantly refer back to** <p></p>
>Should this be moved to the very top of the training to cover all concepts, not just metadata concepts? OR should this be moved to unit 1.1?

>[!NOTE]
> BO - maybe in the previous module when we're defining metadata we could tie this in. We could say that there are lots of different definitions and understandings of metadata and its associated terminology, and that in the next module (i.e. this one) we'll spend time unpacking and making sense of the terminology. But I might get to the end of this course and change my mind!
> :large_blue_diamond: Agree **KR TO MOVE TO PREVIOUS MODULE**

**Metadata and data**
> ARCHIVING 2 SENTENCES: Most obviously, metadata applies to data which has been collected for a specific purpose. Less obviously, it also applies to data such as text, images or sound which is processed into ‘numbers’ for statistical analysis

>[!NOTE]
> JJ &rarr; KR
>What do you mean by project level - give examples. Higher level aggregated information of the project. Explain the purpose of having these levels of metadata <br>
> Expand on: if you just have the project level information / only have item level / only have project level - what information would you be missing? <br>
> Explain that you need a collection of different levels of information <br>
> Include how provenance is important throughout all metadata levels <br>

>[!NOTE]
> KR question: Would you call it Item level metadata or data level metadata? <br>
> Should be it be study/project? What is difference between study or project? <br>

**Metadata as a search tool**

Metadata are also leveraged in search and filter tools to help users discover research data.

>[!NOTE]
> BO - leveraged as or leveraged in? I think it's in (but could be wrong!).

**Variable search tool**

UK Data Service Variable and Question Bank. 

<img src="img/UKDS_qvbank.png" alt="Alt Text" width="700" height="320">

CLOSER Variable search 

<img src="img/CL_searchpage.png" alt="Alt Text" width="700" height="320">

**Keyword search tool**

CESSDA Data Cataologue search 

<img src="img/CESSDA_seachpage.png" alt="Alt Text" width="700" height="320">

>[!NOTE]
>Add
>Example: UK LAC - Linkeage data - having information at the wrong level - consent around data sharing wasn't documented at correct level

Knowing what different levels and types of metadata you can create can help you organise your metadata and check that you have captured necessary information to describe your data thoroughly.

**Where you find metadata in reseach settings**

Outside of the metadata you create for your own research, you will most commonly come across metadata in data catalogues and data repositories.

For example:

- Project level:_[add screenshot example]_
- Dataset level:_[add screenshot example]_
- Item level:_[add screenshot example]_

THINK ABOUT WHERE TO PLACE THIS

**Where is metadata used in research settings?**

Registry - single source of information (not interchange) - FAIRSharing (registry of places that share data in a FAIR way)

Catalogue if you have a catalogue that uses a standard, you can aggregate metadata to a central place. However, catalogues do not always specify standards.

Repository - a way of maintaining the provenance and evolution of the metadata - has information around versioning. 

The level of metadata created also depends on where the data will be deposited e.g. some data registries or catalogues may only require you to briefly describe your sample and the types of data collected - we can say repos will be covered in more detail later.

>[!NOTE]
> Is it helpful to make this distinction here?
> How can we describe the differences?
> Venn diagram between these tools
> BO - I like the idea of a diagram. I think we should define provenance here as I don't think we've mentioned it yet and it's quite jargon-y. We need a transitioning sentence at the start of this or at the end of the previous section. Maybe related to my comment above about what you create depends on where it's going to end up?

However, as a research project is described in more detail, the type of data the project collected will inform what metadata can be captured.

- Increased workload
- Time consuming and resource heavy
- Limited usability
- Not relevant for your data

(which includes the [Age 7 Survey (1965)](https://discovery.closer.ac.uk/item/uk.cls.ncds/0103e4b4-09a6-41a8-997b-3ca0b1edcafc) we looked at in unit 2.1

---

## Unit 2.3

Look at two sets of metadata for the same example dataset.

Which one has caputres provenance metadata?

**Example one**

| Metadata element           |  Dataset metadata                     | 
|----------------------------|---------------------------------------|
| Data collection date       | 2023                                  | 
| Data collection method     | Survey                         | 
| Data collection instrument | "Community Health Survey"      | 
| Version                    | --                                    | 
| Last updated               | 2024                                  | 
| Change log                 | --                                    | 
| Related publications       | Public Health Journal                 | 
| Repository                 | Not specified                         | 
| Storage                    | DDI                                   | 

**Example two**

| Metadata element           |  Dataset metadata                     | 
|----------------------------|---------------------------------------|
| Data collection date       | March – June 2023                     | 
| Data collection method     | Online survey                  | 
| Data collection instrument | "Community Health Survey v2.3" | 
| Version                    | Version 1.4 (edition history here)    | 
| Last updated               | 05/12/2024                            | 
| Change log                 | Category names for variable G123 updated     | 
| Related publications       | Smith, L. et al. (2020). "Urban Health Trends". Public Health Journal | 
| Repository                 | World Health Repository               | 
| Storage                    | DDI 3.3                               | 


<details>
<summary><b>Comparing example metadata</b></summary>
<p></p> 

Both datasets contain metadata elements that can capture a study's provenance. However, the lack of detail and missing information in example one makes the provenance weaker.

Comparatively in example 2, we are given more specific information for example 'March-June 2023' rather than just '2023' for the data collection date. We are also provided with version information and the date the metadata was last updated.

</details>

<details>
<summary><b>Why do you think having provenance metadata is important?</b></summary>
<p></p> 

Provenance enhances transparency, trust, credibility and reproducibility of data by providing details such as who created the data, the history of modifications and who made those changes.

</details>




---

## Unit 2.4

Discovery to understanding 

Now imagine you have used the search and filter functions to find a list of research projects that may be of interest to you.
However, when you click through to the resource you are taken straight to this.

_[Provide a screenshot of a research profile page with very little metadata]_

Or if the data is open, straight to the dataset.

_[Provide a screenshot of a dataset with no accompanying documentation]_

What challenges might arise if we only had this information to work from?
Would you choose to cite or use this dataset in your work? Why?
Would you trust these sources?

>[!NOTE]
> BO - could ask how would they find the information they needed to understand and use the data file they'd been given? It links to the point below about contacting the research producers (although this feels a bit repetitive of what we've said in prior units).


For example, if you had a look at this data catalogue page on XXX [Give link to research project profile page], what could you tell someone about the actual data it collected?

Would you be able to describe what variables are within the dataset? Or how many cases it recorded for each variable?


---

Discovery to understanding: the role of metadata

Without strong documentation on data catalogue and repository sites, we're not able to easily understand what the research project is about. We have to contact the research producers to clarify details about the research project or we decide not to use the data as we cannot be sure how it was produced or what data it's contains.

This where metadata comes in. Metadata gives us the information to explain what the research project is about, how it delivered and what it's dataset(s) descrive.

>[!NOTE]
> BO - I feel like we're going back and forth in this section, sometimes revisiting things we've already covered in previous units, especially the bit above about how metadata helps us to understand a research project/data. I think by now they should already know what the role of metadata is, and this section should focus on why and how to use catalogues and respositories, and maybe just have the case study that you've already created flowing throughout each of the sections. I'll stop reviewing this section from here and we can discuss instead. :) 

## Using Codebooks and data dictionaries

_In progress section_

Add information about:
- Where you can find codebooks/data dictionaries and how you can access them
- Give an example of a codebook/data dictionary and ask what information you can gain from them (could tie to an activity e.g. ask people to find information about a particular variable, e.g. how many missing cases)

---

## Unit 2.5

Cross-study comparison case studies:
- [The Effect of the Covid 19 Pandemic on Mental Health](https://learning.closer.ac.uk/researchcasestudies/the-effect-of-the-covid-19-pandemic-on-mental-health/)
  - Uses data from two studies:
    - Avon Longitudinal Study of Parents and Children (ALSPAC)
    - Generation Scotland: Scottish Family Health Study
   
- [Children of immigrants’ cognitive achievement](https://learning.closer.ac.uk/researchcasestudies/children-of-immigrants-cognitive-achievement/)
  - Uses data from two studies:
    - 1970 British Cohort Study
    - Millennium Cohort Study
   
- [Britain’s mobility problem](https://learning.closer.ac.uk/researchcasestudies/britains-mobility-problem/)
  - Uses data from four studies:
    - MRC National Survey of Health and Development (1946 British birth cohort)
    - National Child Development Study (1958 British birth cohort)
    - 1970 British Cohort Study
    - Understanding Society

---

## Unit 2.6

>[!NOTE]
> Key takeaways for three pin analogy: Standardisation increases efficiency and simplifies workflows / Economic of scale argument <br>
> KR Should we include the three pin analogy in this unit or do we feel content works ok without?<br
> BO - I think real world examples are always helpful. We could add it right to the start before we go into standards in the research context?

>[!NOTE]
> Notes from discussion with JJ: <p></p>
> Dublin Core is a standard expressed as a schema <p></p>
> Schema is name, label, description and relationship between metadata elements (description and structure) <p></p>
> Schema is technical description of a standard - it will normally be in XML, JSON <p></p>
> Schemas separates metadata element information from the actual metadata <p></p>
> Standard is the whole thing <p></p>
> Are dublin core and datacite known as a schema or a standard?
> Metadata schemas provide similar clarification to metadata elements that contolled vocabularies do for metadata fields
> Schemas constrict meaning of metadata element
> **REVIEW** (doesn't necessarily belong here) Exercise - CSV file (name of column), database schema (name of column and data format), SPSS/STATA/SAS file (data, codelist, label of column but doesn't include relationships), DDI file


Moreover, the machine actionability of metadata
- Makes data more FAIR by increasing the quality of the metadata
  - Promotes interoperability of metadata
  - By enabling cross-study comparison and secondary research, metadata standards support data re-usability


>[!NOTE]
> BO - I think in the last unit we just said CVs help our metadata become "machine-actionable" (I might be misremembering though!). I can't remember if we've mentioned the difference between machine readable and machine actionable in the earlier units? If we haven't, I think we should do this the first time we introduce the terms, and then make sure we're using the appropriate one(s) going forward.

## Case study (practice): Finding a metadata standard

Which metadata standard would you choose for this research project?

Using [Metadata standards catalogue](https://rdamsc.bath.ac.uk/subject-index) or the [DDC Metadata standards guideline](https://www.dcc.ac.uk/guidance/standards/metadata) identify a relevant metadata standard to use for this research.

_[Description of research project - discipline, area of enquiry]_

>[!NOTE]
> We would then explain what metadata standard we picked for this dataset and give the reasoning behind it (e.g. popular in the discipline, expansive, relevant etc.)


## Case study (answer): Finding a metadata standard

This is the metadata standard we chose.

Reasons behind this choice:
- [give the thought process behind choosing that particular metadata standard]


## Application: Find a metadata standard for your research

Now you have practised finding a relevant metadata standard, find a metadata standard for you research.

---
## 2.7

As we go along, we will refer back to [unit 2.5](<2.5 Controlled vocabularies.md>) and [unit 2.6](<2.6 Metadata standards.md>) to think about the tools we can use to create high-quality, effective metadata.


<details>
<summary><b>Who should create research project metadata?</b></summary>
<p></p>
  
Every research project should caputre some level of metadata. Even if you're not planning to share or deposit your data, metadata is a helpful tool to manage and preserve your data so you can come back to it at a later date. For people who are sharing their data, metadata is key in helping others find, understand and access your data, and is often an essential requirement of data repositories and data catalogues.

</details>

<details>
<summary><b>When should you create metadata?</b></summary>
<p></p>

You can create metadata about your research project from the beginning. Starting at the beginning will save you time in the long-term and will allow you to update and add to your metadata as you go along. This means you can capture any changes made to the research project, creating provenance and provide transparency around the research process.

</details>



<details>
<summary><b>How can we produce high-quality metadata?</b></summary>
<p></p> 

**Metadata standards**

As we explored in [unit 2.6](<2.6 Metadata standards.md>), a metadata schema or standard can help make our metadata interoperable with other projects' metadata. Schemas and standards can also help us identify what metadata to create as they often specifcy what metadata elements to capture. You should select a metadata schema or standard at the very beginning of a reasearch project so you don't have to re-do or retrofit metadata into a standard at the end of a project. 

What schema or standard to use depends on your research. You can select a discipline specific standard or an inter-disciplinary standard. If you want to deposit your data or metadata in a repository, the repository may require you to adhere to a specific schema or standard. 

</details>

<details>
<summary><b>How should you store metadata?</b></summary>
<p></p>

Metadata should be created and stored in a machine readable format. To begin with, you can create study level metadata in an excel spreadsheet stored alongside your data files. There is also other software available to help create and manage metadata, we will explore this more in the Foundation course.

</details>

