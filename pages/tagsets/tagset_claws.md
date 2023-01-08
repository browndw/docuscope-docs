---
title: CLAWS7 Tagset
tags: [getting_started]
keywords: release notes, announcements, what's new, new features
last_updated: July 3, 2016
summary: "Descriptions of the part-of-speech tags for all versions of the model."
sidebar: mydoc_sidebar
permalink: tagset_claws.html
folder: tagsets
---

## CLAWS7

CLAWS7 is robust part-of-speech tagset developed at Lancaster University. [(Try it!)](http://ucrel-api.lancaster.ac.uk/claws/free.html) It is used in the [BYU family of corpora](https://www.english-corpora.org/), a project headed by Mark Davies and in ongoing development. The popularity of those data sets partly motivated the choice to use this tagset -- as opposed to say the [Penn Treebank tagset](https://www.ling.upenn.edu/courses/Fall_2003/ling001/penn_treebank_pos.html).

This allows users to compare their results directly to those from much larger corpora. The tradeoff, is that CLAWS7 has is large and relatively fine-grained, which can be challenging for users with less familiarity to English syntax.

### Tags table

| Tag   | Description                                                        | Examples                       |
|-------|--------------------------------------------------------------------|--------------------------------|
| APPGE | possessive pronoun, pre-nominal                                    | *my*, *your*, *our*                  |
| AT    | article                                                            | the, no                        |
| AT1   | singular article                                                   | a, an, every                   |
| BCL   | before-clause marker                                               | in order (that), in order (to) |
| CC    | coordinating conjunction                                           | and, or                        |
| CCB   | adversative coordinating conjunction                               | but                            |
| CS    | subordinating conjunction                                          | if, because, unless, so, for   |
| CSA   | as as conjunction                                                  | as                             |
| CSN   | than as conjunction                                                | than                           |
| CST   | that as conjunction                                                | that                           |
| CSW   | whether as conjunction                                             | whether                        |
| DA    | after-determiner or post-determiner capable of pronominal function | such, former, same             |
| DA1   | singular after-determiner                                          | little, much                   |
| DA2   | plural after-determiner                                            | few, several, many             |
| DAR   | comparative after-determiner                                       | more, less, fewer              |
| DAT   | superlative after-determiner                                       | most, least, fewest            |
| DB    | before determiner or pre-determiner capable of pronominal function | all, half                      |
| DB2   | plural before-determiner                                           | both                           |
| DD    | determiner (capable of pronominal function)                        | any, some                      |
| DD1   | singular determiner                                                | this, that, another            |
| DD2   | plural determiner                                                  | these, those                    |

{% include links.html %}
