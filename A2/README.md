#HCDE410
Files for HCDE410 - Assignment A1

Adapted from # cdsw-2020 https://wiki.communitydata.science/Seattle_open_data

# A2 — Bias in Data

**Dataset:** Wikipedia Talk Corpus
**Source:** (pulled 2026-10-20)
    **Project Overview:** https://meta.wikimedia.org/wiki/Research:Detox
    **Dataset Descriptions:** https://meta.wikimedia.org/wiki/Research:Detox/Data_Release 
    **Datasets:** https://figshare.com/projects/Wikipedia_Talk/16731 
    **Project GitHub:** https://github.com/ewulczyn/wiki-detox/blob/master/src/figshare/Wikipedia%20Talk%20Data%20-%20Getting%20Started.ipynb
    **Perspective API:** https://github.com/conversationai/perspectiveapi
**License / terms of use:** Apache License, Version 2.0 

## Questions I asked
Q1. What is the gender distribution of annotators?
Q2. What is the distribution of the annotators by first language?
Q3. What is the distribution of these annotators by age group?
Q4. what is the distribution of these annotators by education level?

Q5. Is there any missing demographic data? Where and how much?
Q6. How does do demographic analysis statistics change when duplicated data is included versus cleaned out?

Q7. In general, how do the demographics of annotators compare to those of English-speaking internet users overall? Why would it matter if the worker demographics don't match the demographics of the intended end users of the Perspective API?
Q8. What issues might arise if the Wikipedia Talk Corpus was used to train a machine learning-driven "hostile speech detector" that could be used on any website or social media platform?

Q9. What % of workers who labelled the toxicity dataset do we have demographic data for?
Q10. What % of the comments in the toxicity dataset were labelled by male vs. female-identified workers?
Q11. What % of the comments in the toxicity dataset were labelled by people for whom English is NOT their first language?
Q12. How might this dataset present a biased view of "toxicity"? How would you expect such biases to impact how the Perspective API performs?

## How to re-run
Open `hcde410-a2-ipynb` and run all cells (needs `requests`, `pandas`, `matplotlib`, `random`).
