| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Wireframes / storyboards

Link to my shorthand: https://carnegiemellon.shorthandstories.com/the-green-lakes-Skoug/index.html

My storyboard includes 3 visualizations:

1. Where algae forms: Using tableau, I mapped GLERL monitoring buoy locations in Western Lake Erie, along with the concentration of algae sediments found at each location. This data is recent, but I collected it a few weeks ago during week 1. I believe it is still representative of algae blooms during the summer, though.

 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Harmful Algae Blooms</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f5f5f5;
        }

        .header {
            max-width: 1200px;
            margin: 40px auto 20px;
            padding: 0 20px;
        }

        h1 {
            margin-bottom: 10px;
        }

        .description {
            font-size: 16px;
            line-height: 1.5;
        }

        .tableau-container {
            max-width: 1200px;
            margin: 0 auto 40px;
            padding: 0 20px;
        }

        iframe {
            width: 100%;
            height: 700px;
            border: none;
            background: white;
        }
    </style>
</head>

<body>

    <div class="header">
        <h1>Harmful Algae Blooms More Concentrated in August and September</h1>

        <p class="description">
            NOAA - Great Lakes Environmental Research Laboratory, Summer 2026
        </p>
    </div>

    <div class="tableau-container">

        <iframe
            src="https://public.tableau.com/views/HABConcentration--FinalProject/Sheet1?:showVizHome=no"
            allowfullscreen>
        </iframe>

    </div>

</body>
</html>

2. Harmful Algae Blooms (HABs): This visualization uses Environmental Sensor Processor data to track the presence and quantity of microcystin, one of the most prevalent harmful algae species. It shows the amount of toxin present in the water based on color and size. I would normally just use color to show the distribution of toxin percentages, but since measurements occurred around the same region, they all overlapped on the map. I believe this mix of both size and color variation best demonstrates the danger of toxins. However, it may lead people to believe that is where algae forms. I have yet to find a solution to that problem.

3. Economic Output: This diagram shows the economic output for economic sectors that rely on the Great Lakes-- namely fishing and tourism. These industries will be the most impacted by the spread of algae blooms. It can show farmers the wider impact of their actions on their surrounding communities. 


# User research 

## Target audience

With my Shorthand website, I hope to reach farmers in the Great Lakes region who directly contribute to the nutrient load in water. Nutrients from fertilizer and livestock farms can run off into waterways. These farmers may know that they need to limit the amount of fertilizer they use, but they may not understand why. I want to convince these farmers to invest in new technology that will limit the amount of fertilizer they use, thus limiting the amount that runs off into larger bodies of water. Though, I need to convince already cash-strapped farmers to make an investment: I will propose financial resources that could fund sustainable technology implementation in the region. 

In trying to find people to interview, I want to speak with people who are familiar with topics introduced in this class, but also laypeople without extensive knowledge of data visualization or policy intervention. So, I plan to speak with two students in class, then with two friends who are not in my graduate program. I can gauge how the public may interpret my work using this interview audience. 

## Interview script
> List the goals from your research, and the questions you intend to ask. 


| Goal | Questions to Ask |
|------|------------------|
| Improve story, cater to audience  | Does the storyboard speak to my audience? Would farmers be offended? |
| Visualizations match story (no unnecessary vizzes that distract) | Should I include more/less visualizations? |
| Compelling aesthetic choices that support story| How does the visual design of the visualizations and storyboard convey the story?|



## Interview findings

My interview questions mostly revolved around my storyboard in Shorthand. I wanted to refine the visualizations on my own time, but I needed more feedback on my story and Shorthand site. 


| Questions               | Interview 1 (in-class interview with fellow TSWD students)| Interview 2 (in-class interview with fellow TSWD students) | Interview 3 (non-student)| Interview 4 (non-student)| 
|-------------------------|--------------------------------|-------------|-------------|-------------------------| 
| Does the storyboard speak to my audience? |  Make the audience clear from the introduction. You didn't mention your key audience until the "recommendation" at the end.  |  I appreciated the call out to farmers in the call to action. But, you can remove text bloat. It's a lot to read!| 
| Should I include more/less visualizations? |  3-4 visualizations works. Nothing is distracting from the message. | Agreed, 3-4 visualizations works due to the vizzes having different topics/insights.|
|  How does the visual design of the storyboard convey the story? | I liked the story arc presented. Personal photos are a nice touch. | Please change the shade of green you used for the background! It's hard to read the text from far away.| 


# Identified changes for Part III
> Document the changes you plan on implementing next week to address any issues identified.  



| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| Clean up HTML | Some visualizations are not appearing correctly at first glance. Formatting is off... had to go full screen to show viz.  |
|  Shade of Green  |   I will choose a more muted shade of green.    |
|   Immediately address stakeholders | Remove bloated text from introduction, instead immediately address my audience. Perhaps I can change the subtitle of my project, too. |
| Work on visualizations | I had rough draft visualizations prepared for these interviews. I need to make more robust vizzes that match the aesthetic choices I used in the Shorthand site.|
| Text legibility  |   Change color AND bold / use different color for important outtakes.  |




## References
I will list my full references for the assignment (so far) here: Not all of these sites were used to inform this specific part of the project. 
Department of the Interior—Benthic Algal Community Composition in the Laurentian Great Lakes. (2024). Data.Gov. Retrieved September 23, 2026, from http://catalog.data.gov/dataset/benthic-algal-community-composition-in-the-laurentian-great-lakes-2024

Department of the Interior—Potential for microbially mediated nitrogen transformations in benthic algae, sediment, and overlying water in the Great Lakes. (2022). Data.Gov. Retrieved September 23, 2026, from http://catalog.data.gov/dataset/potential-for-microbially-mediated-nitrogen-transformations-in-benthic-algae-sediment-2022

Harmful Algal Blooms (HABs), CIGLR. (n.d.). Retrieved September 23, 2026, from https://ciglr.seas.umich.edu/project/harmful-algal-blooms-habs/

Economics: National Ocean Watch. (n.d.). Retrieved September 23, 2026, from https://coast.noaa.gov/digitalcoast/data/enow.html

US Department of Commerce, N. (2026-a). NOAA-GLERL Western Lake Erie Environmental Sample Processor data. Retrieved September 23, 2026, from https://www.glerl.noaa.gov/res/HABs_and_Hypoxia/esp-data/

US Department of Commerce, N. (2026-b). NOAA-GLERL Western Lake Erie Weekly Field Sampling data. Retrieved September 23, 2026, from https://www.glerl.noaa.gov/res/HABs_and_Hypoxia/wle-weekly-current/

American Farmland Trust. (n.d.). Protecting the Great Lakes through a Farm Navigator Network. American Farmland Trust. Retrieved October 1, 2026, from https://farmland.org/protecting-the-great-lakes-through-a-farm-navigator-network

Causes of HABs and Toxicity. (n.d.). NCCOS - National Centers for Coastal Ocean Science. Retrieved October 1, 2026, from https://coastalscience.noaa.gov/science-areas/habs/causes-of-habs-toxicity/

CDC. (2025, December 9). Symptoms Caused by Harmful Algal Blooms. Harmful Algal Bloom (HAB)-Associated Illness. https://www.cdc.gov/harmful-algal-blooms/signs-symptoms/index.html

Michigan State University. (n.d.). Great Lakes Partnership for Food and Farm Development. Great Lakes Partnership for Food and Farm Development. Retrieved October 1, 2026, from https://www.canr.msu.edu/glp-ffd

NOAA Office for Coastal Management. (2024). Economics: National Ocean Watch. Digital Coast. https://coast.noaa.gov/digitalcoast/data/enow.html

US Department of Commerce, N. (n.d.). HABs Monitoring. Retrieved September 30, 2026, from https://www.glerl.noaa.gov/res/HABs_and_Hypoxia/habsMon.html

## AI acknowledgements
No AI was used in the research or production of this assignment, nor in the shorthand site or tableau visualizations. 

