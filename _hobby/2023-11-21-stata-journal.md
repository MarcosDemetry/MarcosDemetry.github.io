---
layout: page
thumbnail-img: /assets/img/hobby-exploring-SJ/keywords_occurances.png
title: The Stata Journal
tags: [data, public]
---

This journal will always be special to me because it has my first peer-reviewed paper.
As an homage, I scraped data on the article title, volume, issue, and author names.

Since their start in 2001, they have published 23 volumes containing 1251 articles and 1081 unique authors.
On average, there are 56 articles per volume (or 54 if we include the incomplete volumes 1 and 23).
<img src = "/assets/img/hobby-exploring-SJ/count_articles_per_volume.png" width ="100%"/>

Some authors collaborate together several times, which gives us 738 unique author combinations.
Top authors (counting their appearance as single authors and co-authors) yields:
<img src = "/assets/img/hobby-exploring-SJ/top_authors.png" width ="100%"/>

Looking only at co-authorships, the top 20 author collaborations are:
<img src = "/assets/img/hobby-exploring-SJ/top_author_collaborations.png" width ="100%"/>

Co-authorship is also quite common and has become more common over time
<img src = "/assets/img/hobby-exploring-SJ/count_authors_per_article.png" width ="100%"/>
<img src = "/assets/img/hobby-exploring-SJ/avg_authors_per_article_per_volume.png" width ="100%"/>

Finally, we can create cool collaboration networks like this one, based on code from <a href="https://www.kaggle.com/code/bkoseoglu/co-authorship-network-analysis/notebook"> here</a>.
<iframe src = "/assets/img/hobby-exploring-SJ/collaboration_network.html" width ="100%" height = "300"></iframe>

We can also explore the topics using data from Web of Science and visualize it using VOSviewer
(this was until volume 22 and I might update soon, but not today)
For example, keyword co-occurences look like this:
<img src = "/assets/img/hobby-exploring-SJ/keywords_occurances.png" width ="100%"/>

Using words from the abstracts, we see some clear clusters.
There's a programming cluster (green-purple, bottom-right), statistics cluster (green-yellow, top-left),
economics/econometrics cluster (yellow, bottom-left).
<img src = "/assets/img/hobby-exploring-SJ/terms_occurances.png" width ="100%"/>

Uploaded 2023–11–21; Last updated 2023–11–21

<a href="/hobby">Back to Hobby</a>