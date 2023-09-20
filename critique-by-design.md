| [home page](https://tae-c.github.io/tae-datavis/) | [visualizing debt](visualizing-debt) | [critique by design](critique-by-design) | [final project I](final-project-I) | [final project II](final-project-II) | [final project III](final-project-III) |

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

  [FiveThirtyEight]: <https://fivethirtyeight.com/features/why-some-tennis-matches-take-forever/>
