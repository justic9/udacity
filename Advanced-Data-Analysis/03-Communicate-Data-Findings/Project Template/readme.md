# (Ford GoBike)
## by (Mahmoud Ali Elbasiony)


## Dataset

> 1. Dataset: [Ford GoBike](https://www.kaggle.com/keerthanamanoharan/ford-gobike-tripdata-2018)
2. Explore the data: Feel free to explore the jupyter notebook where the dataset is visually, and programatically explored. 
3. Document the story: organized findings convey a story to present to an audience.
4. Communicate the findings - a slide deck with my findings is prepared for a curious audience.

## Summary of Findings

This project is a win - win situation where a large number of people can benefit from this program:

- Environmentally friendly, budget friendly, and lifetsyle friendly.
- Subscribers (i.e. daily commuters) benefit from a health commuting choice.
- Customers (i.e. tourists, students, etc.) have a sustainable, yet flexible option for touring the city.
- Affordable and convenient transportation for the people of all socioeconomic classes.
- Renting a bike from theFord GoBike System is a fantastic (healthy and environmentally friendly) way of moving around in the city, both for enjoyment and work. 


## Key Insights for Presentation

There are two types of clients using the system: Subscribers and Customers. Subscribers are primarily daily commuters, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm. Customers are usually tourists or occassional riders who use the system mainly on weekends to explore the Bay Area. Age is also a factor within user type. Subscribers who fall in the age group between 31-40 years old are the most common age group to use the bike sharing system. The 31-40 years old also lead the spike which occurs across all age groups in October. Subscribers who fall in the 21-30 year old age group are the next most common age group to use the bike sharing system, and follow a similar trend at the 41-50 year olds. The oldest age group, the 51-70 years have the lowest bike rides in the two groups with very few rides (comparative to the entire dataset).

### Files
- readme.md - This Markdown file contains sections that you should fill out as you select your dataset, complete your exploration, and plan your explanatory analysis. 

- exploration_template.ipynb - This Jupyter Notebook contains section templates to help you organize your exploration, starting from loading in the data, working through univariate visualizations, and ending with bivariate and multivariate exploration. 

- slide_deck_template.ipynb - This Jupyter Notebook contains starter cells to help you organize your slide deck deliverable. These cells provide an example of how the slide deck should be organized, including pre-set slideshow settings.

To view the slide deck, you will need to use the expression (all one line):
jupyter nbconvert slide_deck_template.ipynb --to slides  --template output_toggle --post serve

- output_toggle.tpl - This template file can be used with nbconvert to export your slide deck. This adds extra functionality to the slide deck by hiding the code to start, only making it visible if the reader clicks on the output (which should mostly be visualizations in the case of this project).