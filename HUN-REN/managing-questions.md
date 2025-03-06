---
title: Structures for Managing Questions in DDI
author: Jon Johnson
date: March 8, 2025
---

## Outline

---

## Overview

Even a simple object such as a QuestionItem has a lot of complexity.

Different response domains require different structures, but these are useful in being able to a priori determine the type of a question.

DDI has a number of additional structures which can also be used to manage and harmonise.

---

## Generic DDI structures (Agency)

Each DDI item has a URN (a persistent identifier) which can be used to assist in management

```
urn:ddi:agency:id:version
<URN>urn:ddi:uk.iser.ukhls:2f1e27ba-e2e9-4bfe-a814-fa54809a77c9:1</urn>

```

This can be used to identify all items from a specific agency e.g. to differentiate between different data collectors. 

---

## Generic DDI structures (basedOn)

If you want to specify that one question is based on another e.g. there was an additional code added to the code list. 

This is also useful if you have a set of translated questions as separate question items that you want to associate with each other. 

**NB** this is a pair-wise operation so can be cumbersome to implement.

---

## Generic DDI structures (Language)

```xml
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
Powerful way of managing questions in a multi language environment. It does however require that the QuestionItem is in a single Agency

---

## Generic DDI structures (Concept)

QuestionItems ccan reference a concept ideally through an explicit persistent identifier, this can be any PID in a vocabulary or concept scheme.

---

## Generic DDI structures (Schemes)

QuestionItems are by default in a QuestionScheme. You cannot have have QuestionItems 'free floating'.

You can create multiple schemes by a theme, or other categorisation to suit your purposes. 

Since a QuestionItem has a URN moving it between schemes does not affect it, so you can have a generic scheme and move it later. 
This might be useful if you want to allow only certain users to manage a specific type of question. 

## Generic DDI structures (
Q — QG
QGs are useful for adhoc grouping. Groups can reference a concept. This is a more flexible way of managing question-concept relationships than assigning a concept reference to the QI

Agency





