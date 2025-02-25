---
title: DDI-LIfecycle Questions and Instruments
author: Jon Johnson
date: February 25, 2025
---

## Outline

- Questionnaires and Surveys
  - Questionnaire structure
  - Questionnaire components

---

## What is a question?

![](img/what-is-a-questiona.png)


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
| Question      | qstn     | QuestionItem      |
|               | qstLit   | QuestionGrid      |
|               |          | QuestionBlock     |
| Measurement   |          | MeasurementItem   |
| Instruction   | preQTxt  | Instruction       |
|               | postQTxt |                   |

DDI-C has limitations

---

## QuestionItem

![](img/question-item-relationships.png)

| Routing       |          | Sequence. Loop    |
|               |          | IfThenmElse.      |
|               |          | RepeatUntil,      |
|               |          | RepeatWhile       |

---

## Acknowledgements and Sources

Slides 

DDI Training Group. (2021, August 11). Introducing Question and Instrument Structures. Zenodo. https://doi.org/10.5281/zenodo.5180579

---
