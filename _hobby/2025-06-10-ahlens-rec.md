---
layout: page
thumbnail-img: /assets/img/hobby-ahlens-rec/colors-frequency.png
title: Can I Analyze Fashion Taste?
subtitle: Analyzing recommendations from my fiancé for clothes from Åhlens
tags: [data, personal]
---

What does a PhD student do when given a gift card to go shopping? 
Ask for clothing recommendations and analyze the results!

The setting: I had a gift card of about €200 to the Swedish department store Åhlens. 
Given my non-existent sense of fashion, I asked my fiancé to give me clothing recommendations.
She sent me an Excel-file with each row containing a link to an item and a personal note on why she likes this piece.
Each sheet was for a different category of items (e.g. long sleeves, sweaters, etc.). You see why I love her, right?

So, I wrote a short Python script that for each item, scrapes the following info: brand name, item name, color, online storage status, warehouse storage status, price, rating, description, and color. This information wasn't available for each item. With the most available information, here's what I discovered about her recommendations for me.

Most clothing items were for around 1,000SEK (~€99). The price distribution is as below.
<img src = "/assets/img/hobby-ahlens-rec/price-distribution.png" width ="100%"/>

Most of her favorite items were long sleeves, followed by short sleeves, shirts and jackets.
<img src = "/assets/img/hobby-ahlens-rec/category-distribution.png" width ="100%"/>

If I were to look go around the department store myself, where would I start? I grouped the items by their brand name. The clear winner is 'John Henric'. 
<img src = "/assets/img/hobby-ahlens-rec/brand-distribution.png" width ="100%"/>

Now I know which brands she likes on me. The next question is, what colors should I go for?
I'm not a fan of complicated color names (what is _moonstruck_ or _mole mel_??). I took the fancy names and converted them to 'regular' colors. I took each color and plotted it in proportion to its frequency in the data. The results were clear, I should wear greens and browns.
<img src = "/assets/img/hobby-ahlens-rec/colors-frequency.png" width ="100%"/>

The perfect clothing item would be for a long sleeve from John Henric in either green or brown, and might cost around €90.

If I don't buy an expensive item, I could also optimize the use of the gift card by buying the most number of items while sticking to my budget. So I wrote a simple function that finds how many (and which) items I could buy within a given budget. For example, for 3000SEK or approx €300, I could have bought all of the following:
<img src = "/assets/img/hobby-ahlens-rec/budget-optimization.png" width ="100%"/>

Overall, shopping has become much more enjoyable now that I can run some code on it.

Uploaded 2025-06-10; Last updated 2025–06-10

<a href="/hobby">Back to Hobby</a>


