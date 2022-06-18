# CitiBike_Analysis
[Link to Dashboard]
https://public.tableau.com/app/profile/ryan.cabaong/viz/Citibike1_16473188208250/Dashboard1#1

CitiBike data between January and August 2019 for trends and visualize them using Tableau Public.

Before making visualizations, I fixed the trip_duration dataframe column to a standard time count (minutes) using Python Jupytor Notebook Pandas' library.
Additionally, I fixed the gender column from a number 0 (Male), 1 (Female), 2 (Other) to strings.

In this line graph visual shows a sharp rise of people who bike for on average four to six minutes.
Yellow (Male), Blue (Female), Red (Other)

Over 70k males bike for 10 minutes, Nearly 30k females bike for 10 minutes, and nearly 10k non-binary bike for 10 minutes.

![bike average times](https://user-images.githubusercontent.com/79386482/173476473-728e96b4-09e3-48c5-a290-60041911384a.PNG)

This 2D heatmap graph represents the amount of biking activity according to the time of day.
The most common time people bike is between 5pm to 6pm Thursdays averaging 40k individuals.
During the weekends when people have time to bike, the rates expand by nearly 40% throughout each hour.

![time of day averg](https://user-images.githubusercontent.com/79386482/173475334-fcd85e2d-948c-4173-809a-f32732b9a786.PNG)

Conjointly, this 2D heatmap represents the activity from individual users (Dark blue represents high activity and white represents low or no activity).

![bike id repair](https://user-images.githubusercontent.com/79386482/174419334-da5a03c6-3399-40c1-a464-9a917be4bad9.PNG)
