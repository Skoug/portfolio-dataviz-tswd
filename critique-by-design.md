| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Makeover Monday: UFO Sightings


_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization

https://makeovermonday.vercel.app/dataset/2026-wk25-ufo-sightings
<img width="1345" height="784" alt="makeoverMondayUFOSightings" src="https://github.com/user-attachments/assets/91160219-a276-4664-8fc4-60ef68574070" />

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
<img width="2185" height="1789" alt="Scanned_MakeoverMon_sketch_01" src="https://github.com/user-attachments/assets/4de86ffb-8c4b-423c-9c7f-8aa226e5a1fe" />
<img width="2251" height="1895" alt="Scanned_MakeoverMon_Sketch_02" src="https://github.com/user-attachments/assets/ee0a4ab2-0edc-4104-81f5-d49ee4656838" />


## Step four: Test the solution
Questions I asked my group members, 3 fellow students at Carnegie Mellon's Heinz College. 

- A. What information does this viz convey, and how well does it convey?

- B. How can the style of the visualization be refined?

- C. How could I incorporate the time variable seen in the original data viz?

- D. Who do you think is the intended audience for this?

Results: 

| Question | Interviewee 1 | Interviewee 2 | Interviewee 3 |
|----------|-------------|-------------|-------------------|
|      A    |Good design, grasps general concept quickly| Geolocation data useful for interpretation |Provides an informative hook and cites source, easy to understand|
|      B    |Heatmap instead?|Use overlapping points, but create a gradient for cities with >1 report.|Overlapping points works well! |
|      C    | Multiple vizzes on a dashboard | Doesn't need more info| Make a time slider variable to change the year displayed.|
|      D    | UFO-positive people. Those who don't need to be convinced to believe| General US public | People who know the NUFORC |

Synthesis: 

  Based on the suggestions of my peers, I will DESCRIBE SOLUTION 

  
_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._


## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._







