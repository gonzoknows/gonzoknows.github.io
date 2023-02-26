---
title: GPTZero Case Study (Exploring False Positives)
date: 2023-02-19 00:01:00 -0800
categories: [Artificial Intelligence, AI Detection]
tags: [plagiarism, gptzero, ai]                   #tags should always be lowercase
---

## Introduction
In this case study, I will be sharing the vast amounts of false positives current AI detection software gives, specifically for this case study I will be demonstrating GPTZero. I personally want to thank the supposed "Healthcare professional" who brought this to my attention via my contact [link](https://simplex.chat/contact#/?v=1-2&smp=smp%3A%2F%2F0YuTwO05YJWS8rkjn9eLJDjQhFKvIYd8d4xG8X1blIU%3D%40smp8.simplex.im%2F4dgDprEeyoZrmJCgU2GBv7zIIvjSg4Qt%23%2F%3Fv%3D1-2%26dh%3DMCowBQYDK2VuAyEAxLm3lJtPPwoIE3e-4eS2348cbjMIaVqEqVLDUDz0NDc%253D%26srv%3Dbeccx4yfxxbvyhqypaavemqurytl6hozr47wfc7uuecacjqdvwpw2xid.onion). It has motivated me to look more into this issue rather than just posting bypasses to these popular AI detection software programs, it will be only more beneficial to highlight their real usability in general. 

## What is [GPTZero](https://gptzero.me/)?
GPTZero is a tool that uses certain characteristics of AI to identify when AI is being used. It looks at things like how difficult it is for the AI to understand certain words or phrases, and uses this information to tell if the AI was involved in creating a piece of text. It's like a "fingerprint" for AI, that can detect when it has been used.

## The False Positives 
From my own testing before even thinking about writing this case study on GPTZero, I have found that GPTZero gives very mixed results while OpenAI's AI Classifier is usually more consistent but less informative about what is AI written and what is human written. After testing the medical paper on `"Severe Outcomes Among Patients with Coronavirus Disease 2019 (COVID-19) — United States, February 12–March 16, 2020"` - [Source](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7725513/)

 GPTZero states that more than 50% of this paper is AI written, and keep in mind this is only the **first paragraph** taken from the paper. Considering this is an official medical paper and that was written in 2020 by [Multiple CDC Contributors](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7725513/#article-1aff-info). It's not AI written, it's quite obvious this is a **false positive**. 

 `Note: Even after testing the maximum amount of words (5,000 characters) against GPTZero, the false positives still scored above 50%`

![Image display's a false positive in GPTZero detection method](/assets/img/gptzero%20case%20study/gptzero.png)

`Thank you to the supposed "Healthcare professional" for sharing this link`

### Pie Chart
The following pie chart follows these rules below. 
- All papers tested will be under the "[neurology](https://www.ncbi.nlm.nih.gov/pmc/?term=neurology)" topic
- All papers that are flagged as AI or low perplexity counts will be marked as false positive
- All papers abstracts will only be tested 
 
The Results are shocking, as GPTZero marks 11 of the 20 medical papers as having AI written portions. Keep in mind, I only tested the abstracts of the papers. 
![Image display's a pie chart showing false positives in GPTZero's detection model](/assets/img/gptzero%20case%20study/gptzero%20pie%20chart.png)

### Pie Chart Resources
False Positives:
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7164350/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7164350/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8093009/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8093009/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7668548/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7668548/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8055322/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8055322/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5894931/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5894931/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6105044/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6105044/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3776536/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3776536/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5047042/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5047042/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4762419/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4762419/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7538222/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7538222/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3590056/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3590056/)

Positives: 
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5573046/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5573046/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9302935/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9302935/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4239836/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4239836/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4098835/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4098835/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6453766/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6453766/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3359588/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3359588/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3235353/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3235353/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4115603/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4115603/)
- [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9202529/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9202529/)

Wayback Machine Screenshot Link

`This screenshot serves as a representation of what order these medical papers where tested in. The order follows from 1 through 20.`

[https://web.archive.org/web/20230219025214/http://web.archive.org/screenshot/https://www.ncbi.nlm.nih.gov/pmc/?term=neurology](https://web.archive.org/web/20230219025214/http://web.archive.org/screenshot/https://www.ncbi.nlm.nih.gov/pmc/?term=neurology)

## The Control (Baseline)
As a control for our case study, I will be using OpenAI's (ChatGPT Parent Company) AI Classifier. 

`Note: OpenAI's AI classifier is a "work-in-progress"`

The image below shows the first paragraph from the medical paper on `"Severe Outcomes Among Patients with Coronavirus Disease 2019 (COVID-19) — United States, February 12–March 16, 2020"` - [Source](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7725513/)
![Image display's a medical paper tested against OpenAI's AI Classifier](/assets/img/gptzero%20case%20study/classifier.png)
`"The classifier considers the text to be unclear if it is AI-generated." - OpenAI's AI Classifier`

Due to this paper being published in 2020 and the academic level of this paper. It's extremely unlikely this paper used any AI based software. We can actually do another test to insure with 100% certainty, this paper didn't use any AI when writing by looking back at it's archived links via [Wayback Machine](https://web.archive.org/) by Internet Archive. 

According to the Wayback Machine from the archived link [https://web.archive.org/web/20210823160148/https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7725513/](https://web.archive.org/web/20210823160148/https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7725513/), dated (August 23, 2021). The wording has not changed since publication.

`The Wayback Machine is a community based universal internet archive tool, that takes timestamped screenshots of the web. With the goal of perserving the web and it's content`

### OpenAI AI Classifier Limitations

"Current limitations:

- Requires a minimum of 1,000 characters, which is approximately 150 - 250 words.
- The classifier isn't always accurate; it can mislabel both AI-generated and human-written text.
- AI-generated text can be edited easily to evade the classifier.
- The classifier is likely to get things wrong on text written by children and on text not in English, because it was primarily trained on English content written by adults." - [Source](https://openai.com/blog/new-ai-classifier-for-indicating-ai-written-text/)

## The Problem

Having inaccurate reports on a software program that is about to go commercial is a big red flag and brings along many problems. Far too many problems to simply state in a single blog post. The biggest problem I personally can see it having and one that can relate to my life is plagiarism in the education field. If a student is wrongfully accused of plagiarism due to the institution following a flawed AI detection program, it could be detrimental to any student. At my institution, plagiarism carries a huge impact on your character. My university labels it as "Academic dishonesty, therefore, is a serious breach of university standards and will result in substantial penalties."