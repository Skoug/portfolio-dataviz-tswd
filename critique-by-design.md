| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Makeover Monday: UFO Sightings

## Step one: the visualization

<img width="1000" height="500" alt="makeoverMondayUFOSightings" src="https://github.com/user-attachments/assets/91160219-a276-4664-8fc4-60ef68574070" />
#MakeoverMonday 2026 WK25/UFO Sightings. (2026, June 22). https://makeovermonday.vercel.app/dataset/2026-wk25-ufo-sightings


### Why this Visualization?
I wanted to challenge myself to find a visualization that is too simplified. Normally, in critiques, we want to remove extraneous details from existing visualizations. However, the original viz in this scenario had neither context nor conveyed an interesting story. This visualization challenged me to add detail without overwhelming my audience.

Also, I found the topic of the visualization, UFO sightings, to appeal to a larger audience. For example, GDP information could appeal to the economically inclined, but UFO sightings can appeal to the general public. This data comes from the National UFO Research Center (NUFORC), a governmental organization, but it demonstrates a contentious pseudo-scientific topic: UFO research. By remaking this viz, I get to tell a "fun" story to a large audience: should I frame the visualization to trust the reports, or to doubt why NUFORC released it in the first place? The original Makeover Monday visualization left me with more questions than answers, thus informing my choice!

## Step two: the critique
### Ranking according to Stephen Few's Effectiveness Profile:
#### Usefulness: 2/10 
  The intended audience, people who trust information from the National UFO Research Center, won't gain much information from this dataset. The line graph shows count of
  UFO sightings alone. This demonstrates an outlier value of reports in 2023, but nothing else. Did people report more in the same area? Was it the same person filing all
  the reports? Was there some kind of rare astrological event that occurred in 2022 that spiked the reports? Were there political motives behind the increase in reports?
  Did the spike happen due to quarantine-induced psychosis? 

#### Completeness: 3/10
  Axis labels are not demonstrative of meaning. There is no title for the graph, nor citation of where the data comes from. There are scales on how many reports were filed   across years-- this gives us our 3/10 rating, because we can see values of data presented over time, at minimum. 

#### Perceptibility: 2/10
  Due to the lack of title, proper axis titles, and unlabled curve, we cannot easily tell what the graph is demonstrating. The mediocre title and axis label lead me to       rate this visualization a 2/10 in perceptibility. 

#### Truthfulness: 1/10
  The dataset shows little to no UFO reports from 1975 to 2019, with a modest increase in 2020 and a huge spike in reports in 2022. 2022 is an outlier, and it leads me to    question the validity of the data collection executed by the National UFO Research Center. The visualization makes no effort to explain why or how this discrepancy         occurred. Furthermore, due to the lack of citation for the NUFORC, we cannot see who published the info in the first place. 

#### Intuitiveness: 8/10
  The simplicity of this visualization gives it a high "intuitiveness" score. Though the viz lacks context, the line itself is extremely readable and demonstrates a sharp    spike in UFO reports filed during 2022. If this was the original intention of the visualization, then it completes its job well without overwhelming the viewer with        extraneous details. 

#### Aesthetics: 3/10
  This viz is not ugly per-se, but it is not visually stimulating. The plain gray and limited elements gives the viz a plain look. While plain graphs are good in terms of    simplicity, they do not draw our audience's attention, nor tell an interesting story. The aesthetics of this visualization should be more focused on the topic-- UFOs. In   my redesign, I plan to use green and gray/silver, two colors commonly associated with the public conception of aliens. This will add to the aesthetics, visual intrigue,   and aid in the story I plan to tell. 
  
## Step three: Sketch a solution
 In my redesign, I aim to add context as to why we see an outlier year in the original distribution. For the purposes of my visualization, I will focus specifically on 2022. This will help us explore why exactly the I want to incorporate location information included in the original dataset. We can test what parts of the country experienced the highest increase in UFO reports and if any patterns emerge between location and frequency of reports. My audience will increase as well: I want anyone from the U.S. to gain information on UFO sightings and why there was such a large increase in 2022. 

I believe a map of the United States with points (circles) that highlight each report based on its location will increase interpretability of the data. I will use the latitude/longitude variable in the excel to plot the location of each report. The viz will use gray to define states and boundaries, with green for each point-- the green should be an alert shade. This green also related to our pre-conceived understanding of "green" aliens. The color variation will hopefully add visual intrigue. I will need to include a different title and legend for my graph. I think a fun title (perhaps misleading)  could be, "Where will aliens go next? | an exploration of 2022 UFO reports from the National UFO Research Center." 
<img width="1000" height="500" alt="Scanned_MakeoverMon_sketch_01" src="https://github.com/user-attachments/assets/4de86ffb-8c4b-423c-9c7f-8aa226e5a1fe" />
<img width="1000" height="500" alt="Scanned_MakeoverMon_Sketch_02" src="https://github.com/user-attachments/assets/ee0a4ab2-0edc-4104-81f5-d49ee4656838" />


## Step four: Test the solution
Questions I asked my group members, 3 fellow students at Carnegie Mellon's Heinz College. 

- A. What information does this viz convey, and how well does it convey?

- B. How can the style of the visualization be refined?

- C. How could I incorporate the time variable seen in the original data viz?

- D. Who do you think is the intended audience for this?

Results: 

| Question | Interviewee 1 | Interviewee 2 | Interviewee 3 | Interviewee 4: Former TSWD student, taken after primary interviews | 
|----------|-------------|-------------|-------------------|------------------------------------| 
|      A    |Good design, grasps general concept quickly| Geolocation data useful, but large circles aren't as useful for locating where events occur specifically |Provides an informative hook and cites source, easy to understand| Change the title. Fun hook but doesn't show main takeaway/pattern in data. | 
|      B    |Heatmap instead?|Use overlapping points, but create a gradient for cities with >1 report.| Overlapping points works well! | Keep the pinpoints / symbol map|
|      C    | Multiple vizzes on a dashboard | Doesn't need more info, 1 year is enough.| Make a time slider variable to change the year displayed.| 1 year is enough. Simple / minimalistic for easier understanding. 
|      D    | UFO-positive people. Those who don't need to be convinced to believe| General US public | People who know the NUFORC | Including the summary variable is good, audience is anyone entertained / interested in people's descriptions of UFO sightings | 

#### Synthesis: 

Based on the suggestions of my peers, I needed to figure out how to differentiate different concentrations of reports across the map. I need to show, generally, where events occur vs. where they don't across the U.S., while still highlighting individual reports. This poses a challenge, as a heatmap shows general UFO report hotspots without focus on reports. I believe a pinpoint symbol map will work best to demonstrate the geolocation of the reports. Next, my group decided that while one year of information was useful for telling a story, more years of information could be useful for audience members who want to look deeper into the data. However, I think that multiple years of geolocation information will overwhelm my audience. Is there a way to find a happy medium? Finally, the audience for this visualization could vary. Many people could be interested in the nuances of "alien" sightings, whether they be skeptics or believers. In general, my audience will be people who are interested in UFOs, but not previously aware of the NUFORC. This visualization should be their first introduction to this dataset. 

## Step five: build the solution

<div class='tableauPlaceholder' id='viz1789668886373' style='position: relative'><noscript><a href='#'><img alt='UFO Sightings More Concentrated in Eastern States: Where will UFOs Appear Next?An exploration of 2022 Unidentified Flying Object (UFO) reports from the National UFO Research Center. https:&#47;&#47;pub-cee805df54de4b6c8f93bee984e3c725.r2.dev&#47;datasets&#47;2026-wk25- ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;QR&#47;QRPGB3T2P&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;QRPGB3T2P' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;QR&#47;QRPGB3T2P&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1789668886373');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

#### Description
My final visualization, "UFO Sightings More Concentrated in Eastern States: Where will UFOs Appear Next?", features data from the NUFORC displayed in a manner digestible for the public. The symbol map preset on Tableau allowed me to identify where UFOs are reported using latitude and longitude variables. When a user places their cursor on a report, key variables appear: the city the incident occurred in, the date of the sighting, and a summary of what the reporter saw. An interested user can scroll over each location, but the lack of labels on every point increases perceptibility for other audiences. 

Each pinpoint, representing a report, is placed on the geolocation where it occurred. My critique and my interviews with peers revealed that...

1. People want to know where reports occur, but...
2. A standard diverging color heatmap of reports will be too visually overwhelming.

After experimentation in Tableau, I discovered that changing the opacity of each symbol can act as a quasi-heat map. Individual pinpoints will appear transparent (lighter in shade) than locations with many concentrated reports (deeper in shade). With each point at 30% opacity, we are able to see the individual symbols and also perceive differences in tone that convey concentration. Transparent symbols allowed my visualization to improve in perceptibility, intuitiveness, and aesthetic simplicity on the Stephen Few Effectiveness Profile, as compared to my drafts. 

Next, to increase the trustworthiness of the data, I included a link to the original dataset published by the NUFORC. Readers can identify that this information is sourced from a Federal agency. Instead of blindly representing a trend in a dataset, like the Makeover Monday visualization, the link and title work in combination to contextualize the data. The title now explicitly mentions concentration of reports (based on geolocation): the title guides the reader to a conclusion, and the hook adds intrigue. My title is a bit long, but I wanted to convey my outtake from the data while preserving my original hook. The addition of a title will increase the score on intuitiveness, completeness, and truthfulness criteria.

The process of critique helped me realize areas where my visualization was lacking-- who was the visualization for? How could I display concentrated vs. diffused reports across the nation? Experimentation in Tableau aided in this effort; I worked with the data and experimented with filters, color, shape, symbols, and more attributes of each report to finalize the visualization. I believe this visualization reaches my goal of demonstrating each report individually while showing the overall concentration of reports across the nation in 2022. Though this may not reflect the takeaway of the Makeover Monday visualization, I believe my choices more accurately represent different aspects of the NUFORC dataset and aids in comprehension for the general public. 

## References

I interviewed a former _Telling Stories With Data_ student, who aided me in refining my title. Her expertise allowed me to reframe my conception of the titles' purpose: rather than act as a hook, it must also explicitly state the main takeaway of the viz, too. For interested graders, please contact me, and I will mention this student's name. I will not publish any personal information on my site. 

Makeover Monday Post:
#MakeoverMonday 2026 WK25/UFO Sightings. (2026, June 22). https://makeovermonday.vercel.app/dataset/2026-wk25-ufo-sightings

Kaggle post used as a source by Makeover Monday:
Arvidsson, J. (2023). UFO Sightings. Kaggle. https://www.kaggle.com/datasets/joebeachcapital/ufo-sightings

Data Source: NUFORC
National UFO Research Center. (2023). https://pub-cee805df54de4b6c8f93bee984e3c725.r2.dev/datasets/2026-wk25-ufo-sightings/ufo_data_nuforc.csv

## AI acknowledgements
No AI was used in the writing or the creation of visualizations within this assignment. 







