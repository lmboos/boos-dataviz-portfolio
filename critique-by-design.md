| [home page](https://lmboos.github.io/boos-dataviz-portfolio/) | [data viz examples](dataviz-examples.md) | [final project I](final-project-part-one.md) | [final project II](final-project-part-two.md) | [final project III](final-project-part-three.md) |

# Redesign of "The World's Biggest Military Spenders"

## Step one: the visualization
After browsing several Makeover Monday visuals, I decided on a visual that has significance to me. As a member of the US Army, I was intrigued by the military spending visual. It was no surprise to see the United States as the biggest spender, but I did not realize by how much. A few countries in the top 10 were surprising as well, like India and the United Kingdom. The source website had two visuals to depict the military spending. First, a unique take on a pie chart for spending in 2021. Then, there was a supporting table showing spending from 2017 to 2021, but only for half of the top 10 nations that are included in the first chart. 

<div align="center">
  <img src="Original Visual 1.png" width="400"/>
</div>

<div align="center">
  <img src="Original Visual 2.png" width="400"/>
</div>

## Step two: the critique
For the critique portion of this exercise, I completed a Google Form where I rated the visual on a sliding scale, as well as with short responses. The primary critiques I had of the visuals were that the color scheme and shapes on the pie chart added no value. At first, I thought the color scheme was a type of gradient with darker green indicating greater spending and vice versa. However, after looking closer, the colors did not have any clear association with the countries. Also, a pie chart should be split into slices, but instead he had obscure shapes that made it harder for me to grasp the size differences. Finally, his incorporation of a table I thought was a good idea to further support his pie chart, but then I realized he only included data for half of the countries. 

## Step three: Sketch a solution
For my sketch I split it into two sections - recreating the pie chart and redesigning the table to show trends. I had two ideas for each sketch as shown below.

<div align="center">
  <img src="Redesign Sketch.jpg" width="800"/>
</div>

## Step four: Test the solution

During the testing phase, I folded my sketch page in half, so that I could present my options for each sketch. First I showed the redesign options for the pie chart, followed by the redesign options for the table. I asked the same questions for each sketch. Following the interview for both sketches, I showed them the original graphics to see if there was any more follow on feedback. I enjoyed looking at and critiquing my partners' visualizations because it gave me a new perspective on my own redesigns. I noticed things I did and did not like that I was then able to bring back to my sketches, as well as to theirs.

Questions: 

1. Can you tell me what you think this chart represents?

2. Which of these two chart options do you believe is most effective at telling a story?

3. Is there anything you would change or do differently?
   
4. Is there anything you find confusing?

5. After seeing the original graphics, do you have any additional comments or feedback?

**Results**: 

| Question | Interview 1 | Interview 2 | Interview 3 |
|----------|-------------|-------------|-------------|
| 1a         | Military expenditure            | Military expenditure            | Military expenditure             |
| 2a         | Pie chart because stacked area would make more sense when considering multiple year duration            | Pie Chart because it is a good tool to break up whole into multiple parts            | Pie Chart            |
| 3a         | Nothing significant             | Consider a tree map or bubble chart over pie chart            | Nothing significant            |
| 4a         | There are a lot of tiny slices which can be confusing            | Nothing signficant            | Work on a descriptive title            |
| 1b         | Military spending over time           | Military spending over time            | Military spending over time             |
| 2b         | Line plot            | Line plot            | Stacked bar chart because do not want to see multiple overlapping lines and it will be easy to compare the differences between countries with this option            |
| 3b         | Nothing significant             | Nothing significant            | Nothing significant            |
| 4b         | What is the point of the trends? Does it provide the viewer any additional information?             | Nothing signficant            | Work on a descriptive title (again)            |
| 5         | Nothing significant            | Try to do an interactive world map over time in tableau like we did with the in class exercise           | Clear improvement from the originals            |

**Synthesis**: 
The most significant critique I had was suggestions on how to utilize a different chart. I was inspired by the interactive world map idea after the inteviewee showed me an example of what that could look like. To implement this, there would be a symbol map on top with a line chart below it to present trends over time. Along with taking two visualizations and turning it into one, the next biggest critique I had was to work on titles to grab viewers attention. 

## Step five: build the solution
For the final redesign, I tried to take the feedback I received to produce the best result. I did not quite get it to where I wanted it to go, but I think with more practice in tableau, I will be more successful in the future. Rather than have one combined interactive visual, I did manage to do an interactive symbol map, along with a stacked area chart to display spending trends over time. I would have loved to have them move in sync over the years, but I did not figure out how to accomplish that with the stacked area chart. I did look at doing a line plot to present the trends over time, though the feedback from interviewee 3 held true that having 10 separate lines made it confusing. For the symbol map, it is challenging to see the changes in size of the circles over 2017-2023 though. However, I think if I pulled data across several decades the changes might have been more drastic. 

Another thing I struggled with in the redesign was formatting the data correctly so that Tableau could properly display it. I had to clean up the data I pulled from SIPRI quite a few times, and found the solution by having a long form table. This is something I am grateful to have learned now so that for the final project visualizations, I will know how to best organize the data for Tableau. 

### <a href = "https://public.tableau.com/shared/K84Z3BK2F?:display_count=n&:origin=viz_share_link" target="_blank">World's Biggest Military Spenders</a>

<div class='tableauPlaceholder' id='viz1739414989453' style='position: relative'>
  <noscript><a href='#'>
    <img alt='Military Spender Dashboard ' 
      src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;J4&#47;J4WCPH5TY&#47;1_rss.png' 
      style='border: none' />
  </a>
  </noscript>
  <object class='tableauViz'  style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
    <param name='embed_code_version' value='3' /> 
    <param name='path' value='shared&#47;J4WCPH5TY' /> 
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;J4&#47;J4WCPH5TY&#47;1.png' /> 
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
    <param name='filter' value='publish=yes' />
    <param name='ignore_sticky_session' value='yes' />
  </object>
</div>                

<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1739414989453');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { 
    vizElement.style.width='1000px';vizElement.style.height='827px';
  } else if ( divElement.offsetWidth > 500 ) { 
    vizElement.style.width='1000px';
    vizElement.style.height='827px';
  } else { 
    vizElement.style.width='100%';
    vizElement.style.height='977px';
  }                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## References
Conte, Niccolo. “Ranked: Top 10 Countries by Military Spending.” Visual Capitalist, Visual Capitalist, 18 Aug. 2022, www.visualcapitalist.com/ranked-top-10-countries-by-military-spending/. 

"SIPRI Military Expenditure Database 2024, https://www.sipri.org/databases/milex" 

## AI acknowledgements
I utilized ChatGPT to help guide me on some of the tableau functionalities when I got stuck. For the symbol map, originally the percentages were displayed as decimals so I asked how I would fix that and it explained when I right click on the percentage, choose format, and in the numbers section I changed it from decimal to percentage. For the stacked area chart, originally there was no sorting by dollar amount. It explained that in the marks card I could select sort from the country drop down menu. From there, I could sort ascending or descending by the field of my choosing.

