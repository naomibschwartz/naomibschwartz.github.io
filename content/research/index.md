---
title: Research
date: 2023-10-11

type: landing

sections:
  - block: markdown
    id: intro
    content:
      title: Our Research
      text: Our lab’s research addresses questions about the causes and consequences of disturbance and extreme events in forest landscapes, mostly in tropical regions. Climate and land-use change are already altering the frequency and intensity of disturbance and climate extremes. Can we predict which forests will be most vulnerable to these events? What are the processes that underlie spatial heterogeneity in forest responses to disturbance and climate extremes? How do these events shape forest landscapes? To address these themes, we use a variety of tools including remote sensing and GIS, forest censuses, plant functional trait measurements, and socio-economic surveys.
    design:
      columns: '2'
      background:
        text_color_light: true
        image:
          filename: green-vegetation.jpeg
          filters: 
            brightness: 0.3
          size: cover
          position: center
          parallax: true
      spacing:
        padding: ["20px", "0", "20px", "0"]
        
  - block: markdown
    id: intro
    content:
      title: Study Sites
      text: <iframe 
        width='100%' height='400px'
        src="https://api.mapbox.com/styles/v1/kmcguire33/clp1hgkip00ct01r6h2ppg7ni.html?title=false&access_token=pk.eyJ1Ijoia21jZ3VpcmUzMyIsImEiOiJjbG5ucnp1em0wNzJrMnNwZ2ZyYTg2dTY4In0.TuyTQQVMp_TFZkj57EbkGg&zoomwheel=false#1.70/26/-12" title="schwartz-map-11.16.23"
        title="schwartz-map" 
        style="border:none;">
        </iframe>
    design:
      columns: '1'
      spacing:
        padding: ["20px", "0", "10px", "0"]
        
  - block: markdown
    id: active-projects-1
    content:
      title: Current Projects
      text: |-
        ## **Savanna-Forest Boundaries in a Seasonally Dry Tropical Landscape**
        We are working to understand the ecological processes that maintain boundaries between forests and mesic savannas in seasonally dry tropical landscapes. Our work focuses on Southeast Asia, where deciduous dipterocarp savannas and dry evergreen forests form patchy landscape mosaics with abrupt transitions between vegetation types. We are using remote sensing, field data, and modeling to quantify the influence of climate variability and land use on fire regimes in this landscape and to identify key feedbacks between fire, soil conditions, and vegetation structure and function at boundaries between vegetation types.
        
        Relevant Publications: <br>
        * *[The environmental drivers of tree cover and forest--savanna mosaics in Southeast Asia]({{< relref "/publication/pletcher-2022-environmental" >}})*
        
        {{< gallery album="savanna-forest" >}}
    design:
      columns: '1'
      spacing:
        padding: ["20px", "0", "20px", "0"]
  
  - block: markdown
    id: active-projects-2
    content:
      title:
      text: |-
        ## **Post-Fire Environments in Western North American Forests**
        With climate change and increasing fire activity in Western North America, trajectories of forest recovery in burned forests are uncertain. We are using satellite and remotely piloted aircraft (RPA) remote sensing to map environmental conditions in burned forests and identify how these factors influence forest recovery.
        {{< gallery album="post-fire" >}}
    design:
      columns: '1'
      spacing:
        padding: ["20px", "0", "20px", "0"]  

  - block: markdown
    id: active-projects-3
    content:
      title:
      text: |-
        ## **Impacts of Rainfall Seasonality on Tropical Forest Composition, Function, and Drought Response**
        Rainfall regimes vary across many axes beyond just total annual rainfall, including number of dry seasons, onset and duration of the dry season, and contrast between wet and dry seasons, among others. We are working to link herbarium collections and satellite remote sensing data to investigate how rainfall seasonality influences variation in plant water-use strategies and how these differences scale up to influence productivity and other ecosystem processes in seasonally dry tropical forests (SDTF). We are also interested in how average seasonality is associated with how vulnerable or resilient forests are to drought.
        
        Relevant Publications: <br>
        * *[Beyond MAP: A guide to dimensions of rainfall variability for tropical ecology]({{< relref "/publication/schwartz-2020-beyond" >}})*
    
    design:
      columns: '1'
      spacing:
        padding: ["20px", "0", "30px", "0"]
      
  - block: markdown
    id: past-projects
    content:
      title: _Past Projects_
      text: |-
        {{< spoiler text="Drought Effects in Heterogeneous Landscapes" >}}
        Future increases in drought frequency and intensity will likely have major impacts on tropical forests, but predicting drought impacts remains difficult in part because the drivers of spatial variability in drought effects are not well understood. The severity of water stress a tree experiences during drought depends on where it is located in a landscape due to spatial heterogeneity in topography, soil factors, or the competitive environment. Furthermore, vulnerability to drought differs across species and size classes, which may in turn be associated with various landscape factors. I am using remote sensing, tree demography, and functional trait data to try to better understand the drivers of spatial heterogeneity in drought response in Puerto Rican forests at scales ranging from individual trees to forest stands. 
        {{< /spoiler >}}
        
        {{< spoiler text="Drivers of Spatial Patterns of Wind Downfall Damage" >}}
        Windthrow is a major disturbance in tropical forests. Though fragmentation is thought to increase risk of windthrow, evidence for this phenomenon is inconclusive. A recent mesoscale convective system in Ucayali, Peru, which caused widespread windthrow across a highly fragmented forest landscape provides an opportunity to examine the impacts of fragmentation on vulnerability to wind damage at a landscape scale. I use satellite imagery to map wind damage and land cover, and examine the relationship between fragmentation, forest age, and severity of wind damage. 
        {{< /spoiler >}}
        
        {{< spoiler text="Dynamics of Second-Growth Forests in a Human-Dominated Landscapes" >}}
        Tropical second-growth forests accumulate carbon quickly, and could be important for carbon sequestration and conservation in tropical landscapes. Reforestation and restoration have become important parts of many national conservation and climate mitigation strategies. Understanding where and why second-growth forests emerge and persist in dynamic landscapes is key to quantifying their potential carbon storage and contributions to conservation. In Schwartz et al. 2017, I used a 28 year land-cover time series to identify spatial and temporal factors associated with forest regrowth and permanence in the and to simulate future trajectories of forest regrowth and carbon sequestration in the Peruvian Amazon. Schwartz et al. 2020 uses remotely sensed data to identify biophysical and socio-economic factors associated with reversals of reforestation across all Latin America.
        {{< /spoiler >}}
        
        {{< spoiler text="Integrating Social and Ecological Drivers of Fire Regimes in the Western Amazon" >}}
        Though most research on changing fire regimes in the Amazon has been conducted in the drier and more seasonal Eastern Amazon, fire activity has been on the rise in the Western Amazon as well. With an interdisciplinary group of collaborators at Columbia University and CIFOR, I have been involved in research to identify the climatic, biophysical, and social drivers of fire activity in the Ucayali region, Peru. We have found that climate conditions place the largest constraints on fire activity, with fire far more common in drought years but that social factors, such as land use/land cover and landowner absenteeism influence local spatial patterns of fire activity. Contrary to conventional wisdom, we found that fires are actually far more common in areas with high rates of landowner absenteeism, where fewer individuals are present to help control escaped fires and where fallow vegetation provides abundant, dry fuels. 
        {{< /spoiler >}}
        
    design:
      columns: '2'
      background:
        text_color_light: true
        image:
          filename: green-vegetation.jpeg
          filters: 
            brightness: 0.3
          size: cover
          position: center
          parallax: true
      spacing:
        padding: ["20px", "0", "20px", "0"]
---
