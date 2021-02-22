# Kawarith
an Arabic Twitter Corpus for Crisis Events

## Data Description
The Kawarith corpus comprises Arabic tweets from 22 crisis events that occurred between October 2018 and September 2020. Kawarith focuses on high- to medium-risk events that are most likely to trigger substantial Twitter activity and encompasses a wide range of hazard types, including floods, shootings, bombing, wildfires, pandemics, sandstorms and explosions.

## Repository Structure
1. Unlabelled Corpus: 
A large-scale crisis-related Arabic Twitter corpus of 1,658,795 unique tweets from 22 emergency events. <br>
Each folder contains tweet IDs collected during a specific crisis along with query terms and collection dates.

2. Labelled Data: 
A gold-standard dataset comprising ~12k unique tweets from seven events: the Jordan floods, Kuwait floods-18, Hafr Albatin floods-19, the Cairo bombing, the Dragon storms, the Beirut explosion and Covid-19. Apart from Covid-19, which was labelled by relatedness to the event, tweets were annotated in terms of information type in a multi-label schem. A copy of the annotation instructions (translated to English) has been uploaded.<br>
There is a folder for each event containing the following:<br>
a) tweet IDs and their assigned labels.<br>
b) tweet IDs for train and test sets.<br>


## Rehydrating Tweets (for research purposes)
To comply with [Twitter’s policies](https://developer.twitter.com/en/developer-terms/agreement-and-policy), only tweet IDs are published. You can retrieve complete Tweets Objects using hydration tools such as [Twarc](https://github.com/DocNow/twarc) or [Hydrator](https://github.com/DocNow/hydrator).

## How to cite this resources:
```
Alharbi, Alaa, and Mark Lee. "Kawarith: an Arabic Twitter Corpus for Crisis Events." Proceedings of the Sixth Arabic Natural Language Processing Workshop. 2021
```

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
