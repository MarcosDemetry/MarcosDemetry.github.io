---
layout: page
title: Beautifully Unnecessary Statistics (BUS)
---

## Guiding Principles ##
Human behaviour is fascinating. It is a noble pursuit to try gain a better understanding of things such as how we make decisions, the systems in which we make decisions, how we influence each other and how our individual choices translate into aggregate outcomes. In doing so, we gain new perspectives on a broad range of topics such as education, migration, health, labor and policy. As a guiding principle, I believe in having an open mind when exploring and a cautious mind when exploiting.

I'll update this page sporadically and not on a specific schedule.
It's meant to be light and fun for both me and you. 
It's highly unconventional to write in a stream of thought manner like this.
But heck, why not? For just this part of the website, enjoy some hot mess.

Here's what this page contains right now:
- [Seminar Participation](#1-seminar-participation)
- [Exploring the Lex Fridman Podcast](#2-exploring-the-lex-fridman-podcast)
- [Exploring the Stata Journal](#3-exploring-the-stata-journal)

## 1 Seminar Participation ##
Have you ever wondered exactly how many presentations _I_ have attended since starting my PhD?
I sure have. And I've done something about it.

Last updated 2023-11–19: Here are some plots for the seminars and brown bags that I have attended.

<img src = "/assets/img/blog-seminar-participation/Cumulative-number-of-seminars-and-brown-bags-by-Month-year.png" width ="100%"/>
<img src = "/assets/img/blog-seminar-participation/Total-number-of-seminars-per-year.png" width ="100%"/>
<img src = "/assets/img/blog-seminar-participation/Total-number-of-seminars-per-academic-year.png" width ="100%"/>
<img src = "/assets/img/blog-seminar-participation/Total-number-of-seminars-and-brown-bags-pie-chart.png" width ="100%"/>
<img src = "/assets/img/blog-seminar-participation/Total-number-of-seminars-and-brown-bags-per-host-institution-pie-chart.png" width ="100%"/>
<img src = "/assets/img/blog-seminar-participation/Total-number-of-seminars-and-brown-bags-per-academic-position.png" width ="100%"/>
<img src = "/assets/img/blog-seminar-participation/Total-number-of-own-presentations-per-academic-year.png" width ="100%"/>

[Back to top](#guiding-principles)

## 2 Exploring the Lex Fridman Podcast ##
I love the Lex Fridman podcast. So I did some digging. The following is based on data from YouTube.

First, the podcast has had a lot of views. Over 400 million views.
<img src = "/assets/img/blog-exploring-LFP/cum_views_over_time.png" width ="100%"/>

Lex averages 5 days between episodes and has done so consistently for a few years now.
<img src = "/assets/img/blog-exploring-LFP/days_since_last_publish.png" width ="100%"/>

To get a feeling for what the podcast is about, let's look at its guests.
First, we have the most recurring interviewees. You can form your own opinion about them,
but I find the breadth of their fields fascinating. Physcists, programmers, philosophers, fighters, podcasters, teachers, and more!
<img src = "/assets/img/blog-exploring-LFP/guests_count.png" width ="100%"/>

The podcast's most viewed episodes (with over 12 million for first place).
<img src = "/assets/img/blog-exploring-LFP/most_viewed_episodes.png" width ="100%"/>

So what do they discuss on these podcasts? Based off of the titles, here's the top 20 words and bigrams.
Basically, a lot of AI, physics, human nature, and our future.
<img src = "/assets/img/blog-exploring-LFP/top_20_words.png" width ="100%"/>
<img src = "/assets/img/blog-exploring-LFP/top_20_bigrams.png" width ="100%"/>

Beyond the title, they must talk about several different stuff in the actual interview.
For the episodes with timestamps available, we can see the average number of topics per episode is around 18.
<img src = "/assets/img/blog-exploring-LFP/timestamps_count.png" width ="100%"/>

The length of the episode correlates positively with the length of the episode.
My favorite outlier is Balaji Srinivasan's episode, at an impressive 7 hours 47 minutes and 52 seconds.
<img src = "/assets/img/blog-exploring-LFP/regplot_timestamps_vs_pod_length.png" width ="100%"/>

<img src = "/assets/img/blog-exploring-LFP/barplot_timestamps_vs_pod_length.png" width ="100%"/>


[Back to top](#guiding-principles), [Previous topic](#1-seminar-participation) 


## 3 Exploring the Stata Journal
This journal will always be special to me because it has my first peer-reviewed paper.
As an homage, I scraped data on the article title, volume, issue, and author names.

Since their start in 2001, they have published 23 volumes containing 1251 articles and 1081 unique authors.
<img src = "/assets/img/blog-exploring-SJ/count_articles_per_volume.png" width ="100%"/>

Some authors collaborate together several times, which gives us 738 unique author combinations.
Top authors (counting their appearance as single authors and co-authors) yields:
<img src = "/assets/img/blog-exploring-SJ/top_authors.png" width ="100%"/>

Looking only at co-authorships, the top 20 author collaborations are:
<img src = "/assets/img/blog-exploring-SJ/top_author_collaborations.png" width ="100%"/>

Co-authorship is also quite common and has become more common over time
<img src = "/assets/img/blog-exploring-SJ/count_authors_per_article.png" width ="100%"/>
<img src = "/assets/img/blog-exploring-SJ/avg_authors_per_article_per_volume.png" width ="100%"/>

Finally, we can create cool collaboration networks like this one, based on code from <a href="https://www.kaggle.com/code/bkoseoglu/co-authorship-network-analysis/notebook"> here</a>.
<iframe src = "/assets/img/blog-exploring-SJ/collaboration_network.html" width ="100%" height = "300"></iframe>

We can also explore the topics using data from Web of Science and visualize it using VOSviewer
(this was until volume 22 and I might update soon, but not today)
For example, keyword co-occurences look like this:
<img src = "/assets/img/blog-exploring-SJ/keywords_occurances.png" width ="100%"/>

Using words from the abstracts, we see some clear clusters.
There's a programming cluster (green-purple, bottom-right), statistics cluster (green-yellow, top-left),
economics/econometrics cluster (yellow, bottom-left).
<img src = "/assets/img/blog-exploring-SJ/terms_occurances.png" width ="100%"/>
<img src = "/assets/img/blog-exploring-SJ/statistics_cluster.png" width ="100%"/>
<img src = "/assets/img/blog-exploring-SJ/economics_cluster.png" width ="100%"/>
<img src = "/assets/img/blog-exploring-SJ/programming_cluster.png" width ="100%"/>


[Back to top](#guiding-principles), [Previous topic](#2-exploring-the-lex-fridman-podcast) 