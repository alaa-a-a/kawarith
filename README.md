# Kawarith
an Arabic Twitter Corpus for Crisis Events

## Data Description
The Kawarith corpus comprises Arabic tweets from 22 crisis events that occurred between October 2018 and September 2020. Kawarith focuses on high- to medium-risk events that are most likely to trigger substantial Twitter activity and encompasses a wide range of hazard types, including floods, shootings, bombing, wildfires, pandemics, sandstorms and explosions.

## Repository Structure
1. Unlabelled Corpus: 
A large-scale crisis-related Arabic Twitter corpus of 1,658,795 unique tweets from 22 emergency events. Each text file contains tweet IDs collected during a specific crisis.

2. Labelled Data: 
A gold-standard dataset comprising ~12k unique tweets from seven events: the Jordan floods, Kuwait floods-18, Hafr Albatin floods-19, the Cairo bombing, the Dragon storms, the Beirut explosion and Covid-19. Apart from Covid-19, which was labelled by relatedness to the event, tweets were annotated in terms of information type in a multi-label schem. 
There is a folder for each event containing the following:<br>
a) tweet IDs and their assigned labels.<br>
b) list of the query terms and collection dates.<br>
c) tweet IDs for train and test sets.<br>
d) annotation instructions.

## Rehydrating Tweets (for research purposes)
To comply with [Twitter’s policies](https://developer.twitter.com/en/developer-terms/agreement-and-policy), only tweet IDs are published. You can retrieve complete Tweets Objects using hydration tools such as [Twarc](https://github.com/DocNow/twarc) or [Hydrator](https://github.com/DocNow/hydrator).

## How to cite this dataset:
```
BibTeX:
```
