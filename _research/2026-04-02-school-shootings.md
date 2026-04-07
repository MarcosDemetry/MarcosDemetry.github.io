---
layout: page
thumbnail-img: /assets/img/research-school-shootings/Demetry-school-shootings-SOLE-JOLE-2026-04-07-1318.pdf
title: "Flight from Fights: School Shootings, Mobility and Neighborhood Sorting"
tags: [ongoing]
---

## Congrats! You've seen my poster at SOLE-JOLE 2026 ##

Contents in this page:
- [Quick Recap](#1-quick-recap)
- [The Landscape of School Shootings](#2-the-landscape-of-school-shootings)
- [Main Result: Enrollment Drops](#3-main-result-enrollment-drops)
- [Who Leaves? Composition Effects](#4-who-leaves-composition-effects)
- [Between-School Segregation Rises](#5-between-school-segregation-rises)
- [Heterogeneity Analyses](#6-heterogeneity-analyses)
- [Robustness Checks](#7-robustness-checks)
- [Let's Stay in Touch!](#8-lets-stay-in-touch)

---

## 1. Quick Recap ##

Wandered away from the poster and need a quick refresher?

- **What's this about?** I study how school shootings affect total enrollment, and whether it is the socioeconomically better-off students that exit the affected schools and sort into neighboring schools with other well-off students leading to greater between-school socioeconomic segregation.
- **How did I estimate this?** I use a staggered Difference-in-Differences design, exploiting the exogenous timing of ~2,300 school shootings across the United States between 1990 and 2022. Schools within 500 meters of a shooting serve as the treated group; never- and not-yet-treated schools are the control group. I use the [Callaway and Sant'Anna (2021)](https://doi.org/10.1016/j.jeconometrics.2020.12.001) estimator to obtain group-time average treatment effects robust to treatment effect heterogeneity.
- **What did I find?** School shootings reduce enrollment by an average of **4%** or about 25 students in a typical shooting school. Fatal shootings eventually shrink schools by **10%**. Non-poor families exit faster than poor ones, and between-school socioeconomic segregation persistently increases within affected districts.
- **Do I trust these results?** Yes. Effects are stable across treatment radii from 250m to 5km, robust to alternative estimators, and pass a randomization-inference placebo test.
Schools that close entirely are dropped from the estimation sample, so the estimated effects are a *lower bound*.
- **Main Contribution** Studying the effects of school shooting explicitely on between-school socioeconomic segregation

---

## 2. The Landscape of School Shootings ##

School shootings have become an increasingly salient feature of American public life. I use the [K-12 School Shooting Database](https://k12ssdb.org) (Riedman, 2024), which defines a school shooting as any incident in which a gun is brandished, shots are fired, or bullets strike school property, regardless of time of day or day of year. This broad definition captures the full range of incidents that families may plausibly respond to.

<img src="/assets/img/research-school-shootings/shootings_fatal_nonfatal.png" alt="School shootings by fatality, 1966–2022" width="100%"/>

The number of shootings has risen sharply since the early 2000s, with roughly 300 incidents in 2023 alone, approximately 50 of which were fatal. Between 1990 and 2022, around **2,300 schools** experienced at least one shooting.

<img src="/assets/img/research-school-shootings/shootings_map.png" alt="Geographic distribution of school shootings, 1990–2022" width="100%"/>

Shootings are widespread across the United States, concentrated in urban and suburban areas.

**Identifying the treatment.** I classify a school as treated if it lies within 500 meters of a shooting identified in the K-12 School Shootings Database. 
By using a spatial join, I capture multiple schools that may be affected by the same shooting.
The figure below illustrates this for Marjory Stoneman Douglas High School in Parkland, Florida (February 14, 2018).

<img src="/assets/img/research-school-shootings/treatment_buffer_parkland.png" alt="Treatment buffer illustration: Marjory Stoneman Douglas H.S., Parkland FL, 2018" width="100%"/>

The gruesome mass shooting at the Marjory Stoneman Douglas High School (serving grades 9--12) occurred in proximity to the Westglades Middle School (serving grades 6--8).
The perpetrator of this shooting was himself enrolled in this nearby middle school in the years prior to carrying out this attack.
In the figure above, a map with increasing radius of treatment assignment shows that students of this middle school would not have been considered treated had the spatial join only captured school units using a merge on name or a spatial merge of within 250meters of a school shooting.
Within 500 meters, both the focal high school and the middle school across the yard are considered affected.
A three minute drive away lays the Country Hills Elementary School, captured by the 1km radius in the map. Testimony from a school police officer, Dave Dittman, jumping into action to help protect the students at Marjory Stoneman Douglas High School,
shows how resources and individuals in the nearby community are affected.

---

## 3. Main Result: Enrollment Drops ##

<img src="/assets/img/research-school-shootings/main_enrollment_result.png" alt="Effect on log enrollment: all shootings vs. fatal shootings" width="100%"/>

The dynamic event-study plot above shows the Average Treatment Effect on the Treated (ATT) for all school shootings. Pre-trends are flat, supporting the parallel trends assumption. After a shooting:

- **All shootings:** enrollment falls by roughly **4%** on average — equivalent to about 25 students in a school with the median enrollment of 632.


The equivalent exercise for **Fatal shootings** gives an overall ATT reaching approximately **–10%** at longer horizons.
Putting these estimates in perspective, enrollment following the biggest mass shootings in the U.S.
declined by 5\%, 12\%, 1\% and 7\% for the Columbine (1999), Sandy Hook (2012), Parkland (2018), and Santa Fe (2018) shootings.

The pattern is consistent with **families voting with their feet**: after a shooting, the affected school's enrollment shrinks and continues to shrink in subsequent years as family decisions compound.

---

## 4. Who Leaves? Composition Effects ##

Is it random which students leave? The share of **Free or Reduced Lunch Eligible (FRLE)** students---a standard proxy for household poverty in U.S. school data---answers this question.

<img src="/assets/img/research-school-shootings/frle_share_result.png" alt="Effect on share of free/reduced lunch eligible students" width="100%"/>

The share of FRLE students *rises* after a shooting. This means the students who remain are disproportionately from lower-income households, while non-poor families are the ones leaving. This non-random exit sets the stage for rising between-school socioeconomic segregation within the district.

**Does this school-level composition shift carry through to the district level?** Using three district-level poverty proxies — share of Free Lunch recipients (household income ≤130% of the federal poverty level), share of Reduced Lunch recipients (130–185% FPL), and their combined share, I estimate the overall ATT for each.

<img src="/assets/img/research-school-shootings/district_lunch_overall_att.png" alt="District-level overall ATT on free and reduced lunch shares" width="100%"/>

The results reveal a nuanced pattern: the share of **Reduced Lunch** recipients *rises* in shooting districts, while the share of **Free Lunch** recipients *falls*. The combined free-or-reduced share shows a small negative effect. The dynamic effects are modest throughout the event window:

<img src="/assets/img/research-school-shootings/district_lunch_combined.png" alt="Dynamic ATT on district-level free and reduced lunch shares" width="100%"/>

This divergence between the two groups is informative. Free lunch recipients are the poorest households (≤130% FPL); reduced lunch recipients are somewhat better-off poor households (130–185% FPL). The pattern suggests that the very poorest families tend to *stay* — they have the fewest exit options, while moderately low-income families are more likely to leave and are partly replaced by slightly higher-income families moving into the district. The net result is a subtle upward shift in the district poverty distribution, consistent with the "last-resort" nature of affected schools for the most disadvantaged.

---

## 5. Between-School Segregation Rises ##

If non-poor families leave shooting schools and re-enroll their children at other schools within the same district, we would expect between-school socioeconomic segregation to increase. That is exactly what I find.

<img src="/assets/img/research-school-shootings/segregation_exposure_index.png" alt="Effect on between-school exposure index (free lunch vs. non-free lunch)" width="100%"/>

The outcome here is a **between-school exposure index** measuring the probability that a randomly chosen schoolmate of a free-lunch student is also a free-lunch student where higher values indicate more sorting. After a shooting, the index rises modestly but persistently, consistent with non-poor families sorting into other (higher-status) schools elsewhere in the district.

The effect is not large in absolute terms but is meaningful in the context of an already-stratified U.S. public school system. And because shootings are frequent and cumulative, the aggregate effect on district-level segregation may be substantial. 
Segregation is a multifaceted phenomenon, and one would need to investigate changes in peer-group composition *within-school* as well as between-districts and between-counties. Ideally, we would have data to identify which students attend which grade and classroom, and follow their mobility across schools regardless of where they end up.

A further complication is that I can only observe public school data, to the extent that students leave the public school system entirely, we may see drops in enrollment that are not accompanied by any sorting *within the public school system*.

---

## 6. Heterogeneity Analyses ##

The average treatment effect masks important variation. Three dimensions of heterogeneity are particularly informative.

### Open Enrollment Laws ###

Do states that allow families to freely choose any school within or across district boundaries show larger enrollment declines after shootings? 

<img src="/assets/img/research-school-shootings/het_open_enrollment_att.png" alt="Overall ATT by open enrollment policy type" width="100%"/>

Permitting students to switch schools within the same school district results in a larger negative effect on enrollment than when that switching is not permitted. However, and rather paradoxically, in states where switching schools *between* districts is not permitted, we find a larger negative effect on enrollment than where that type of switch is permitted. One possible explanation for this is that states where switching schools across district lines is not permitted, there are other institutional factors that make families more mobile in relocating residentially. In fact, with the exception of Florida---9 of the 10 most affected states have strict interdistrict open enrollment rules. Thus, it is completely logical that we find the greatest drop in enrollment in the sample of states that are most affected.

<details>
  <summary>Event-study plots by open enrollment type</summary>
  <p>
    <strong>Within-district open enrollment (intradistrict):</strong>
  </p>
  <img src="/assets/img/research-school-shootings/het_intradistrict_oe.png" alt="Event-study by within-district open enrollment" width="100%"/>
  <p>
    <strong>Between-district open enrollment (interdistrict):</strong>
  </p>
  <img src="/assets/img/research-school-shootings/het_interdistrict_oe.png" alt="Event-study by between-district open enrollment" width="100%"/>
</details>

**Policy implication:** There is a genuine **trade-off between school choice and integration**. Open enrollment policies expand educational opportunity for families who can act on them, but they also allow non-poor families to exit schools hit by violence faster and more completely, leaving behind a poorer, more segregated student body.

### Background County Violence: The "Last Straw" ###

Not all shootings happen in the same neighborhood context. I split the sample by quartile of pre-shooting county homicide rates (from the FBI's Supplementary Homicide Reports).

<img src="/assets/img/research-school-shootings/het_county_violence_att.png" alt="Overall ATT by county homicide rate quartile" width="100%"/>

Schools in the **highest-violence counties (Q4)** see the largest enrollment drops — close to **–8%** on average. Schools in low- and medium-violence counties see effects near zero.

<details>
  <summary>Dynamic treatment effects by county violence quartile</summary>
  <img src="/assets/img/research-school-shootings/het_county_violence_dynamic.png" alt="Event-study by county violence quartile" width="100%"/>
  <p>
    In the most violent counties, effects emerge immediately at year 0 and deepen over time, reaching approximately –8% to –10% at longer horizons. In lower-violence counties, the confidence intervals consistently include zero throughout the event window.
  </p>
</details>

**Interpretation:** In already-violent neighborhoods, families may be close to their tolerance threshold. A school shooting becomes the "last straw" that tips a marginal family into leaving. In peaceful communities, the same event is more of a shock but not necessarily a reason to abandon an otherwise well-regarded school. There is not enough data in the lowest quartile to estimate the effects for the Q1 sample in isolation.

### Number of Same-Level Schools in the District ###

How many realistic alternatives does a family have? The number of same-level schools in the district (primary, middle, high) determines whether exit is feasible.
For example, if a shooting happens at a high school in a district with only one high school, mechanically, there are no outside options for students who wish to switch schools but remain in the same school district.

<img src="/assets/img/research-school-shootings/het_nschool_att.png" alt="Overall ATT by number of same-level schools in district" width="100%"/>

These results show a nuanced picture of the effects.
First, primary-schools often experience greater enrollment drops than high-schools. This is consistent with the fact that most shootings occur in high-schools, but that those those that occur in elementary (primary + middle) schools are deadlier. Second, most effects are more precisely estimated for larger school districts. This is in line with shootings occuring in primarily urban areas. Finally, counterintuitively, we find some positive effects on enrollment in high-schools in mid-size districts. 
These are the exception rather than the rule, but they do highlight the complex nature of the effects of shootings on mobility.

---

## 7. Robustness Checks ##

### Is the 500m Radius the Right Choice? ###

<img src="/assets/img/research-school-shootings/radius_att.png" alt="Overall ATT by treatment radius, 250m to 50km" width="100%"/>

The overall ATT is remarkably stable between **250m and 5km** — ranging from about –4% to –5% across all specifications. At 10km the effect attenuates; at 50km it *reverses* to positive. This reversal is exactly what we would expect from a reallocation story: schools far from the shooting *receive* the displaced students, pushing their own enrollment up.

A 50km radius is equivalent to (1) Dallas to Fort Worth, Texas, (2) Philadelphia to Trent, New Jersey or (3) San Francisco to San Jose, California. Putting it in these terms clarifies just how plausible it is to relocate following a shooting at a loved one's school.

This radius pattern is itself a robustness check: the spatial gradient of effects, with the sharpest decline at the treated school and positive spillovers at very large distances, is consistent with deliberate sorting by families rather than a generic shock to the area.

<details>
  <summary>Dynamic treatment effects by radius</summary>
  <img src="/assets/img/research-school-shootings/radius_event_study.png" alt="Event-study by treatment radius, 250m to 50km" width="100%"/>
  <p>The event-study confirms that the pattern holds across the full post-shooting horizon and not just on average. At close radii (250m–5km) the decline emerges in the shooting year and deepens over time. At 50km, the trajectory turns positive after a few years, tracing the gradual absorption of displaced students by distant schools.
  </p>
</details>

### School Closures: A Lower Bound ###

<img src="/assets/img/research-school-shootings/school_closure.png" alt="School closure rates following a shooting" width="100%"/>

Not all schools survive a shooting. Approximately **1 in 66 shooting schools close within five years** which is a closure rate roughly double that of comparable untreated schools. Once a school closes, it disappears from the sample.

This matters for interpretation: the enrollment estimates are computed only on schools that remain open. Schools that close entirely — presumably those with the most severe enrollment declines — are excluded. The **true average effect of a shooting on enrollment is therefore larger** than the –4% we estimate. Our main result is a lower bound.

---

## 8. Conclusion ##

* School shootings affect **total enrollment negatively**
* A greater share of **remaining students** at the affected school are **poorer** students
* Following this outflow of non-poor students, I find an **increase in socioeconomic segregation** between schools within the affected district
* This presents a **trade-off** between increased **school choice** and **socioeconomic diversity** and integration at schools

---

## Let's Stay in Touch! ##

I'm glad you've made it this far and thanks for your interest in my work!

If you'd like to discuss the paper, share related findings, or just say hello, let's **grab a coffee** (we'll exchange contact details or reach out here <a href="mailto:marcos.demetry@lnu.se?subject=SOLE-JOLE 2026: grab a coffee! &body=Hi Marcos, great poster and blog post! Let's grab a coffee during this conference. E-mail me back and we'll set something up. (Feel free to add your actual message below)">marcos.demetry@lnu.se</a>).



I'm broadly interested in **urban economics and segregation** (what drives the sorting of people across neighborhoods and schools?) and **crime economics** (how does exposure to crime shape economic decisions and outcomes?). School shootings sit at the intersection: they are a form of crime exposure that directly affects one of the most consequential economic decisions a family makes — where to educate their children.

---

<a href="/research">Back to Research</a>
