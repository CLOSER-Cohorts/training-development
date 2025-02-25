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

## Questionnare structures and DDI

DDI Lifecycle allows the **specification**, **management of the questionnaire components**, **implementation**, and subsequent **description** of these componente to their **relationship** to the data generated from the questionnaire. It is necessarily complex as a result of its multiple roles.


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

[![DDI Lifecyle: Questions and Instruments. (2021)],(https://docs.google.com/presentation/d/1wZ03TVoVMv-TWI9rMD-lWUh6XhF233ws/edit#slide=id.p1)



---
