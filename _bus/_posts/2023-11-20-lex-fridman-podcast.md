---
layout: page
title: Lex Fridman Podcast
date: 2023-11-20
tags: [data analysis]
collection: bus
---

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

Uploaded 2023–11–20; Last updated 2023–11–20

<a href="/BUS">Back to BUS</a>