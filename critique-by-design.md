| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique by Design

## Step one: the visualization

_Include link to the original data visualization (or screenshot - make sure to correctly cite your sources, etc.).  Include paragraph or two on why you selected this particular data visualization.  For obvious reasons, the data visualization you select should come from a publicly accessible source._

[Orignal Image]![prb-image-export](https://github.com/user-attachments/assets/50b8dfeb-ccf1-4f3a-a020-c8c7f357f1a2)

Click on the Link for an interactive version.
[Source: https://www.prb.org/usdata/indicator/marriage-age-women/map/state/2015]

I chose this specific visualization because I thought the data was very interesting. I am currently 22 years old and a lot of my peers post-graduation are starting to settle down and get married. I on the other hand, am foucsing on furthering my education. This specific data set and graphic was very appealing to me because it shows the differences in median age of first marriage in the United States and which is condusive to an interesting comparison between different states. I also thought that the graphic was well created and thought out so it would be a challenging redesign exercise. Although the data almost made for a map, I wanted to see if I could do something else with it. 

## Step two: the critique

The visualization works well in terms of providing a general snapshot of marriage trends for women across the U.S. The clean and simple design makes it accessible and easy to interpret for most viewers. The one thing with this map is that it is not telling a story, we see the numbers of median age of first marriage, but this information is lacking depth of answering any questions. For example, why is there a difference in these medians. Likewise the visualization is just a little boring, its communicating information but not in a way thats making me want to know more about these stats.  What worked well were the map layout which is a familiar way for us to digest data and information, I also liked the interactive element of hovering over and seeing the individual information for every state. What didn't work was the colors of the gradient, I would've personally inverted the colors or chosen a more contrasting gradient to show the contrast between states. Likewise lack of context makes the map feel flat. What I would do differently is use different colors that would be in relation to the US median instead of breaking up the gradient based on the ages. That would add another layer to the data visualization story and when first looking at the chart would show how some states are much higher than the median age while others have a much lower age. This would also the states to be in comparison and add a dynamic level to the visualization instead of having just static statistics that are a little boring. Finally, there is always a problem, as we discussed in class, about using maps to visualize data. When using maps, it is hard to distinguish population, for example at a quick glance you can see that most of the states get married before the age of 28. However the median age of 28 tells a different story, the most populous states in the country, California, NY, and Florida all have a median marriage age of >28, but since most of the Midwest, the largest region, of the United States is rural, it doesn't seem as such. Therefore, this map is not telling the whole story due to the nature of map visualizations not accounting for population. Two changes I would make is 1.) Add a more contrasting color palette to make state differences easier to perceive. 2.) Maybe use a time series line graph to show how the median marriage age changes over time. I could divide the country into regions and observe the data in that manner. 

## Step three: Sketch a solution

[Sketch][<img width="469" alt="Screen Shot 2024-09-18 at 12 10 17" src="https://github.com/user-attachments/assets/625811d8-abfa-4583-84cd-faa9a35f85ae">]

For the sketch, I orignally thought to aggreagate all the data by regions to make the data more digestable. I wanted to see how the median age increased over time so that is what my story was with creating this redesigned visualization. I averaged all the medians and assigned different colors to different regions. 

## Step four: Test the solution

_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._

Questions to ask: 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 

| Question                                            | 26M Student                                         | 23F Student |
|-----------------------------------------------------|-----------------------------------------------------|-------------|
|Can you tell me what you think this is?              |showing me the trend of age for first time marriage.|I think this is a graph of the median first marriage age in the us over time|
|Can you describe to me what this is telling you?     |And you are breaking it down by the 4 regions in the US while also giving the overall average  |  this is telling me how the first marriage age has changed over time          |  
|Is there anything you find surprsing or confusing?   |the south stayed relatively the same from 2006 to 2019.|i think it was a little confusing that there were so many lines because at first I thought the lines were for different countries|
|Who do you think is the intended audience for this?  |financial institutions| I think the intended audience is people who are curious about marriage ages
|Is there anything you would change or do differently?|would like to see it starting from 1920 and on the x axis, add a vertical line to break it down per generation| I would change the title of the graph to say median age of first marriage trend over time by geographical area of us or something like that

Synthesis: 
From the feedback that I got, I learned that this representation of the data is a little confusing. I could change the title and potentially identify the United States in a more neutral color so it is not confused with the others. Based on this feedback, I gather that a line chart isn't the best way to visualize this data and I might be more inclined to make something like a boxplot isntead of instance. 

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

For my final redesign data visualization I included a boxplot which references the original data. I thought side-by-side boxplot would be a great way to represent the data and how the median age of marriage has changed within regions over time. A boxplot also shows outliers which might I thought would be cool to represent. The line in the middle shows the average age between 2006-2019 of average age of first marriage and I thought it would be a great reference point to add to see which regions are above/below average for comparison. 

<div class='tableauPlaceholder' id='viz1726678193939' style='position: relative'>
<noscript>
<a href='#'>
<img alt='BoxPlot of Median Age of First Marriage in the US by Regions&#47;Time ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cr&#47;CritiqueByDesign&#47;BoxPlotofMedianAgeofFirstMarriageintheUSbyRegionsTime&#47;1_rss.png' style='border: none' />
</a>
</noscript>
<object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
<param name='embed_code_version' value='3' />
<param name='site_root' value='' />
<param name='name' value='CritiqueByDesign&#47;BoxPlotofMedianAgeofFirstMarriageintheUSbyRegionsTime' />
<param name='tabs' value='no' />
<param name='toolbar' value='yes' />
<param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cr&#47;CritiqueByDesign&#47;BoxPlotofMedianAgeofFirstMarriageintheUSbyRegionsTime&#47;1.png' /> 
<param name='animate_transition' value='yes' />
<param name='display_static_image' value='yes' />
<param name='display_spinner' value='yes' />
<param name='display_overlay' value='yes' />
<param name='display_count' value='yes' />
<param name='language' value='en-US' />
</object>
</div>                
<script type='text/javascript'>
var divElement = document.getElementById('viz1726678193939');
var vizElement = divElement.getElementsByTagName('object')[0];
vizElement.style.width='100%';
vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
var scriptElement = document.createElement('script');
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
