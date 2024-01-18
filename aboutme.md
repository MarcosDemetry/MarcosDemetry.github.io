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
- [Exploring my Netflix](#4-exploring-my-netflix)
- [Exploring my library](#5-exploring-my-library)
- [Exploring ASSA 2024](#6-exploring-assa-2024)

## 1 Seminar Participation ##
Have you ever wondered exactly how many presentations _I_ have attended since starting my PhD?
I sure have. And I've done something about it.

Last updated 2023-12–09: Here are some plots for the seminars and brown bags that I have attended.

In the figure below, can you spot when my exchange semester began? (Of course you can, it's a rhetorical question.)
<img src = "/assets/img/blog-seminar-participation/Cumulative-number-of-seminars-and-brown-bags-by-Month-year.png" width ="100%"/>

Breaking down my attendance by fiscal and academic year, respectively, gives the following.
<img src = "/assets/img/blog-seminar-participation/Total-number-of-seminars-per-year.png" width ="100%"/>
<img src = "/assets/img/blog-seminar-participation/Total-number-of-seminars-per-academic-year.png" width ="100%"/>

Here's my favorite figure in this section: Heatmap of day-of-week and month-year. In the fall of 2021, I was still an RA at the Swedish Institute for Social Research, while doing my first semester of the PhD; they had seminars on Tuesdays and Mondays, while my department had seminars on Thursdays. Due to coursework (and the pandemic), I didn't attend many seminars that first semester. From my second semester onwards, I attended our usual Thursday seminar, 2–3 times a month. Beginning in February of 2023, we changed the seminar day to Wednesdays. Finally, Beginning in September of 2023, I attended the IRLE seminars every Wednesday in Berkeley, plus a bunch of other seminars spread out throughout the week!
<img src = "/assets/img/blog-seminar-participation/Heatmap-DOW-month-year.png" width ="100%"/>
<img src = "/assets/img/blog-seminar-participation/Total-number-of-seminars-and-brown-bags-pie-chart.png" width ="100%"/>
<img src = "/assets/img/blog-seminar-participation/Total-number-of-seminars-and-brown-bags-per-host-institution-pie-chart.png" width ="100%"/>

Not surprising, most presentations are given by PhD students or APs. 
<img src = "/assets/img/blog-seminar-participation/Total-number-of-seminars-and-brown-bags-per-academic-position.png" width ="100%"/>

I've had the honor of presenting a few times myself:
<img src = "/assets/img/blog-seminar-participation/Total-number-of-own-presentations-per-academic-year.png" width ="100%"/>

Econ gets a lot of crap for its gender imbalance. And it has a highly skewed gender distribution. This is looking at presenters' genders, but the share of men would be even higher if I counted per presentation instead of per presenter (since I've seen some people present multiple times, and it's mostly been men).
<img src = "/assets/img/blog-seminar-participation/Unique-presenters-by-gender.png" width ="100%"/>

If you are like me<sup>*</sup>, you've gone around wondering the following:
Which is more popular among economists, Google Sites or Github Pages?
I don't have a definitive answer, but use this figure to argue about it at the pub.<sup>&dagger;</sup>
<img src = "/assets/img/blog-seminar-participation/Unique-presenters-by-personal-website.png" width ="100%"/>


<sup>*</sup> Congrats! That's a big win.
<sup>&dagger;</sup> How representative is my sample to the sample of all economists? Squarespace + Google Domains = True. Google Sites has a relative majority, but is that all that counts to declare victory?
I will start campaigning to get people with no personal websites to create a Github Pages.

Uploaded 2023–11–20; Last updated 2024–12–09

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

Uploaded 2023–11–20; Last updated 2023–11–20

[Back to top](#guiding-principles), [Previous topic](#1-seminar-participation) 


## 3 Exploring the Stata Journal
This journal will always be special to me because it has my first peer-reviewed paper.
As an homage, I scraped data on the article title, volume, issue, and author names.

Since their start in 2001, they have published 23 volumes containing 1251 articles and 1081 unique authors.
On average, there are 56 articles per volume (or 54 if we include the incomplete volumes 1 and 23).
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

Uploaded 2023–11–21; Last updated 2023–11–21

[Back to top](#guiding-principles), [Previous topic](#2-exploring-the-lex-fridman-podcast) 

## 4 Exploring my Netflix
Is there any greater sign of procras... being cultured than watching good TV?
If I'm not listening to music (which was 55.8k minutes so far in 2023) or watching podcasts on YouTube (like the trifecta Lex Fridman, Joe Rogan, Andrew Huberman, with a little Theo Von, Whitney Cummings, Neil DeGrasse Tyson, and Sean Carroll sprinkled on top), then I have a show or movie running in the background on Netflix.

In an attempt to make this truly beautifully unnecessary statistics, I give you a summary of my Netflix viewing activity.

Surprisingly, I played outside more in the beginning of the pandemic (March–July of 2020), than I did toward the end of that year.
I seem to be getting a cold in December–February of every year, so viewing times really shoot up during that period.
<img src = "/assets/img/blog-exploring-Netflix/time_spent_watching_netflix_by_month_year.png" width ="100%"/>

What have I watched the most? If I look at movies and series together (i.e. removing episode information from title), I get these excellent shows on my top 20.
And I'll throw in a little WordCloud while we're at it to capture a few more titles than the top 20.
<img src = "/assets/img/blog-exploring-Netflix/top_20_shows.png" width ="100%"/>
<img src = "/assets/img/blog-exploring-Netflix/wordcloud.png" width ="100%"/>

What's more interesting is seeing when I've watched these series. For the top 10, you see that I've rewatched Community at least 3 times, and likewise had 3–4 bursts of viewing B99. Arrested Development on the other hand is just always in my life. Every once in a while, I'll rewatch the first 3 episodes. For Narcos, I watched the 3 seasons as they came out, then jumped on the Narcos Mexico series as it came out as well (starting November 2018).
<img src = "/assets/img/blog-exploring-Netflix/top_10_viewing_activity.png" width ="100%"/>

If we instead let series episodes compete with movies, then this is what the top 20 looks like.
<img src = "/assets/img/blog-exploring-Netflix/top_20_titles.png" width ="100%"/>

For my top 30, a quick run using the [IMDB/Cinemagoer](https://cinemagoer.github.io) Python library, gives me the following
information on genres, ratings and release years.
<img src = "/assets/img/blog-exploring-Netflix/imdb_first_genre.png" width ="100%"/>
<img src = "/assets/img/blog-exploring-Netflix/imdb_rating_distribution.png" width ="100%"/>
<img src = "/assets/img/blog-exploring-Netflix/imdb_year.png" width ="100%"/>

One day, I may take these BUS seriously. Today is not that day.
In the words of Maximus Decimus Meridius, "Are you not entertained? Is this not why you are here?"

Uploaded 2023–12–01; Last updated 2023-12-01

[Back to top](#guiding-principles), [Previous topic](#3-exploring-the-stata-journal) 

## 5 Exploring my library
It's no secret that I love my personal library. And it keeps expanding much faster than I can keep up (or, ehm, justify). As of 2023–12–23, I have 493 books in my bookshelves at home that are also registered in my little database. There are at least 50 or so books that I still need to register. Of the registered books,
I've read 297 (or approximately 60%).

<img src = "/assets/img/blog-exploring-library/home-bookshelves.jpeg" width ="100%"/>
<img src = "/assets/img/blog-exploring-library/books_read_per_year_cumulative.png" width ="100%"/>

For most books, and especially after 2014, I also have an exact date read, and we could get this more granular plot.
<img src = "/assets/img/blog-exploring-library/books_read_per_day_cumulative.png" width ="100%"/>

A lot of books are read within a month. Some books take years. Of course, what this means is that I've started reading a book and put it a way for many months, then picked it up again. 
But this statistic is already very skewed, because I was a much more avid reader between 2014–2018, and would finish a book per 1.5 weeks on average. This is not super impressive compared to real avid readers, but life is not a competition. (At least I'm trying to convince myself of that)
<img src = "/assets/img/blog-exploring-library/days_to_finish_hist.png" width ="100%"/>

Most of what I own (and read) is non-fiction. I didn't have the guts to classify the bible and psalm books as either fiction or non-fiction, so they got their own category _spirituality_.
<img src = "/assets/img/blog-exploring-library/nonfiction_vs_other.png" width ="100%"/>

My most owned (and read) 15 genres are, to no ones surprise, as follows:
<img src = "/assets/img/blog-exploring-library/top15_genres.png" width ="100%"/>

For some books, I have also classified subgenres.
<img src = "/assets/img/blog-exploring-library/top20_subgenres.png" width ="100%"/>

My most read author is the one and only N.N.T. Then there's _STR_ which is a Swedish association for teaching driving. One or two textbook authors made their way in there as well.
<img src = "/assets/img/blog-exploring-library/top20_authors.png" width ="100%"/>

For most of the books that I've read, I added a rating from 1–5, with 5 being a gripping book
that I could not put away or that made me think differently about life, and the lower ratings are just awful books. Naturally, and thank God, I have no 1-star ratings (if it were that bad, I wouldn't have bought the book in the first place)! The 2-stars are the fallen angels, I bought them with the hopes of them being 4s and 5s, but they quickly made their way to a solid 2. The 3 stars are in actuality 2s but I either really like the author or the topic (despite my disliking of many details). 4 stars are all round great books.
I'd recommend them to folks. 
<img src = "/assets/img/blog-exploring-library/rating.png" width ="100%"/>

Finally, and least surprising, my books are on avg 300–350 pages long. The mean is of course heavily influenced by (1) the bible and (2) Swedish law book.
I wonder if book lengths have changed drastically over time? Only problem is: 11 years of data is not enough, my book purchases are not representative of "books" in general, year published does not equal my edition's year or the year I bought the book, and, lastly, I should get some rest and call it a day.
<img src = "/assets/img/blog-exploring-library/book_lengths_hist.png" width ="100%"/>


As usual, I love exploring my life with data! And it is beautifully flawed, skewed, and with non-random measurement errors, and all the rest.
One day, I'll merge all my datasets capturing different aspects of life on date, and it will be absolutely marvelous. Until then, take care and see you on the next BUS!

Uploaded 2023–12–21; Last updated 2023–12–21

[Back to top](#guiding-principles), [Previous topic](#4-exploring-my-netflix) 

## 6 Exploring ASSA 2024
Started off this fiscal year by attending the Allied Social Science Associations' (ASSA) annual meeting. 
This conference gathers around 70 associations and has poster sessions, over 1800 presentations, and events all concentrated in a period of three days. Coming back home from this conference, I was still overwhelmed with the sheer scale of it. So, I started exploring some data from the conference program as posted on their website (https://www.aeaweb.org/conference/2024/program)

First, the biggest association represented in ASSA, as measured by count of sessions hosted by this association is the American Economic Association (AEA). The (not so close) second largest association is AFA. The figure below shows the top 20 assocations.

<img src = "/assets/img/blog-exploring-ASSA2024/sessions_per_association_top20.png" width ="100%"/>

Each session has on average around 4 presentations.
<img src = "/assets/img/blog-exploring-ASSA2024/papers_per_session.png" width ="100%"/>

These papers had on average 2.5 authors per paper. There's quite 
<img src = "/assets/img/blog-exploring-ASSA2024/authors_per_paper.png" width ="100%"/>

Some researchers were a part of the author team for several papers or presentations—and they are:
<img src = "/assets/img/blog-exploring-ASSA2024/top_30_authors.png" width ="100%"/>

Researchers whose names are listed as authors to papers presented at the conference—where are they affiliated?
The top 30 institutes represented at the conference come as no surprise. Chicago, Stanford, Columbia, the Fed, MIT and UC Berkeley are on top. (I had to count the top 6, not top 3 or top 5, to include Berkeley...)
<img src = "/assets/img/blog-exploring-ASSA2024/top_30_affiliations.png" width ="100%"/>

So, which topics were discussed at the ASSA 2024? Based on JEL classifications for sessions, there was a lot of finance, followed by econometrics, and then specific topics (such as health, environmental, and demographic). The top 30 JEL codes are:
<img src = "/assets/img/blog-exploring-ASSA2024/sessions_per_jel_code_name_top30.png" width ="100%"/>

The ASSA was a great opportunity to explore different topics and meet new people. My personal preferences are for smaller conferences, because you actually get the chance to attend almost everything and to greet almost everybody. Here, of course, that is impossible.

Uploaded 2024–01–18; Last updated 2024–01–18

[Back to top](#guiding-principles), [Previous topic](#5-exploring-my-library) 