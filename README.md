# Welcome to Jeffrey's Portfolio!
This is Jeffrey's public portfolio for the Telling Stories with Data class at CMU!

Link to live site: https://jeffreyscanlon.github.io/Portfolio/

# About me
I am a candidate for my Masters in Public Policy and Management, with a concentration in Data Analytics at Heinz College. My undergraduate field of study is biology. After graduating in 2014, I worked for five years in public schools as a middle school and high school science teacher. My first two years of teaching were in the Mississippi Delta as a Teach for America corps member, and my last three years of teaching were at a charter school in Nashville, Tennessee. As the quotation from Jonathan Zimmerman illustrates, the classroom is an intimate place. It was a daily honor and privilege to work with my students and to be given snapshots into their lives. It also, however, was awakening for me in many ways, as it made me far more aware of the extreme social, racial, and environmental inequities that exist in our country. Compelled by the injustices experienced by my students and their families, and by the increasing threat of climate change, I enrolled in my program at Heinz to gain the skills and education necessary to make a larger impact.

During my time at Heinz, I have had the opportunity to apply my new skills in many settings. During my first year, I worked with the education department at the Carnegie Museum of Natural History to perform a data analytics project for them. I was able to analyze patterns in the schools and groups that have historically visited their museum, helping them to strengthen existing relationships between the museum and the community. I also helped them evaluate the equity of their services, identifying schools and communities that historically were not being served by the museum, and helping them to identify potential barriers to access that the museum could work to reduce or eliminate. I have also been able to work with the Environmental Defense Fund and Covestro, a large chemical manufacturer, to improve the analytic capacity of their energy usage reporting dashboard and develop an environmental justice strategy for the company. I look forward to even more opportunities in this, my final year of the program.

# What I Hope to Learn
In this course, I am hoping to learn how to design professional visualizations that are appropriate for the audience and the context of the problem. I hope to develop my skills as a data interpreter--a liaison between multiple departments within an organization, able to communicate not only technical and stastistical concepts but also strategic business and organizational insights. I hope to be able to use data to convey ideas that are not only compelling, but also honest, holisitic, and novel.

# Portfolio
Here's where all of my nice data visualizations will go.

### Visualizing Government Debt
##### Total Debt, as a percentage of GDP.
This visualization is a simple bar chart to illustrate and compare the magnitude of debt for each country, expressed as a percentage of that Country's GDP. For values greater than 100%, the country's debt exceeds its GDP.

<iframe src="https://data.oecd.org/chart/65Fh" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/65Fh" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2017</a></iframe>

##### Sparklines: Debt-to-GDP Ratios Over Time
In this visualization, I've created a grid of line charts to show a snapshot or "sparkline" of how the debt-to-GDP ratio has changed for each country from 1995 to the present day. Each line chart has a dot representing the most recent data point on record for that country. The data used in this visualization comes from the Organization for Economic Cooperation and Development (OECD).

<div class="flourish-embed flourish-chart" data-src="visualisation/3749016" data-url="https://flo.uri.sh/visualisation/3749016/embed" aria-label="" data-width="90%"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

##### Boxplots: Distributions of Debt-to-GDP Ratios for 
Boxplots can be useful visualizations for understanding the distribution of values for a certain feature or attribute of interest. In this case, the attribute of interest is the Debt-to-GDP ratio. Boxplots make interpreting the distribution easy: to understand the spread of data, look from one tail to the other tail. The greater the distance between the ends of the tails, the greater the spread of data. In some cases, outliers are shown in the area beyond the tails. The box portion of the boxplot shows the interquartile range: the distance between the 25th and 7th percentile and all the values contained within that range. Finally, the line located somewhere between the 25th and 75th percentiles, though not necessarily directly in the middle, represents the median.

I have many critiques of this visualization that I would choose to improve if the Flourish editing environment allowed me to. First, there are many boxplots shown on this chart, and ideally the user would be able to filter this chart to only show a handful of countries of interest at a time. Unfortunately, the filtering feature provided by Flourish seems to only have the ability to filter so that one category (or country) is shown at a time, or to show all countries at once. Additionally, when displaying all countries at once, I would like to make sure that each country is represented with a label on the x-axis. However, there did not seem to be a feature to allow me to do this within the Flourish environment. Likewise, if I had the ability to, I would like to reorder the countries on the x-axis so that there was a little more purpose. For example, I might order them in a descending fashion from left to right based on the maximum Debt-to-GDP ratio for each country, or perhaps in a descending order based on the size of the range in the data. Additionally, I would add that there are a few things that could be done to the data itself to strengthen this visualization. First, countries could be grouped or assigned to groups based on similarities like population size, continent, or other economic factors. Then, boxplots could be made for each grouping. Additionally, boxplots work best when there is a large number of observations. Most of the countries in this dataset have about 25 observations and some have less than this. A larger number would be ideal.

<div class="flourish-embed flourish-scatter" data-src="visualisation/3749367" data-url="https://flo.uri.sh/visualisation/3749367/embed" aria-label="" data-width="25%"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

# Contact
Jeffrey Scanlon
(he/him/his)
LinkedIn: https://www.linkedin.com/in/jeff-scanlon3/
