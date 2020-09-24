# Critique by Design
In this assignment, I use Stephen Few's Data Visualization Effectiveness Profile http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf as a framework for critiquing a data visualization.

Once I've competed my critique, I try my hand at wireframing a solution (or an improved version) of the visualization.

Next, I collect and document feedback about my wireframed redesign from others.

Last, I implement the feedback I've received and create a final visualization that will hopefully be an improvement on the original visualization.

## Step 1: Selecting a Visualization

#### Background Information
I've been fascinated to learn more over the past few months about Governor Tom Wolf's proposal that Pennsylvania join the Regional Greenhouse Gas Iniatitive (RGGI). RGGI is a cap-and-trade program that 10 states in the northeastern and mid-Atlantic United States already participate in.

Thus far, the results for these participating states seem signficant: Since 2005, participating states have (collectively) reduced carbon dioxide emissions emanating from the power sector by 45%. Additionally, revenue that comes from this program can then be dispersed through a reinvestment scheme in order to develop the clean and renewable energy sector, improve energy efficiency, create new jobs, and help states begin a transition to a greener economy.

RGGI has been heavily debated thus far in Pennsylvania. One argument is that because Pennsylvania is coal country, RGGI would harm the state's economy far more than any of the other states currently participating in the program. Economic models have been performed using the REMI (Regional Economic Models, Inc) framework, to forecast the impacts of joining RGGI on jobs, GDP, and personal income and to compare forecasts for three different reinvestment schemes: A Balanced Approach, Ratepayer Assistance, and General Fund.

The visualization I have chosen comes from a presentation created by the Pennsylvania Department of Environmental Protection. http://files.dep.state.pa.us/Air/AirQuality/AQPortalFiles/RGGI/FINAL%20RGGI%20101%20Webinar.pdf The presentation is called "Regional Greenhouse Gas Iniatitive: RGGI 101: How it Works and How it Benefits Pennsylvanians". The visualization I have selected comes from Slide 30 of this presentation, and is shown below: 

![image](https://user-images.githubusercontent.com/70919897/94050289-0e9f3480-fda4-11ea-9851-70b230017bbd.png)

## Step 2: Critique
**Usefulness.**
Unfortunately, this visualization isn't very useful. Part of the reason for this is that it is incomplete (as I will discuss next), but part of the reason is also because there is simply too much going on. There are far too many colors and too many categories to be able see some of the important takeaways from this visualization. One effect of including too many categories is that those categories with small corresponding values are nearly invisible because the bars are so thin. Thus, it is essentially useless to include them on their own.

**Completeness.**
Another key issue in this visualization is that there is simply missing information. The X and Y axes are not labelled, so while a well-informed reader might be able to guess and have a chance of interpretting correctly, this is an unnecessary risk. Likewise, the legend mislabels the categories as "Series," a default setting from Microsoft Excel, and does not reveal their true meaning.

**Perceptibility.**
This visualization also receives low ratings on perceptibility for my critique. There are a few reasons for this. First, the extreme use of color and cross-hatch pattern serves to distract and confuse the eye, rather than highlight the key trends the author is hoping to illustrate. Secondly, it is very hard to estimate the actual size of most of the bars because they are stacked (which means you have to subtract the one end of a bar from the other to understand the true amount) and because many of the bars are very small.

**Truthfulness.**
This visualization received a perfect score for my critique on truthfulness. This is because the authors intentionally decided to include **all** of the information they could, to a fault. In fact, it is this decision to be 100% transparent with the data and show the data in all of its granularity that harms the effectiveness of the visualization so much.

**Intuitiveness.**
For many of the same reasons listed above, this visualization receives a low rating for intuitiveness. Additionally, the dashed line may be easily misunderstood or misinterpretted, as was revealed to me when getting feedback on my redesign. Thus, the author could find a way to redesign the net gains or losses in a way that is less prone to misinterpretation.

**Aesthetics.**
The visualization receives low marks for aesthetics. The extreme use of color and cross-hatching is jarring to the eye and fails to draw the reader in.

**Engagement.**
This visualization might have somewhat higher marks for engagement than for aesthetics because if I reader were to spend a longer amount of time with this visualization, they would likely be able to start to identify different trends and notice more features. However, since the context of this visualization is a presentation, it is unlikely that readers will have the opportunity to spend much time doing this.

## Step 3: Wireframing
Before I began my wireframing redesigns, I asked myself what I thought the intended purpose of the visualization was. Knowing that the data was generated from economic modeling and that policymakers, citizens, lobbysits and more are likely to worry about the impact of RGGI on jobs, I ultimately decided the visualization was trying to communicate the following ideas:

1.) That while in the short term (next 1-2 years) there would be slight to modest job loss in the state as a result of direct RGGI impacts, positive job creation is actually expected within only a few years, with a total net creation of 30,000 jobs by 2030.

2.) Some audience members would likely want to know *how* RGGI is impacting jobs. Which RGGI impacts are most responsible for job gains? Which impacts are most responsible for job loss? Where the original visualization started to go wrong was that they were trying to show this data for each impact and each year, when I had a feeling that a 2030 snapshot would serve this objective better, as would lumping some of the smallest contributing impacts into one group.

For the wireframing, I focused only on solving the first objective (listed above). I tried to accomplish the goal of illustrating more job losses compared to job gains by aggregating all of the gains into one category and all of the losses into another. I changed the color schemes to green and pink, as they are found on opposite sides of the color wheel and would provide strong contrast. I thought that by coloring the losses as a dark shade of green and the gains as a brighter shade of green, the gains would stand out and highlight that they are larger, overall, than the losses. I also, obviously added labels to the axes and correct labels to the updated legend.

**While I tried a lot of different structures, chart types, color schemes, and formatting, the one graph shown below is the only graph that I sent to friends to feedback. I hadn't settled on some of the other options that I was playing around with, and I felt that some of the other graphs I was still working on weren't necessarily addressing the first and primary objective.**
![image](https://user-images.githubusercontent.com/70919897/94087030-af104b80-fdda-11ea-9c12-3e1944df1aa2.png)

**Below are some other visualizations that I put together during the wireframing process. Note: These are not refined visualizations whatsoever and were not sent to friends for review.**

![trytry](https://user-images.githubusercontent.com/70919897/94090971-07e4e180-fde5-11ea-97db-f197dea0eb58.jpg)

I considered using pie charts to show the proportions of RGGI impacts responsible for job losses or job gains. I found that there were too many categories that had a small contribution, like the original visualization.
![image](https://user-images.githubusercontent.com/70919897/94092195-1b457c00-fde8-11ea-9088-a4297d81bbd1.png)

I also considered using area charts rather than a line chart to show the net change in job numbers (gains or losses) from year to year.
![image](https://user-images.githubusercontent.com/70919897/94092242-3617f080-fde8-11ea-88f1-0cec52f5cec4.png)

I then modified the area chart to be a cumulative total of all job gains and losses, rather than only showing net change per year.
![image](https://user-images.githubusercontent.com/70919897/94092267-48922a00-fde8-11ea-80d1-68124f7fa33c.png)


## Step 4: Test the Solution

I asked four friends for feedback on the wireframe redesign. Here is what they said:

<div class="bg-blue-light mb-2">
Melissa C: "I think at first the graph is trying to show the number of jobs that will e created over the next 5 years and then a drop in the number of jobs. Then a steady increase over a decade or so. However, there is still a large number of jobs lost even though there are gains, so the net really doesn't represent the drop, it's more about the number of jobs being created vs the number of jobs lost. So it looks like a decline around 2025 but it is more that there are more jobs lost than gained."
</div>

<div class="bg-green-light mb-2">
Kelsey P: "The graph seems to be promoting the RGGI investments and showing that while there will be both job loss and creation, there will be more job creation over the course of the next several years."
</div>

<div class="bg-blue-light mb-2">
Mark C: "I see this chart as the reinvestments netting the 30k jobs over the next 10 years in a yearly focus. There will inherently be retirements, firings, and quitters thus the black bars decrease while new hires and jobs added increase to the total. The rolling sum per year of the pink should total 30k. A change that could help make 30k stand out more is to change the annual net total line to sum of total net. To show that despite decreases from tough conditions in 21 and 22, by 30 the pink line would rise to 30k would be very clear. The current magnitude of net per indivdual year doesn't seem to me to be as profound with the title as a rolling total would be."
</div>

<div class="bg-green-light mb-2">
Darren G: "I see that this is showing predicted job gains and losses, so if it is a prediction model I would want to know what assumptions are being made for that model. I also see that there is a very big dip at first, so I'd want to know what is causing that dip? It seems to be showing that there will be more job gains than losses, saying that these are the gains we will get if we implement this. So I'm also wondering how does this strategy mitigate net losses? I also think the losses should be red instead of dark black or green, and the dotted line should be red. Although I do think for this graph my initial attention was drawn to the gains because of the light green so I don't know if that was your intention."
</div>

**Takeaways from feedback:**
1.) There was still confusion around the dashed line representing net change in job numbers. My friends were focusing too much on whether this line was increasing or decreasing (which, to be fair, is important), but they seemed to be somewhat neglecting the idea that whether this line is in the negative zone or positive zone is also important. For example, one friend was concerned about the portion of the line that was decreasing from 2025 to 2026. The decreasing line over this range was concerning for my friend even though this line was on the positive portion of the graph. In other words, in both 2025 and 2026, more jobs were added than were lost. The *amount* of jobs added was decreasing, but jobs were still being added more than they were being lost. Because of this confusion, I ultimately decided to follow the advice of my friend Mark, who suggested using a cumulative total rather than the yearly net change. He also accurately identified that the cumulative total would better illustrate the "30,000 added jobs" alluded to in the title, which would enhance the effectiveness.

2.) I decided to change the color scheme based on the comments of my friends. While I was originally trying to avoid the "red, green" dichotomy, I think avoiding this was foolish of me because ultimately this is the color scheme that people are expecting when dealing with gains and losses.

3.) I decided to add two supplemental pie charts to show the total contributions (proportions) of types of RGGI impacts on total gains and losses. I felt that providing this snapshot from the year 2030 would provide just a little more context to some of my friends (and all future viewers of the data) who might be curious to know more about what is driving these gains and losses, without burdening them with too much detail.

## Step 5: Final Solution
![image](https://user-images.githubusercontent.com/70919897/94062212-62b21500-fdb4-11ea-811e-64c2b4a1bf4c.png)
![image](https://user-images.githubusercontent.com/70919897/94062375-95f4a400-fdb4-11ea-8447-99909bd9c694.png)
As you can see, I implemented the three pieces of feedback that were summarized in the previous step. I tried to use a cohesive color scheme between the three different graphs to try to express the idea that these are all connected as part of one larger story. I also made the choice to use the titles to communicate the key takeaways from each graph. I believe these titles connect back to the two objectives I described in the wireframing step. Those objectives were: 1.) to illustrate that RGGI will create many more jobs than it will lose them and 2.) to convey some information as to which impacts play the largest role in driving these gains and losses. To better accomplish objective #2, I also made the decision to group some of the RGGI impacts that had relatively small contributions to job change. For example, I grouped "Fossil Energy Efficiency" and "Electric Energy Efficiency" into one group: Energy Efficiency. I also made a group called "Other" from some smaller, miscellaneous impact categories.
