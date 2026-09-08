| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Data visualization examples
_You can place some of your data viz examples from the course here._  Make sure to include any citations / references / data sources used, and it's probably a good idea to explain what these visualizations show.

# Working With Tableau: Visualizing Government Debt
### Viz 1: Heat map of debt
The following data visualization takes debt data from OECD filings from 2007 to 2024. It charts changes in debt-to-GDP ratio across different nations over time. Any nations with a debt ratio over 100.00 has more debt than income in a single year. This visualization corresponds to parts 1 and 2 of this homework assignment. 
<div class='tableauPlaceholder' id='viz1788883867578' style='position: relative'>
  <noscript>
    <a href='#'>
      <img
        alt='Debt to GDP Ratios Peak in 2020, OECD 2025.'
        src='https://public.tableau.com/static/images/OE/OECDProjectTSWD/DebttoGDPRatiosPeakin2020OECD2025_/1_rss.png'
        style='border: none'
      />
    </a>
  </noscript>

  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='OECDProjectTSWD/DebttoGDPRatiosPeakin2020OECD2025_' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/OE/OECDProjectTSWD/DebttoGDPRatiosPeakin2020OECD2025_/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
    <param name='filter' value='publish=yes' />
  </object>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1788883867578');
  var vizElement = divElement.getElementsByTagName('object')[0];

  vizElement.style.width = '100%';
  vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';

  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script> 

### Viz 2: Redesigned Heat Map
<div class='tableauPlaceholder' id='viz1788895210077' style='position: relative'><noscript><a href='#'><img alt='Japan and Greece Lead in National DebtAverage Debt-to-GDP ratio from 2020-2024, (OECD 2025).  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;OE&#47;OECDHeatmapRedesignProjectTSWD&#47;JapanandGreeceLeadinNtlDebt&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='OECDHeatmapRedesignProjectTSWD&#47;JapanandGreeceLeadinNtlDebt' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;OE&#47;OECDHeatmapRedesignProjectTSWD&#47;JapanandGreeceLeadinNtlDebt&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1788895210077');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

My visualization focuses on average debt ratios within this decade (2020-2024). While the full range of data, spanning from 2007 to 2024, was beneficial in the original heatmap, I wanted my final visualization to focus on observations from the 2020s. This would narrow the scope of the data visualization and make it easier to parse for a contemporary audience. Next, I used the average debt-to-GDP ratio as my observed value, rather than the sum of values across years. 

I decided to use the "treemap" preset for this visualization. I changed the shape of each unit to circles, then sorted the reference area to descending order. This order ensures that the largest circles are at the center of our round visualization. Since viewers can naturally sense statistical values in size changes, they will infer that nations near the center, with the largest circles, will have more debt. Also, since these circles are larger, viewers may be more likely to read them first. This size difference works in conjunction with my color choice. I chose the diverting range yellow to purple, with a center at 100. Nations shaded with yellow have a lower debt-to-GDP ratio (more GDP than debt) and vice-versa for purple nations. So, the nations at the center of the graph are a deep purple that draws the viewer's attention. Notably, I did not use a green-red diverting range: those shades would show the positive/negative implications behind each nation's debt ratio, but the colors could have different meanings depending on a person's nation of origin. Since my audience may be from nations around the world, I did not want to rely on the Western conception that green is associated with positive values and red with negative values. Finally, my title, "Japan and Greece Lead in National Debt", highlights the two nations with the highest debt-to-GDP ratio on average. The title is also placed in a light yellow box to ensure a viewer will notice it upon first glance. The treemap still draws the most attention, however. 

I believe this visualization is more effective than the original heatmap. While color alone differentiated positive and negative values in the heatmap, this visualization uses color, position, and size to highlight nations with the highest debt-to-GDP ratios. Additionally, the title works with the visualization to reinforce our viewer's key takeaway. 

I did not use AI in the drafting of this post or creation of my visualization. 

# Trust in News Media-- In Class Exercise
<div class='tableauPlaceholder' id='viz1788900554273' style='position: relative'><noscript><a href='#'><img alt='Trust in news Media (Simmons Research, 2018) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;tr&#47;trustinmedia&#47;TrustinMedia&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='trustinmedia&#47;TrustinMedia' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;tr&#47;trustinmedia&#47;TrustinMedia&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div> <script type='text/javascript'>                    
  var divElement = document.getElementById('viz1788900554273');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
  
