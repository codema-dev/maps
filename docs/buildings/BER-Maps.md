# Building Energy Rating (BER) Maps

## SEAI Small Area Map

> Developed by Mark Bohacek, Behavioural Economics Unit, SEAI, 2019. Last update: 04/2020

> The data includes currently geo-coded dwellings that have had a BER completed. After clicking on a coloured Small Area the map generates basic summary statistics including a break-down by dwelling type, BER rating, BER value, heating fuel, controls, etc. The map includes a filter that allows users to filter by the percentage of BERs carried out in a Small Area (to operate the filter simply type in the desired percentage). The map also allows user to select Small Areas with a desired combination of median BERs. You can also search by address or EirCode (left magnifying glass), or Small Area (right magnifying glass) buttons located in top left corner of the map.


<iframe width="1000" height="1000" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" 
src="https://renewables.maps.arcgis.com/apps/webappviewer/index.html?id=360f7b3f6f484d7d89b967b41231daef"></iframe>


## `codema-dev` Small Area Map

> Developed by `codema-dev`, 2021. Last update: 07/2020. 

> The map uses a closed-access Small Area version of the SEAI's BER Public Search database to evaluate the median BER rating per Small Area.

> **Caveats**: the BER Public Search database is not a complete building stock database and is biased against old buildings.

<div class='tableauPlaceholder' id='viz1613734369266' style='position: relative'>
    <noscript>
        <a href='#'>
            <img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Du&#47;DublinSmallAreaBER&#47;Sheet1&#47;1_rss.png' style='border: none' />
        </a>
    </noscript>
    <object class='tableauViz'  style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
        <param name='embed_code_version' value='3' /> 
        <param name='site_root' value='' />
        <param name='name' value='DublinSmallAreaBER&#47;Sheet1' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Du&#47;DublinSmallAreaBER&#47;Sheet1&#47;1.png' /> 
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='en' />
        <param name='filter' value='publish=yes' />
    </object></div>                
<script type='text/javascript'>                    
    var divElement = document.getElementById('viz1613734369266');                    
    var vizElement = divElement.getElementsByTagName('object')[0];                    
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
    var scriptElement = document.createElement('script');                    
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## `codema-dev` Postcode Map

<div class='tableauPlaceholder' id='viz1613475109867' style='position: relative'>
    <noscript>
        <a href='#'>
            <img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Du&#47;DublinBERbyPostcode_16134730869990&#47;Sheet1&#47;1_rss.png' style='border: none' />
        </a>
    </noscript>
    <object class='tableauViz'  style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
        <param name='embed_code_version' value='3' /> 
        <param name='site_root' value='' />
        <param name='name' value='DublinBERbyPostcode_16134730869990&#47;Sheet1' />
        <param name='tabs' value='no' /><param name='toolbar' value='yes' />
        <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Du&#47;DublinBERbyPostcode_16134730869990&#47;Sheet1&#47;1.png' /> 
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='en' />
    </object></div>                
<script type='text/javascript'>                    
    var divElement = document.getElementById('viz1613475109867');                    
    var vizElement = divElement.getElementsByTagName('object')[0];                    
    vizElement.style.width='100%';
    vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
    var scriptElement = document.createElement('script');                    
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

> Created using SEAI's BER Public Search database via the [berpublicsearch](https://github.com/codema-dev/berpublicsearch) tool on 23/02/2021.  

> **Caveats**: the BER Public Search database is not a complete building stock database and is biased against old buildings.  

## `codema-dev` Small Area Map

The following Small Area Map was created for the entire Dublin residential building stock as of the [2016 Census](https://www.cso.ie/en/census/census2016reports/census2016smallareapopulationstatistics/) using the [estimated BER bands](BER-Age-Profiles.md)

<object type="text/html" data="../../html/estimated_dublin_small_area_bers.html" width="2000" height="1000" frameborder="0"></object>