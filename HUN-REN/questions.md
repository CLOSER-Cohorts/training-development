---
title: DDI Questions
author: Jon Johnson
date: March 8, 2025
---

## Outline

- What is a question
- Question vs Variable
- DDI-Codebook vs DDI-Lifecycle
- Question Item
- Response Domains

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
|                |          |                   |

DDI-Codebook has limitations for our purposes, so we will just be talking about DDI-Lifecycle

---

## Questions in DDI-Lifecycle

![](img/data-provenance.png)

::: notes
Questions are a central part of the way in which we bring together a concept and its use as an 'instrument' of social enquiry.
:::

---

## DDI-Lifecycle Question Types

There are three question structures in DDI-Lifecycle

- QuestionItem
- QuestionGrid
- QuestionBlock
  - QuestionItem


 ::: notes
 QuestionBlocks are a collection of QuestionItems, we wil concentrate on QuestionItems.
 :::

 ---

## DDI Question Item

QuestionItem type brings together all the elements needed to describe, implement and manage a question

![](img/question-item-relationships.png)

---

## Question Item elements (Implementing)

- In/Out Parameter, Binding are for passing information into the question text (she/he etc)
- External Aid (e.g. a card with response options)
- EstimatedSecondsResponseTime - for a timed question
- ResponseCardinality - number of allowed responses e.g. tick all that apply, max 2/8 etc)

---

## Question Item elements (Management)

- QuestionScheme (all QuestionItems 'live' in a QuestionSheme, there can be multiple)
- RepresentedVariable (definition of variable from output)
- ResponseDomainReference (reference to another place where the ResponseDomain is held)
- InterviewerInstructionReference

---

## Question Item elements (Describing)

- QuestionItemName, Label, Description (ISO 11179)
  - e.g. A1, WORKTYPE
- QuestionIntent, Concept, QuestionGroup (Semantics)
- Question Text (e.g. What is your name)
- Representation
  - ResponseDomain (e.g. CodeList, Text, numeric)
  - StructuredMixedReponseDomain (e.g CodeList + Text)
- ExternalInterviewerReference, InterviewerInstructionReference

---

## Question Item Code List Example

![](img/question-item-example-code-list.png)

::: notes
This shows a question item from Understanding Society, Question name, text, representation type and cardinality (selection style)
:::

---

## Question Item Text language

```xml

<QuestionItemName>
  <r:String xml:lang="en-GB">qi_68</r:String>
</QuestionItemName>
<QuestionText audienceLanguage="en-GB">
  <LiteralText>
    <Text>How interested are you in politics?</Text>
   </LiteralText>
</QuestionText>
<QuestionText audienceLanguage="hu-HU">
  <LiteralText>
    <Text>Mennyire érdekli a politika?</Text>
   </LiteralText>
</QuestionText>

```

::: notes
Text in the same item can be repeated in different language for both content (name and label) and the text, which audience
- audienceLanguage="fr-FR">Dans quelle mesure êtes-vous intéressé par la politique
:::

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

![](img/code-representation.png)

::: notes
Codes are used in two ways as traditional code lists and in statistical classifications which can be more complex e.g. heirachical, levels etc
:::

---

## Code List 

![](img/code-list.png)

---


## Code List (Detail)

```xml
<CodeList>
  <Code isUniversallyUnique="true">
  <r:URN>urn:ddi:uk.iser.ukhls:adc21c8d-40bb-4104-83bb-c5709019a385:1</r:URN>
    <r:CategoryReference>
      <r:TypeOfObject>Category</r:TypeOfObject>
    </r:CategoryReference>
    <r:Value>3</r:Value>
  </Code>
</CodeList>

```

---

## Question Item Numeric Example

![](img/question-item-example-numeric.png)

----

## Numeric Representation

![](img/numeric-representation.png)

---

## Numeric Representation (Details)

```xml

<QuestionText audienceLanguage="en-GB">
  <LiteralText>
    <Text>How many hours paid work did you do last week?</Text>
  </LiteralText>
</QuestionText>
<NumericDomain blankIsMissingValue="false">
  <r:NumberRange>
    <r:Low isInclusive="true">0</r:Low>
    <r:High isInclusive="true">168</r:High>
  </r:NumberRange>
  <r:NumericTypeCode controlledVocabularyVersionID="1.0">Integer</r:NumericTypeCode>
  <r:Label>
    <r:Content xml:lang="en-GB">Hours in week</r:Content>
  </r:Label>
</NumericDomain>

```
---

## Date / Time Representation Example

![](img/question-item-example-date-time.png)

---

## Date / Time Representation

![](img/date-time-representation.png)

---

## Date / Time Representation (Detail)

```xml

<QuestionText audienceLanguage="en-GB">
  <LiteralText><Text>Please write in your date of birth.
  </Text></LiteralText>
</QuestionText>
<DateTimeDomain blankIsMissingValue="false">
  <r:DateTypeCode controlledVocabularyVersionID="1.0">Date</r:DateTypeCode>
    <r:Label>
      <r:Content xml:lang="en-GB">Date of birth</r:Content>
    </r:Label>
</DateTimeDomain>

```

---

## Question Item Text Example

![](img/question-item-example-text.png)

---

## Text Representation

![](img/text-representation.png)

---

## Text Representation (Detail)

```xml

<QuestionText audienceLanguage="en-GB">
  <LiteralText>
    <Text>
      Finally, what job would you like to do once you leave school?
    </Text>
  </LiteralText>
</QuestionText>
<TextDomain blankIsMissingValue="false" maxLength="255">
  <r:Label>
    <r:Content xml:lang="en-GB">Generic text</r:Content>
  </r:Label>
</TextDomain>

```
---

## Acknowledgements and Sources

- Hayley Mills (2021) DDI Lifecyle: Questions and Instruments (https://docs.google.com/presentation/d/1wZ03TVoVMv-TWI9rMD-lWUh6XhF233ws/edit#slide=id.p1)
- DDI Alliance (2025) DDI Model (https://ddialliance.github.io/ddimodel-web/)







