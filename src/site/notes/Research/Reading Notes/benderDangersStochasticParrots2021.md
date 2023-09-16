---
{"dg-publish":true,"permalink":"/research/reading-notes/bender-dangers-stochastic-parrots2021/","tags":["gardenEntry"]}
---


## Records

### Citation

> Bender, Emily M., Timnit Gebru, Angelina McMillan-Major, and Shmargaret Shmitchell. “On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜.” In _Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency_, 610–23. FAccT ’21. New York, NY, USA: Association for Computing Machinery, 2021. [https://doi.org/10/gh677h](https://doi.org/10/gh677h).

### Abstract

> The past 3 years of work in NLP have been characterized by the development and deployment of ever larger language models, especially for English. BERT, its variants, GPT-2/3, and others, most recently Switch-C, have pushed the boundaries of the possible both through architectural innovations and through sheer size. Using these pretrained models and the methodology of fine-tuning them for specific tasks, researchers have extended the state of the art on a wide array of tasks as measured by leaderboards on specific benchmarks for English. In this paper, we take a step back and ask: How big is too big? What are the possible risks associated with this technology and what paths are available for mitigating those risks? We provide recommendations including weighing the environmental and financial costs first, investing resources into curating and carefully documenting datasets rather than ingesting everything on the web, carrying out pre-development exercises evaluating how the planned approach fits into research and development goals and supports stakeholder values, and encouraging research directions beyond ever larger language models.## Citekey
- @benderDangersStochasticParrots2021

### Tags

### Annotations



#### Imported on 2023-01-01 2:00 Pm

> [!quote] Highlight  
> One of the biggest trends in natural language processing (NLP) has been the increasing size of language models (LMs) as measured by the number of parameters and size of training data.
>
> [Page 1](zotero://open-pdf/library/items/ELEYG2UW?page=1) [2023-01-01 > 1:54 pm](2023-01-01#1:54%20pm)

> [!quote] Highlight  
> environmental and financial costs of deep learning systems
>
> [Page 1](zotero://open-pdf/library/items/ELEYG2UW?page=1) [2023-01-01 > 1:56 pm](2023-01-01#1:56%20pm)

> [!quote] Highlight  
> large datasets based on texts from the Internet overrepresent hegemonic viewpoints and encode biases potentially damaging to marginalized populations.
>
> [Page 1](zotero://open-pdf/library/items/ELEYG2UW?page=1) [2023-01-01 > 1:56 pm](2023-01-01#1:56%20pm)

> [!quote] Highlight  
> it is important to understand the limitations of LMs and put their success in context. This not only helps reduce hype which can mislead the public and researchers themselves regarding the capabilities of these LMs, but might encourage new research directions that do not necessarily depend on having larger LMs
>
> [Page 1](zotero://open-pdf/library/items/ELEYG2UW?page=1) [2023-01-01 > 1:55 pm](2023-01-01#1:55%20pm)

> [!quote] Highlight  
> the tendency of human interlocutors to impute meaning where there is none can mislead both NLP researchers and the general public into taking synthetic text as meaningful.

>> We fall for bullshit because we expect people to make good-faith arguments and therefore texts.<br />  
When this is _simulated_ really really well, what else should we expect?<br />

<br />

One way to look at all of this is to say we are training these systems to be best able to fool us!

>
> [Page 2](zotero://open-pdf/library/items/ELEYG2UW?page=2) [2023-01-01 > 1:58 pm](2023-01-01#1:58%20pm)

> [!quote] Highlight  
> increasing the environmental and financial costs of these models doubly punishes marginalized communities that are least likely to benefit from the progress achieved by large LMs and most likely to be harmed by negative environmental consequences of its resource consumption. At the scale we are discussing (outlined in §2), the first consideration should be the environmental cost.
>
> [Page 1](zotero://open-pdf/library/items/ELEYG2UW?page=1) [2023-01-01 > 1:56 pm](2023-01-01#1:56%20pm)

> [!quote] Highlight  
> In collecting ever larger datasets we risk incurring documentation debt.
>
> [Page 1](zotero://open-pdf/library/items/ELEYG2UW?page=1) [2023-01-01 > 1:56 pm](2023-01-01#1:56%20pm)

> [!quote] Highlight  
> LMs are not performing natural language understanding (NLU), and only have success in tasks that can be approached by manipulating linguistic form [14].
>
> [Page 1](zotero://open-pdf/library/items/ELEYG2UW?page=1) [2023-01-01 > 1:55 pm](2023-01-01#1:55%20pm)

> [!quote] Highlight  
> Combined with the ability of LMs to pick up on both subtle biases and overtly abusive language patterns in training data, this leads to risks of harms, including encountering derogatory language and experiencing discrimination at the hands of others who reproduce racist, sexist, ableist, extremist or other harmful ideologies reinforced through interactions with synthetic language.

>> And this is when it is accidental; we might layer on top of all of this the added inertia bad actors can give to these systems in practice.

>
> [Page 2](zotero://open-pdf/library/items/ELEYG2UW?page=2) [2023-01-01 > 1:59 pm](2023-01-01#1:59%20pm)

> [!quote] Highlight  
> critical overview of the risks of relying on everincreasing size of LMs as the primary driver of increased performance of language technology can facilitate a reallocation of efforts towards approaches that avoid some of these risks while still reaping the benefits of improvements to language technology.

>> If we orient this well, perhaps we can find helpful uses in smaller data sets.  Maximization logics (of the funding markets) seem to push it in increasingly violent and stupid directions.

>
> [Page 2](zotero://open-pdf/library/items/ELEYG2UW?page=2) [2023-01-01 > 2:00 pm](2023-01-01#2:00%20pm)




