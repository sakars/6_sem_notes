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

## CAPTCHA

CAPTCHA (Completely Automated Public Turing test to tell Computers and Humans Apart) is **a type of security measure known as challenge-response authentication**.


## Classic IR

[[#Information Retrieval (IR)]] before ~2013 when traditional algorithms were used instead of [[#Natural Language Processing (NLP)]] and Machine learning

From [[2025-02-07#Classic Information retrieval]]

## Click-through rate (CTR)

CTR is **the number of clicks that your ad receives divided by the number of times your ad is shown**: clicks ÷ impressions = CTR

From [[2025-02-21#Google rich snippets]]

## Corpus

A set of documents or texts typically all having some desired property. Like a filtered dataset

One of the larger examples is [WebCorp: The Web as Corpus](https://www.webcorp.org.uk/live/) - an offline collection of a part of a 

## Corpus-based QA

>[!info] Here QA means Question-answering, not quality assurance

A mechanism that attempts to find answers from a [[#Corpus|corpus]]
This usually involves using [[#LLM (Large Language Model)|LLMs]] to extract the correct data.

## Cosine similarity
This is the cosine similarity of a query and a document.
$$
\textit{sim}\left(q,d\right) =
\cos \alpha = 
\frac{q\cdot d}{|q| \cdot |d|} = 
\frac{\sum_{i=1}^{n}{q_i\cdot d_i}}{\sqrt{\sum^{n}_{i=1}{q_i^2}} \cdot \sqrt{\sum^{n}_{i=1}{d_i^2}}}$$

- $q$ is the query
- $d$ is the document to compare against
- $q_i$ is the query parameter for the $i$-th term.
- $d_i$ is the document parameter for the the $i$-th term.

The parameter can be one of various things:
- [[#Term weights]]
- [[#Term frequency]]
- Binary $0$ or $1$ (does the term appear)


When comparing different similarities with the same query, $\left|q\right|$ becomes essentially a constant multiplier. 

If similarity is not required to be in $\left[-1;1\right]$ bounds and comparison is made against the same query, a simplified formula could also be used

$$
\textit{sim}_{\textit{simplified}}\left(q,d\right) = 
\frac{q\cdot d}{|d|} = 
\frac{\sum_{i=1}^{n}{q_i\cdot d_i}}{\sqrt{\sum^{n}_{i=1}{d_i^2}}}
$$

A slight variation used in one of the homework assignments:
$$
\textit{sim}\left(q,d\right) = 
\frac{\sum_{i=1}^{n}{q_i\cdot d_i}}{N_d}
$$

Here, $N_d$ is the word count in documents.

From [[2025-02-07#Vector space model]]
## Crawler
A program that reads websites and indexes or registers their content.


# Č

# D

## Dark web

Web resources that take special precautions to not be found. 

From [[2025-02-07#The invisible web]]

## Document Vector

A grid of what words lie in a document

From [[2025-02-07#Vector space model]]

# E

## Explicit relevance feedback

[[#Relevance feedback]] That is acquired by the user explicitly changing the search parameters or some other information (for example changing the query)

From [[2025-02-07#Explicit relevance feedback]]

See [[#Relevance feedback]]


# Ē

# F

# G

## Google
The biggest search engine in the world. It has like 92% market share.
You know what it is, stop playing dumb.

From [[2025-02-10#Google]]
More on [[2025-02-10#How Google searches (at least kinda)]]
# Ģ

# H

# I

## Implicit Relevance Feedback

[[#Relevance feedback]] that is gained without explicit user interaction.
- Click-through rate
- time on-site
- Bounce rate
- Conversion rate
- Returning visitors

From [[2025-02-07#Implicit relevance feedback]]

See also [[#Relevance feedback]]
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

## LLM (Large Language Model)

From [Large language model - Wikipedia](https://en.wikipedia.org/wiki/Large_language_model)
> A **large language model** (**LLM**) is a type of [machine learning](https://en.wikipedia.org/wiki/Machine_learning "Machine learning") [model](https://en.wikipedia.org/wiki/Model#Conceptual_model "Model") designed for [natural language processing](https://en.wikipedia.org/wiki/Natural_language_processing "Natural language processing") tasks such as language [generation](https://en.wikipedia.org/wiki/Generative_artificial_intelligence "Generative artificial intelligence"). LLMs are [language models](https://en.wikipedia.org/wiki/Language_model "Language model") with many parameters, and are trained with [self-supervised learning](https://en.wikipedia.org/wiki/Self-supervised_learning "Self-supervised learning") on a vast amount of text.

## Link analysis

Algorithm to figure out the importance of documents, neighbourhoods.

From [[2025-02-07#Classic Information retrieval]]

# Ļ

# M

## Metadata

Data used to describe other data

For example, keywords, titles of books, release date. 

## Microdata

![[#Structured data]]

# N

## Natural Language Processing (NLP)

Algorithms for understanding text, not just matching keywords

## NavBoost

A tool by [[#Google]] that gathered data on users through the Google Chrome browser to improve the search results.

From [[2025-02-10#NavBoost]]


## Nofollow-links

In 2005, google introduced this type of links. They mark links as potential spam or other types of links that any crawlers should discard completely. They are still used to indicate that they should be discarded by search engines

```html
<a rel=”nofollow” href=”privacy.html”>Privacy policy</a>
```

From [[2025-02-10#Specialized links]]

# Ņ

# O

## Open data
Data that is freely available on the web to use, share, modify.

Some examples of open data are:
- [OpenStreetMap](https://www.openstreetmap.org/#map=7/56.895/24.608)
- [The official portal for European data | data.europa.eu](https://data.europa.eu/en)
- [Latvijas Atvērto datu portāls](https://data.gov.lv/lv)
- [awesomedata/awesome-public-datasets: A topic-centric list of HQ open datasets.](https://github.com/awesomedata/awesome-public-datasets)


From [[2025-02-07#Semantic web, Social web, Open data]], [[2025-03-07#Open data]]
# P

## Page Rank

A method to rank different webpages in a way that doesn't harm them, when webpages have a lot of outgoing links. Only incoming links are relevant.

The formula:

$$
\mathit{PR}(A) = 
(1-d) + d \left(
\frac{\mathit{PR(T_1)}}{C(T_1)} + 
\frac{\mathit{PR(T_2)}}{C(T_2)} + 
... +
\frac{\mathit{PR(T_n)}}{C(T_n)}
\right)
$$
$A$ - Document we want the page rank of
$d$ - Probability that the person will click on the link. Usually $0.85$
$T_n$ - $n$-th document that links to $A$ 
$PR(X)$ - Page rank of document $X$
$C(X)$ - amount of outbound links going out of document $X$

No [[2025-02-07#IR pamati]], [[2025-02-07#Link analysis]]

## Polite crawler

A [[#Crawler]] that obeys [[#Sitemap|Sitemaps]] and [[#Robots.txt]] pages for what to index and what to ignore.
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

## Relevance feedback

A metric/metrics which show what is relevant by using the information from users to improve the search results.

See also [[#Implicit Relevance Feedback]], [[#Explicit relevance feedback]]

From [[2025-02-07#Relevance feedback]]

## Rich snippets

Extra info that some webpages can mark for appearing in search results

![[Pasted image 20250221105829.png]]

From [[2025-02-21#Google rich snippets]]

## Robots Exclusion Protocol
![[#Robots.txt]]

## Robots.txt 

Also called the [[#Robots Exclusion Protocol]], it indicates to polite crawlers, which pages should or shouldn't be crawled.

From [[2025-02-10#Robots exclusion protocol]]

# S

## Schema.org

A standardized vocabulary created by the most popular search engines. Contains over 1000 categories with which you can organize data for a [[#Crawler]] to display items like [[#Google]] rich snippets.

Site: [Schema.org - Schema.org](https://schema.org/)

From [[2025-02-21#Schema.org]]

## Search engine

A program that has indexed the web, connecting and allowing to find webpages, making the web more transparent.


## Search Engine Optimization (SEO)

Algorithms for improving the results of a [[#Search engine]]

## Semantic tagging

Additional information in webpages that can be used by search engines. Especially useful in Classic IR.

For example, recognizing reviews.

From [[2025-02-07#Semantic web, Social web, Open data]]


## Semantic web

An idea that information need not be located all in a single place. Multiple websites can contain information on the same subject. Using [[#Semantic tagging]] and other tools, we can tie these together, gathering clear information from multitudes of inputs.

## Sitemap

A map containing all links that are accessible to crawlers/users.

It is used to "flatten" the depth of links for crawlers. This way they only need around 2 page jumps to get to every page


From [[2025-02-10#Sitemap]]

## SPARQL

A query language for the [[#Semantic web]].

SPARQL, pronounced 'sparkle', is **the standard query language and protocol for Linked Open Data on the web or for RDF triplestores**.

## Sponsored links


```html
<a rel="sponsored" href="example.com">MySponsor</a>
```

This is used for advertisements, sponsorships. Crawlers may have special handling for these

From [[2025-02-10#Specialized links]]

## Standard Recall values

The usual recall values at which a [[#Precision-Recall curve]] is interpolated.
The standard recall values are:
0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1.0

## Stop-word

Word that is filtered out from documents/queries before procedures like [[#Cosine similarity]] are calculated.

## Structured data

Also sometimes called [[#Microdata]], it describes additional information that html pages can add to create extra information for web [[#Crawler|crawlers]] and [[#Search engine|search engines]].

Can be used to create, for example [[#Rich snippets]]

From [[2025-02-21#IMT]]

# Š

# T

## Term frequency

$\mathit{tf}_{ij}$ is the frequency of the $j$-th term in the $i$-th document.

Frequency just means how many occurrences of that term appears

## Term Vector
![[#Document Vector]]

## Term weights

A calculation used to find common, but distinctive terms for calculating the similarity.

See [[2025-02-07#Vector space model]]
# U

## UGC (User Generated Content)


```html
<a rel="ugc" href="example.com">ROFL</a>
```

These links indicate that they were generated by users such as comments or forum posts

Crawlers may use special behaviour for these.

From [[2025-02-10#Specialized links]]

# Ū

# V

## Vector space model

A search model that uses [[#Document Vector|Document vectors]] to get the similarity between documents and queries

# W

## Webmaster

A mostly outdated term for a person who manages and optimizes a webpage. 
They usually focus on [[#Search Engine Optimization (SEO)]], [[#Semantic tagging]] and other topics to make sure the webpage is run smoothly and is accessible.

## Word Proximity

An extra operator that can be introduced in a [[#Boolean retrieval model]] that can look at distance of words in the original text.

This does mean that the model needs the original text, not just a [[#Bag of words]].

From [[2025-02-07#Boolean retrieval model]]
# X

# Y

# Z

# Ž
