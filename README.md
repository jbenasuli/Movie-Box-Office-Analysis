# Movie-Box-Office-Analysis

Analyzing box office performance for different types of films

**Authors**: Geoff Vogt, James Benasuli

## Overview

Microsoft has decided to create a new movie studio and we were charged with exploring what types of films are currently doing the best at the box office. This presentation reviews our findings and proposes actionable insights to decide what films to target.

## Data

IMDB:
Basic movie attributes including title, runtime and genre, and movie ratings
Producers, writers, actors and directors connected to each movie based on ID

The-Numbers:
Movie budgets export as CSV 
Provides production budget, domestic gross revenue and worldwide gross revenue

## Results

Finding #1
Production budget has a strong positive correlation with revenue. 
Client Implications:
The more money invested in a film, the more money will likely be made in gross revenue.
Very high returns will not be made unless a high investment is made.

![Production Budget vs  Revenue for All Films](https://user-images.githubusercontent.com/122178940/215126301-cf37650d-109f-4f7e-a1a0-fc577a497a0e.png)
![Production Budget vs  Revenue for High Earning Films](https://user-images.githubusercontent.com/122178940/215126336-a73c60df-a969-4d11-9a5f-37300ea47997.png)

Finding #2
Revenue index stays relatively constant regardless of production budget. 
‘Revenue index’ = revenue / budget
Client Implications:
Microsoft is a big company, so if return on investment is flat, it makes more sense to make bigger bets to maximize potential returns 
![Production Budget vs  Revenue Index for All Films](https://user-images.githubusercontent.com/122178940/215126592-fcfedfc7-bcb6-48b7-9e94-ecb20e63f4ae.png)
![Revenue Index Frequency for All Films](https://user-images.githubusercontent.com/122178940/215126668-5a0e1d2d-ce28-4c3b-9968-57cc58dd7322.png)
![Revenue Index Frequency for High Budget Films](https://user-images.githubusercontent.com/122178940/215126694-d6b2cf00-2d65-4969-a4e3-5c386e328b04.png)

Finding #3
Sci-Fi, Animation and Adventure movies have generated the most revenue on average for high-budget films compared to other genres. 
Client Implications:
Microsoft should be targeting Sci-Fi, Animation and Adventure movies to make. 

![Average Revenue by Genre for High Budget Films](https://user-images.githubusercontent.com/122178940/215126938-65fd71f0-ee3e-45eb-805c-cdc2b4b0dd87.png)
![Average Revenue Index by Genre for High Budget Films](https://user-images.githubusercontent.com/122178940/215126963-37cffeae-66b7-4d7c-a79c-af925b2502b7.png)

Finding #4
There are subset of directors that return highest average profitability 
Client Implications:
Sci-Fi: Gary Ross, J.A. Bayona, Colin Trevorrow
Adventure: Kyle Balda, Tim Miller, Eric Guillon
Animation: Kyle Balda, Eric Guillion and Yarrow Chenery

![Average Revenue Index for Top 3 Sci-Fi Directors](https://user-images.githubusercontent.com/122178940/215127536-2439ecea-00f0-4958-aa57-069640ce9950.png)
![Average Revenue Index for Top 3 Adventure Directors](https://user-images.githubusercontent.com/122178940/215127548-d001bc49-d25f-4f73-ab65-63e91c5784f2.png)
![Average Revenue Index for Top 3 Animation Directors](https://user-images.githubusercontent.com/122178940/215127580-a73b6bb0-3c62-4990-81a0-54edb009e306.png)

Finding #5
There are subset of producers that return highest average profitability 
Client Implications:
Sci-Fi: Belen Atienza, Patrick Crowley and Jon Kilik
Adventure: Janet Healy, Christopher Meledandri, and Wyck Godfrey 
Animation: Janet Healy, Christopher Meledandri, and John C. Donkin 
![Average Revenue Index for Top 3 Sci-Fi Producers](https://user-images.githubusercontent.com/122178940/215127668-b9f60a81-87df-4f63-b8a5-3616338ab832.png)
![Average Revenue Index for Top 3 Adventure Producers](https://user-images.githubusercontent.com/122178940/215127677-7b4005b0-57de-420b-874a-aaf9c9f06463.png)
![Average Revenue Index for Top 3 Animation Producers](https://user-images.githubusercontent.com/122178940/215127717-888e4e48-3e81-423d-a7f5-66087d18066c.png)

Finding #6
Sequels have a higher revenue index for high budget films on average.
Client Implications:
Where possible, Microsoft should be targeting sequels to make
![Average Revenue Index for High Budget Sequels and All Films](https://user-images.githubusercontent.com/122178940/215128037-231c063f-bd2f-4c50-bd39-d27197b8236d.png)


## Conclusions

Target high budget movies: Profitability index stays constant regardless of production budget. Bigger bets will allow for greater profits.
Target specific genres: Sci-Fi, Adventure and Animation make the most money of all high-budget films.
Target specific directors/producers: A subset of directors and producers are linked to strongest profitability for high budget films.
Target sequels: Sequels make more money for high-budget films on average.


***
Questions to consider:
* What would you recommend the business do as a result of this work?
* What are some reasons why your analysis might not fully solve the business problem?
* What else could you do in the future to improve this project?
***

## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](https://docs.google.com/presentation/d/18uSn4LZB1TvpaflMaJMC-TbkUVO7qaCuokMCPzJqjcs/edit#slide=id.g200cefc9537_0_27).


```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Notebook containing code to clean, wrangle, and vizualize our data
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── code
│   ├── __init__.py                     <- .py file that signals to python these folders contain packages
│   ├── visualizations.py               <- .py script to create finalized versions of visuals for project
│   ├── data_preparation.py             <- .py script used to pre-process and clean data
│   └── eda_notebook.ipynb              <- Notebook containing data exploration
├── data                                <- Both sourced externally and generated from code
└── imgs                                <- Both sourced externally and generated from code
```
