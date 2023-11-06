[Back to Main Page](/README.md)

# Assignment: Visualizing Government Debt Using Tableau

## General Government Debt
### Embed From OECD Website
<iframe src="https://data.oecd.org/chart/7eMa" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7eMa" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2018</a></iframe>

As stated on the OECD website, "General government debt-to-GDP ratio measures the gross debt of the general government as a percentage of GDP. It is a key indicator for the sustainability of government finance. Debt is calculated as the sum of the following liability categories (as applicable): currency and deposits; debt securities, loans; insurance, pensions and standardised guarantee schemes, and other accounts payable. Changes in government debt over time primarily reflect the impact of past government deficits." This graph, although fairly clean in terms of organization, layout, and writing, is not designed to the best it can be. To begin, the names of the countries at the bottom of the graph are very small and may be hard to read for some viewers. In addition to this, the feature allowing the viewer to "highlight" specific countries by clicking on them becomes overwhelming with the rainbow of colors that is created when multiple countries are highlighted at the same time.

## General Government Debt
### Embed From Tableau
<div class='tableauPlaceholder' id='viz1698970626839' style='position: relative'><noscript><a href='#'><img alt='General Government Debt (Source: OECD Data) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ge&#47;Generalgovernmentdebt&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Generalgovernmentdebt&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ge&#47;Generalgovernmentdebt&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1698970626839');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

Using the same dataset as above, this heat map graph is more effective from a color standpoint in which only two hues of colors (blues and oranges) are used to differentiate the data. However, this depiction can be a bit overwhelming to look at with the large number of values displayed. Although potentially more accessible than the previous graph, the information being presented is still a lot for the viewer to digest.

## Cumulative General Government Debt
### Embed From Tableau
<div class='tableauPlaceholder' id='viz1698973322991' style='position: relative'><noscript><a href='#'><img alt='Cumulative General Government Debt By CountryFrom 2018-2022 (Source: OECD Data) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cu&#47;CumulativeGeneralgovernmentdebt&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CumulativeGeneralgovernmentdebt&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cu&#47;CumulativeGeneralgovernmentdebt&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1698973322991');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

This chart entitled, "Cumulative General Government Debt" displays the data provided by OECD concerning the varying degrees of debt across the years from countries across the world. I chose this chart to display the data after experimenting with different types because I believe it is the most effective at displaying all three required categories of location, value, and year. I chose to consolidate the years shown because I think that the depiction of a 5-year period is much more digestible for the viewer to understand the immediate fluctuations in the level of government debt, especially during the COVID-19 pandemic. I believe that the blue palette is accessible to all viewers and provides a calm, stable depiction of the data while also showing stark contrast in the different hues of the blue. I decided to have the darkest color blue at the bottom (representing the most recent year in the graph of 2022) because dark colors are typically assumed to be "heavier" than lighter colors and it seemed to make the most sense to keep it at the bottom and allow for the gradient to rise towards the top. The key at the top right of the graph allows the viewer to understand the depiction of the years without having too much writing and clutter on the graph itself. Overall, the depiction of the data as cumulative in this chart rather than split into individual years is helpful to see a different perspective of the dataset.
