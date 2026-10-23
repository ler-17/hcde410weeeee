#HCDE410
Files for HCDE410 - Assignment A1

Adapted from # cdsw-2020 https://wiki.communitydata.science/Seattle_open_data

# A1 — Working with Open Data

**Dataset:** Burke-Gilman Trail counter north of NE 70th St
**Source:** https://data.seattle.gov/resource/2z5v-ecg8.json?  (pulled 2026-10-05)
**License / terms of use:** Public Domain 

## Questions I asked
Q1. When is the trail busiest, and when is it quietest?
Q2. Do cyclists and pedestrians use the trail at different times of day?
Q3. Is there evidence people use the Burke-Gilman to commute?
Q4. Direction and flow. Are mornings mostly one direction and evenings the other?

All questions were answered using hourly cyclist and pedestrian traffic counts and count averages from the 
'Burke-Gilman Trail counter north of NE 70th St' dataset. 
Q1, Q2, and Q4 looked at cumulative counts for all days, Q4 focusing on North/South traffic distinctions, while Q3 
compared hourly traffic averages from individual days. 

## How to re-run
Open `A1.ipynb` and run all cells (needs `requests`, `pandas`, `matplotlib`).