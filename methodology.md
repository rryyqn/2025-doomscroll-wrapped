# Methodology

This document explains how the statistics shown in the _2025 Doomscroll Wrapped_ were estimated.

The goal of these figure is plausibility, not precision. Data sources were used where possible. Appropriate assumptions were made for establishing context.


## Data sources
Usage ranges and behavioural patterns were derived from publicly available, non-proprietary sources, including:

- **Global and regional digital usage reports**  
Aggregate reports on social media and online video consumption, including average time spent, frequency of use, and platform penetration across age groups.

- **Time-use surveys and labour statistics**  
Government-published datasets detailing how adults allocate time across work, leisure, sleep, and daily activities, used to contextualise scrolling time within a full day.

- **Academic and industry research on attention and interface design**  
Studies examining session length, infinite scroll behaviour, memory recall, and the cognitive effects of continuous content consumption.

- **Surveys and qualitative research on social media habits**  
Self-reported user behaviour related to doomscrolling, loss of time awareness, and habitual phone use across different settings.

> [!NOTE]
> Sources were selected to establish realistic ranges and behavioural trends rather than precise individual measurements. Links to the exact reports used are listed in the footnotes of this document.


## Initial assumptions
- User represents an “average” adult's usage of social media and online video, representing a middle percentile of active users.
- “Doomscrolling” refers to passive consumption of short-form and feed-based content. Platforms considered include (but are not limited to): YouTube, TikTok, Instagram, X (formerly Twitter), and Snapchat.
- Daily usage is treated as distributed across multiple sessions, rather than a single continuous block, reflecting typical real-world behaviour.
- Where exact platform-specific metrics are unavailable, conservative estimates and assumptions were used to avoid exaggeration or shock-based framing.

<br />

---

<br />

## Calculations

### Total daily scrolling time

According to the Digital 2026 Global Overview Report[^1], the average weekly usage of social networks and video-centric platforms was 18 hours and 36 minutes per user. This is equivalent to 1116 minutes per week.

```
Daily average = Weekly average / 7
              = 1116 / 7
              ≈ 159.4286 minutes per day
```
This is equivalent to 2 hours and 39 minutes.

<br />

### Total annual scrolling time

```
Yearly average = Daily average * 365
               = 159.4286 * 365
               ≈ 58191.4286 minutes per year
```
This is equivalent to 40.4 days.

<br />

### Percentage of year scrolling

```
Percentage of year scrolling = Yearly average / total
                             = 40.4/365
                             ≈ 0.1107 or 11%
```

<br />

### Percentage of year free time
Calculation assumes a 24-hour timeframe of a full-time employee on a weekday. This assumption allows the use of data on the time spent on activies each day, as seen in the American Time Use Survey[^2].
All major activity categories include related travel time.

| Activity  | Hours Taken (per day) | Percentage of total time |
| ------------- | ------------- | ------------- |
| Personal care (including sleep)  | 9.80	| 40.8%  |
| Eating and drinking  | 1.24  | 5.2%  |
| Household activities  | 2.01  | 8.4%  |
| Work | 7.95 | 33.1%  |
| Leisure | 3.00 | 12.5%  |

<br />

### Percentage of free time spent scrolling
```
Percentage of free time spent scrolling = Percentage of year scrolling / Percentage of free time (leisure)
                                        = 11 / 12.5
                                        = 88%
```

<br />

### Ads funded this year
Given that the average user scrolled for 58191 this year, the estimate number of ads received can be calculated with the time interval between viewing ads while scrolling. This value will be assumed at 2.5 minutes, although this figure is not verified.
```
Ads funded = total time / ad time interval
           = 58191 / 2.5
           = 23276.4
           ≈ 23277
```

<br />
           
### Memory recall

A study found that infinite scroll design reduces memory recall of posts compared to scrolling with friction[^3], indicating that continous scrolling does not support content memory.

<br />


### Original intent
Surveys find many people lose track of time and have no idea how long or how much they’ve been scrolling, indicating a loss of original purpose[^4].

<br />


### Extent of usage
Experts describe doomscrolling as a mindless habit that becomes second nature, where people often pick up their phones and start scrolling without awareness[^5]. A survey found people doomscroll even in unexpected settings, like on the toilet, at weddings, school events and funerals[^4], demonstrating how habitual the behaviour has become.

<br />


[^1]: [Digital 2026 Global Overview Report](https://datareportal.com/reports/digital-2026-global-overview-report)
[^2]: [American Time Use Survey News Release](https://www.bls.gov/news.release/atus.htm)
[^3]: [Infinite scroll design reduces memory recall of posts](https://arxiv.org/abs/2407.18803)
[^4]: [Users report losing track of time and being unaware of time spent scrolling](https://www.thesun.co.uk/fabulous/35625246/brits-doomscroll-sex/)
[^5]: [Experts describe doomscrolling as a mindless habit that becomes second nature](https://health.clevelandclinic.org/everything-you-need-to-know-about-doomscrolling-and-how-to-avoid-it)
