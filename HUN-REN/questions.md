---
title: DDI Questions
author: Jon Johnson
date: March 8, 2025
---

## Outline

- What is a question
- Question vs Variable
- DDI-Codebook vs DDI-Lifecycle

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

**DDI-Codebook** is variable-centric – it only provides a partial description of question as the source of data for a variable

**DDI-Lifecycle** supports stand-alone question specification, implementation and management, crucially its representation, and can also describe the use of a question within a questionnaire flow-logic

---

## DDI Items Related to Questions

| Coverage       | DDI-C    | DDI-L             |
|----------------|----------|-------------------|
| Question Text  | qstLit   | QuestionText      |
| Question       | qstn     | QuestionItem      |
| ResponeDomain  |          | Representation    |
| Instruction    | preQTxt  | Instruction       |
|                | postQTxt |                   |
| Flow / Logic   |          | ControlConstructs |


DDI-Codebook has limitations for our purposes, so we will just be talking about DDI-Lifecycle

---

## DDI-Lifecycle Question Types

There are three quesstion structures in DDI-Lifecycle

- QuestionItem
- QuestionGrid
- QuestionBlock
  - QuestionItem

 :::
 QuestionBlocks are a collection of QuestionItems, we wil concentrate on QuestionItems.
 :::

## DDI Question Item

QuestionItem type brings togather all the elements needed to describe, implement and manage a question

![](img/question-item-relationships.png)

---

## Question Item elements (Implementing)

- In/Out Parameter, Binding are for passing information into the question text (she/he etc)
- External Aid (e.g. a card with response options)
- EstimatedSecondsResponseTime - for a timed question
- ResponseCardinality - number of allowed responses e.g. tick all that apply, max 2/8 etc)


---

## Question Item elements (Management)

- QuestionScheme
- RepresentedVariable (definition of variable from output)
- ResponseDomainReference (reference to another place where the ResponseDomain is held)
- InterviewerInstructionReference


---

## Question Item elements (Describing)

- QuestionItemName, Label, Description (ISO 11179)
  - QuestionItemName (e.g. A1, WORKTYPE)
- QuestionIntent, Concept, QuestionGroup (Semantics)
- Question Text (e.g. What is your name)
- QuestionText (The question, allows insertion of contextual information)
- Representation
  - ResponseDomain (e.g. CodeList, Text, numeric)
  - StructuredMixedReponseDomain (e.g CodeList + Text)
- ExternalInterviewerReference, InterviewerInstructionReference  (to where they are held)

---

## Representation Types

- CodeRepresentation
- DateTimeRepresentation
- TextRepresentation
- NumericRepresentation
- Other Numeric e.g. Nominal, Scale, Ranks
- CategoryRepresentation (used in classifications)
- Geograhical - several available

---

## Code Representation



---

## Numeric Representation

---

## Date / Time Representation

---

## Text Representation

---

## Acknowledgements







