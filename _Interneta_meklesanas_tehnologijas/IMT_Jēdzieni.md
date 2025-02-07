# A

# Ā

# B

## Bag of words

Text converted into a set of word occurrences.
These occurrences are counted.

From [[2025-02-07#Bag of words]]

## Boolean retrieval model

Each document is a [[IMT_Jēdzieni#Bag of words|bag of words]].
Query contains Boolean operators AND, OR, NOT
Search the documents for bags matching query.

The same principle could be applied with keywords.

This is a data *filtering* model, not a *sorting* model.

From [[2025-02-07#Boolean retrieval model]]
# C

## Classic IR

[[#Information Retrieval (IR)]] before ~2013 when traditional algorithms were used instead of [[#Natural Language Processing (NLP)]] and Machine learning

From [[2025-02-07#Classic Information retrieval]]

## Cosine similarity
This is the cosine similarity of a query and a document.
$$
\textit{sim}\left(q,d\right)
\cos \alpha = 
\frac{q\cdot d}{|q| \cdot |d|} = 
\frac{\sum_{i=1}^{n}{q_i\cdot d_i}}{\sqrt{\sum^{n}_{i=1}{q_i^2}} \cdot \sqrt{\sum^{n}_{i=1}{d_i^2}}}$$

From [[2025-02-07#Vector space model]]
## Crawling


# Č

# D

## Dark web

Web resources that take special precautions to not be found. 

From [[2025-02-07#The invisible web]]

## Document Vector

A grid of what words lie in a document

From [[2025-02-07#Vector space model]]

# E

# Ē

# F

# G

# Ģ

# H

# I

## Information Retrieval (IR)

Termins, kas radies ap 1950-ajiem.

Apzīmē meklēšanu tekstā, teksta līdzību, mūsdienās iekļauj matemātiskus modeļus meklēšanai tekstā.

Vēlāk ar interneta parādīšanos arī saišu analīze.

No [[2025-02-07#Mazliet vēstures]]
No [[2025-02-07#Information Retrieval]]

## Invisible web

Information not findable by the usual web crawlers

From [[2025-02-07#The invisible web]]
# Ī

# J

# K

# Ķ

# L

## Link analysis

Algorithm to figure out the importance of documents, neighbourhoods.

From [[2025-02-07#Classic Information retrieval]]

# Ļ

# M

## Metadata

Data used to describe other data

For example, keywords, titles of books, release date. 

# N

## Natural Language Processing (NLP)

Algorithms for understanding text, not just matching keywords

# Ņ

# O

## Open data
Data that is freely available on the web.

From [[2025-02-07#Semantic web, Social web, Open data]]
# P

## Page Rank

A method to rank different webpages in a way that doesn't harm them, when webpages have a lot of outgoing links. Only incoming links are relevant.

No [[2025-02-07#IR pamati]], [[2025-02-07#Link analysis]]

## Pooling

Mechanism to reduce the size of a collection while retaining or hopefully improving [[IMT_Jēdzieni#Precision|Precision]] of the pooled data.

This is done by combining multiple search engine system results, taking the top X results from each and combining the sets. The pool size may vary because it depends on how many times systems find the same resource relevant.

From [[2025-02-07#Pooling for calculating recall]]

## Precision

Precision: Precentage of the relevant documents we retrieved

$$
P = \frac{\mathit{RETR}\cap \mathit{REL}}{\mathit{RETR}}
$$
From [[2025-02-07#Precision and recall]]

## Precision-Recall curve

Plot of the balance of different algoritms, where [[#Precision]] and [[#Recall]] define the x and y axes.
# Q

# R

## Recall

Recall: How many of the relevant documents we have retrieved

$$
R = \frac{\mathit{RETR}\cap \mathit{REL}}{\mathit{REL}}
$$

From [[2025-02-07#Precision and recall]]
# S

## Search Engine Optimization (SEO)

Algorithms for improving the results.

## Semantic tagging

Additional information in webpages that can be used by search engines. Especially useful in Classic IR.

For example, recognizing reviews.

From [[2025-02-07#Semantic web, Social web, Open data]]

## Standard Recall values

The usual recall values at which a [[#Precision-Recall curve]] is interpolated.
The standard recall values are:
0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1.0

# Š

# T

## Term Vector
![[#Document Vector]]

## Term weights

A calculation used to find common, but distinctive terms for calculating the similarity.

See [[2025-02-07#Vector space model]]
# U

# Ū

# V

## Vector space model

A search model that uses [[#Document Vector|Document vectors]] to get the similarity between documents and queries

# W

## Word Proximity

An extra operator that can be introduced in a [[#Boolean retrieval model]] that can look at distance of words in the original text.

This does mean that the model needs the original text, not just a [[#Bag of words]].

From [[2025-02-07#bool]]
# X

# Y

# Z

# Ž
