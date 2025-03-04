---
title: DDI-LIfecycle Questionnaires and Instruments
author: Jon Johnson
date: March 8, 2025
---

## Outline

- Questionnaires and Surveys
  - Questionnaire structure
  - Questionnaire components

---

## What is a question?

![](img/what-is-a-question.png)


---

## Question vs Variable

::::: columns
::: column
*Question*

- Describes a means of capturing data
- A question specifies a text and a means of defining the form of the expected response
- Questions can be organized in a questionnaire

:::
::: column
*Variable*

- Description of data
- A variable does not need to come from a question
:::
:::::

---

## Questions in DDI

**DDI Codebook** is variable-centric – it only provides a partial description of question as the source of data for a variable

**DDI Lifecycle** supports stand-alone question specification and management, can describe the use of a question within a questionnaire flow-logic

---

## DDI Items Related to Questions

| Coverage      | DDI-C    | DDI-L             |
|---------------|----------|-------------------|
| Questionnaire |          | Instrument        |
| Question Text | qstLit   | QuestionText      |
| Question      | qstn     | QuestionItem      |
|               |          | QuestionGrid      |
|               |          | QuestionBlock     |
| Measurement   |          | MeasurementItem   |
| Instruction   | preQTxt  | Instruction       |
|               | postQTxt |                   |

DDI-Codebook has limitations for our purposes, so we will just be talking about DDI-Lifecycle

---

## Questionnare structure

![](img/hun-ren-simple-questionnaire.png)

:::
This is possibly the simplest questionnaire imaginable, Title, some information about what is going to do, something to tell the respondent the sort of information in each clock of questions, a question with some response options 
a filter to ask quesitons only of specific universe of participantes,and another question with a different type of response option
:::


---

## Questionnare structures and DDI

DDI Lifecycle allows the **specification**, **management of the questionnaire components**, **implementation**, and subsequent **description** of these componente to their **relationship** to the data generated from the questionnaire. It is necessarily complex as a result of its multiple roles.


---

## DDI Instrument Model

![](img/instrument.png)

:::
Instruments have a relationship to other instruments (group/scheme), a data collection, types of collection and development activities
:::


---

## DDI Instrument Model (Focus)

![](img/instrument-high-level.png)

:::
Just looking at the instrument object, common things to describe a questionnaire, name, label, description but other than that NOTHING that looks familiar
This is becuase the actual questionnaire is an abstract object called a **ControlConstruct** which is a wrapper for all the things contained in an actual questionnaire
:::


---

## DDI Control Construct

![](img/control-construct.png)

:::
This acts as a set of containers for the things we actually want to be asking and the things that control the way in which we implement it. 
Again, not many things here we are familiar with!
Typically a questionnaire starts with a sequence
:::

---

## DDI Sequence

![](img/sequence.png)

:::
So we can see here that a sequence is a way of controlling the flow of a questionnaire Sequence contains Control Constructs.
A special construct is the QuestionConstruct 

:::

---

## DDI Question Construct

![](img/question-construct.png)

:::
Finally, we have something we can recognise a Question!
And some things we might want to associate with it such as a response unit or analysis unit
:::

---

## DDI Question

![](img/question.png)

:::
Nearly there, there are three types of question supported in DDI, QuestionItem, QuestionBlock and QuestionGrid, so Question act as ANOTHER wrapper, pointing to a ControlConstruct .... which brings us to a QuestionItem
:::

---

## DDI QuestionItem 

![](img/question-item-relationships.png)

:::
There are a number of things here which we should focus on
:::

---

## DDI QuestionItem Elements

- Question Item Name (e.g. A1, WORKTYPE)
- Question Text (e.g. What is you name)
- ResponseCardinality (e.g. 1, 2, all)
- ResponseDomain (e.g. CodeList, Text, numeric)
- StructuredMixedReponseDomain (e.g CodeList + Text)

:::

I'm afraid we are not finished .... the response domain is another whole set of relationships
:::

---

## DDI Response Domain Representations

![](img/representations.png)

:::
There are a wide range of possible representations for responses available
:::

----

## DDI QuestionItem Relationships

![](img/question-item-relationships.png)

:::
Instruction - This is a seperate element from Question Text 
Concept - a questionItem can be directly associated with a specific or multiple concepts
QuestionGroup - a way of creating groups of questions by some other typology
QuestionScheme - a storage container for question items - used for manageing them
:::

---


## Acknowledgements and Sources

- Hayley Mills, (2021) DDI Lifecyle: Questions and Instruments https://docs.google.com/presentation/d/1wZ03TVoVMv-TWI9rMD-lWUh6XhF233ws/edit#slide=id.p1
- DDI Alliance, DDI Model  https://ddialliance.github.io/ddimodel-web/

---
