### Portfolio
Below are assignments to _Telling Stories with Data_ course, but feel free to check out my design portfolio [here]

| [home page](https://tae-c.github.io/tae-datavis/) | [visualizing debt](visualizing-debt) | [critique by design](critique-by-design) | [final project I](final-project-I) | [final project II](final-project-II) | [final project III](final-project-III) |

# tae-datavis
Portfolio for Telling Stories with Data

### About me
Hi, I am a product designer, and I believe my curiosity is what fuels innovation and leads me to new connections and discoveries. I am a 2nd year Master of Design student in the School of Design.
After graduating from Pratt Institute with a Bachelor's in industrial design, I worked at iOttie Inc designing consumer electronics and at Fossil Group designing smartwatches and traditional watches for Michael Kors. Most recently, I've interned at BCG as an experience designer. 
Outside of design, i enjoy having nerdy discussions about watches and playing tennis!

### What I hope to learn
I want to continue learning data visualization methodologies and techniques. Last year, I was briefly exposed to data visualization, and it was definitely an area of discipline I was attracted to. Over my summer internship, the project I was working on involved designing a dashboard, and having an in-depth knowledge of this topic could have helped me drastically. I understand the importance of clear communication and data visualization is something I want to continue learning and improving on.

### Assignment:Visualizing goverment debt
Part 1

<iframe src="https://data.oecd.org/chart/7aXS" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7aXS" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2019</a></iframe>

Part 2

<div class="flourish-embed flourish-chart" data-src="visualisation/14928192"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Part 3

<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/14928571"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

I wanted to show a race of these countries over the course of 1995 to 2017. The chart is only showing the top 10 countries with the highest debt-to-gdp ratio. I couldn't figure out a way to directly import the data into the preset template. So I only showed 15 countries and did some manual data entry. The 15 countries shown are Austrailia, AUstria, Belgium, Canada, Czech Rep, Denmark, Finland, France, Germany, Greece, Hungary, Ireland, Italy, and Japan

Tableau Exercise

<div class='tableauPlaceholder' id='viz1694528190128' style='position: relative'><noscript><a href='#'><img alt='Trust in News Organizations (Source: Simmons Research) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;Practice2_16945281818510&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Practice2_16945281818510&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;Practice2_16945281818510&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1694528190128');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

### Assignment 3 & 4: Critique by Design

#### Original visualization
![tennis original chart!](https://github.com/tae-c/tae-datavis/assets/143672477/ad87f1dc-1ae7-4236-afbe-5b4bf6fdf910)
The original visualization I worked to improve on was the "Surface Speeds" chart by [FiveThirtyEight]. I liked how they separated fastest, slowest, and other notable tournaments into different charts. It was easy to see those 3 categories at a glance, however as a viewer, I wanted the option to expand or see all the other tournaments as well. While informative, the charts are visually boring. I'd like to reimagine this chart into a more visually engaging graphic that is also interactive. I'm not sure if "years running" is important in this chart. As a viewer, I think the more important data points to highlight are the surface type and time added so that the viewers can immediately learn from the visualization that type of surface directly relates to how much time is being added per point.

This selected chart is lacking color and design for sure. It's intended to be informative, so I think the creator had it in a simple chart view. I think there are some missed opportunities to drive other narratives because of its excel-like layout. Also the chart does not show all 205 tournaments and by doing so, viewers can't really see where on the spectrum hard court speeds fit in. I would show all 205 tournaments so that viewers can also visually see the ratio of different surfaces on pro tour.

#### Sketch of my redesign idea
![my sketch!](https://github.com/tae-c/tae-datavis/assets/143672477/b10b892c-d3f3-44e5-837e-2eb1a6d63bc1)
As for my redesign sketch, I wanted to move away from the classic excel-like chart view into a more colorful bar chart view. First, I want to categorize different surfaces into distinct colors so that the viewer can easily see which surface tends to be slower or faster and include a legend at the bottom. Second, I want to show all 205 tournaments here instead of showing only 10 fastest and slowest tournaments like the original. Third, I removed "years running" data. Fourth, I arranged them in a bar chart with all negative times indicating faster matches and positive times indicating slower matches.

I've shown this sketch to a few people in my department, and the feedback was very helpful. One of my users was not familiar with professional tennis tournaments and expressed that this visual taught them about the existance of different surfaces on pro tour as well as showed a clear relationship between type of surface and match time. Hearing this, I decided to move onto building the visualization on Flourish.

#### My visualization
<div class="flourish-embed flourish-chart" data-src="visualisation/15043129"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

This was my redesigned visualization built on Flourish, and it is not exactly as I sketched it previously. I was not able to categorize the 4 surface types into different colors and display all the tournaments in one single view. Instead, I was able to figure out how to categorize the surfaces into different filter tabs so that the viewer can click through each surfaces and see how much time was being added or subtracted per point. I believe my original sketch idea, if executed, would do a better job of showing the relationship between match speed and court surface, because all of the 205 tournaments would be viewed in one single view.  

  [here]: <http://www.taeyoungchang.com>
  [FiveThirtyEight]: <https://fivethirtyeight.com/features/why-some-tennis-matches-take-forever/>
