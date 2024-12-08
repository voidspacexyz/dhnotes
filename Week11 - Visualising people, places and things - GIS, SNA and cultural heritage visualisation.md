## Definitions


## Week Overview
Trying to read in a manner that is not linear or comprehensive may be challenge enough, but then how do we represent the intermediate and output layers of the understanding we thereby develop?  Visualisation is an art in itself, taking many forms, but always bringing together a complex weave of heuristics, data types (from human approximation through to sensor readings), images, statistical analysis into complex systems of signs and meaning, such as Geographic Information Systems or data visualisations from charts and graphs through to relationship maps and word clouds.  How can we know how to read and create them in transparent ways?



## Sources
- ### Mandatory 
- **REQUIRED READING, RESEARCH ARTICLES:**

1. Murrieta-Flores, P., Donaldson, C. E., & Gregory, I. N. (2017). GIS and literary history: advancing digital humanities research through the spatial analysis of historical travel writing and topographical literature.Digital Humanities Quarterly, 11(1). [http://www.digitalhumanities.org/dhq/vol/11/1/000283/000283.html](http://www.digitalhumanities.org/dhq/vol/11/1/000283/000283.html)
2. So, Richard Jean, and Hoyt Long. “Network Analysis and the Sociology to Modernism.” boundary 2 40, no. 2 ( June 2013): 147–182. [http://home.uchicago.edu/hoytlong/NetworkAnalysis.pdf](http://home.uchicago.edu/hoytlong/NetworkAnalysis.pdf)

**REQUIRED MATERIALS TO PREPARE:**

There is a lot here - take a look at a couple of these links to get a sense of the possibilities ahead of class.  

1. Technologies and examples for spatial approaches: The dominant platform for digital mapping is almost certainly ESRI's ARC GIS (though QGIS provides a good, free, open source alternative), however a longtime limitation on these platforms was their relative inability to represent spatial changes over time.  This gap is addressed by tools like TimeMapper (http://timemapper.okfnlabs.org/) and Nodegoat ([https://nodegoat.net/)](https://nodegoat.net/));   Another area where data-driven spatial humanities is progressed is in the development of gazetteers (a geographic index) and related projects like Recogito: [https://recogito.pelagios.org/](https://recogito.pelagios.org/)  For a good overview: [https://www.modernlanguagesopen.org/articles/10.3828/mlo.v0i0.299/](https://www.modernlanguagesopen.org/articles/10.3828/mlo.v0i0.299/).   There are lots of example projects you might look at, such as: The Down Survey (http://downsurvey.tcd.ie/history.html) or Deep Map of West Cork: [http://www.deepmapscork.ie/](http://www.deepmapscork.ie/) .
2. For social networks the sitiation is a little different, as one software programme, Gephi (https://gephi.org/), dominates.  You can see how the affordances of social network analysis are used by projects and infrastructures by looking at projects like: Mapping the Republic of Letters (http://republicofletters.stanford.edu/); DraCor ([https://dracor.org/)](https://dracor.org/)) and of course the card game (?) "Brecht beats Shakespeare": [https://dracor.org/img/merch/Brecht_Beats_Shakespeare_DH2018.png](https://dracor.org/img/merch/Brecht_Beats_Shakespeare_DH2018.png)
		
- ### Further 
- TBU



### Discussion Questions

What makes for an effective data visualisation?  A trustworthy one? How does the long tradition of mapping align with or challenge the affordances of the digital?  How do the statistics and conventions of social network analysis expose and hide information about connections between people or characters?  How canthese tools be used not just for display, but to develop different understandings of cultural or historical phenomena?

### Characteristics of Effective and Trustworthy Data Visualizations

**Effective data visualizations** can enhance understanding of historical travel writing by representing places not as isolated points but as interconnected locations along a travel route. The sources primarily discuss data visualizations in the context of Geographic Information Systems (GIS) and their application to literary and historical research, particularly travel writing.

- Point-based maps can illustrate quantitative geographic data like proximity and scale but fall short in representing qualitative human experiences like travel. To address this, researchers can employ techniques like Cost-Surface Analysis (CSA) and Least-Cost-Path Analysis (LCP).
- CSA and LCP help create spatial models that reveal how the physical landscape and road networks influence travel routes and, consequently, the travelers' experiences and written accounts.
- The sources utilize visualizations like LDA maps to identify frequently traveled routes, offering insights into collective preferences for specific areas among different travelers.
- Visualizations can highlight empirical details often overlooked in traditional literary analysis, such as the specific vantage point from which a writer observed a landscape, enhancing understanding of how physical realities shaped their perceptions.

However, the sources acknowledge the limitations of these techniques and emphasize the importance of integrating them with qualitative analysis for a more comprehensive interpretation of historical travel writing.

The sources also highlight the potential of combining GIS techniques with other emerging technologies, such as Google Earth, to create more interactive and engaging visual representations of historical journeys.

**Trustworthy data visualizations** involve using reliable sources for the underlying data, such as historical maps, to ensure accuracy in representing the historical context. It's important to note that modern DEMs, while useful, contain data about modern infrastructure that may not have existed in the past, potentially impacting the accuracy of historical visualizations.

While the sources focus on the application of data visualizations in the specific domain of historical travel writing, the principles of effectiveness and trustworthiness can be generalized to other fields.

- Effective data visualizations should clearly and accurately convey information, using appropriate visual elements and techniques to highlight key insights and patterns.
- Trustworthy data visualizations rely on accurate and reliable data sources, transparent methodologies, and careful consideration of potential biases and limitations.

The source titled "Recogito-in-a-Box: From Annotation to Digital Edition | Modern Languages Open" provides information about a tool called Recogito, which is used for semantic annotation and can help researchers visualize geographical data from historical texts. However, it doesn't specifically discuss what makes a data visualization effective or trustworthy.

The source "http://home.uchicago.edu/hoytlong/NetworkAnalysis.pdf" explores network analysis, a different type of data visualization, and doesn't directly address the characteristics of effective or trustworthy data visualizations.

Overall, while the sources offer valuable insights into effective data visualizations for historical travel writing, they don't provide a comprehensive discussion of the broader principles of effectiveness and trustworthiness in data visualization.

### Key Ideas of Each Author


- **Patricia Murrieta-Flores, Christopher Donaldson, and Ian Gregory** in _GIS and Literary History: Advancing Digital Humanities research through the Spatial Analysis of historical travel writing and topographical literature_ argue for using advanced spatial analysis techniques within Geographic Information Systems (GIS), specifically Cost-Surface Analysis (CSA) and Least-Cost-Path Analysis (LCP), to enrich interpretations of historical travel writing. They demonstrate this by analyzing 18th-century travelogues of the English Lake District by Thomas Gray, Thomas Pennant, and Arthur Young. Their analysis reveals how road infrastructure and the terrain significantly influenced travel routes and, consequently, the writers' experiences and representations of the region. They emphasize the importance of moving beyond point-based mapping to consider travel as a process, recognizing the influence of the physical landscape and the travelers' vantage points on their accounts. While acknowledging the limitations of using modern DEMs, they suggest future research should consider incorporating historical DEMs for greater accuracy. The authors also highlight the potential of integrating GIS with other technologies like Google Earth to create interactive virtual tours, fostering innovative collaborations between humanities scholars and Geographic Information Scientists.
- **Gimena del Rio Riande and Valeria Vitale** in _Recogito-in-a-Box: From Annotation to Digital Edition_ present a digital workflow using Recogito, an open-source semantic annotation tool, to create digital editions of historical texts enriched with geographic data. They illustrate this process through a case study of the early Argentinian chronicle _La Argentina Manuscrita_. They emphasize the value of combining semantic annotation and map-based visualizations for understanding historical travel narratives. By using Recogito, users can identify and disambiguate place-names, trace itineraries, and investigate historical geographies without needing advanced computing expertise. The authors demonstrate how Recogito's export options, particularly the TEI format, can be used to create digital editions that incorporate the spatial data extracted through annotation. They suggest that Recogito's integration with historical gazetteers and its ability to generate map-based visualizations provide valuable tools for researchers interested in tracing itineraries and investigating trading routes.
- **Hoyt Long and Richard So** in _Network Analysis and the Sociology of Modernism_ propose using network analysis and visualization to understand the social dimensions of modernist poetry production in the U.S., Japan, and China, focusing on the role of journals as organizers of literary activity. They argue that publication data, visualized as a network of relations, can reveal patterns and structures that traditional literary history often overlooks. Through their analysis, they identify the concepts of "brokerage" and "closure" as key dynamics shaping the literary field. "Brokerage" refers to individuals who bridge disparate groups within the network, facilitating the flow of ideas, while "closure" describes the tightening of relationships within groups, fostering internal cohesion. They challenge conventional views of brokerage, suggesting that in the literary field, those occupying broker positions are often not the most prominent figures. Their analysis also reveals that closure, while potentially limiting innovation, can also serve to strengthen group identity and enhance a group's ability to disseminate its ideas. By comparing the network structures of different national literary fields, the authors highlight the value of quantitative methods for understanding the social and cultural dynamics of literary movements. They acknowledge the limitations of network analysis, recognizing the need for further textual and historical analysis to fully understand the social and cultural significance of the patterns revealed through their visualizations.


### Limitations of Point-Based Cartographic Representations

Point-based cartographic representations, while useful for certain types of analysis, present significant limitations for researchers examining the geographical experiences depicted in literature, particularly travel writing. The sources highlight these limitations and suggest alternative approaches to address them.

- **Oversimplification of Travel:** Point-based maps typically represent locations as isolated points, connected by straight lines. While this can illustrate the sequence of places visited, it fails to capture the complexity of travel as a process, neglecting the influence of the terrain, the road network, and the various experiences encountered along the way ([Print](http://www.digitalhumanities.org/#)GIS and Literary History).
- **Neglect of Qualitative Experiences:** The sources emphasize that point-based maps excel at representing quantitative geographic data like proximity and scale but are less effective at conveying qualitative aspects of human experience, such as the sensations, emotions, and perceptions associated with traveling through a landscape ([Print](http://www.digitalhumanities.org/#)GIS and Literary History).
- **Limited Insight into Vantage Points:** Point-based maps don't provide information about the traveler's vantage point, which is crucial for understanding how they perceived and described the landscape. The sources argue that seemingly objective descriptions can be heavily influenced by the traveler's position and the physical realities of the terrain ([Print](http://www.digitalhumanities.org/#)GIS and Literary History).
- **Inadequate Representation of Unvisited Places:** Travelogues often mention places that the author didn't visit but were nonetheless part of their mental geography. Point-based maps struggle to represent these unvisited places and their significance within the broader narrative ([Print](http://www.digitalhumanities.org/#)GIS and Literary History).

The author suggest that moving beyond point-based representations and employing techniques like CSA and LCP can help researchers create more nuanced spatial models that better reflect the complexity of geographical experiences in literature. These models can account for factors like the terrain, road networks, and the direction of travel, offering insights into how these elements shaped the traveler's route, perceptions, and ultimately their written account.

Furthermore, the sources highlight the importance of integrating spatial analysis with close reading and qualitative analysis. The data visualized through maps and spatial models can serve as a starting point for deeper interpretation, prompting researchers to consider the textual details, historical context, and the traveler's subjective experiences.

By combining these approaches, researchers can gain a richer understanding of how geographical experiences are represented in literature and how those representations are shaped by both physical and cultural factors.

### Shaping Lake District Tourism Through Road Improvements (GIS and Literary History: Advancing Digital Humanities research through the Spatial Analysis of historical travel writing and topographical literature)

Eighteenth-century road improvements significantly shaped Lake District tourism by enhancing the accessibility of certain areas and, in turn, influencing the perceptions of the region reflected in travel writing.

- The construction of turnpikes and carriage roads during the mid-18th century facilitated easier and faster travel through the Lake District, particularly in the eastern region.
- This development led to increased tourism in areas surrounding lakes such as Windermere, Ullswater, and Derwentwater, as these became focal points for travelers seeking scenic beauty and picturesque landscapes.
- The accounts of prominent travelers like Thomas Gray, Arthur Young, and Thomas Pennant, who relied heavily on these improved roads, further popularized these areas.
- Their writings, widely read and influential in shaping public perception, predominantly highlighted the attractions of the eastern Lake District, contributing to its growing popularity as a tourist destination.
- One source, examining the spatial relationship between these authors' travel routes and the Lake District's topography, reveals that their itineraries closely aligned with the natural corridors formed by the terrain.
- This suggests that they primarily followed established roads, as these offered the most efficient and convenient paths through the region.
- Conversely, the western valleys, like Wasdale and Ennerdale, remained less frequented due to the lack of well-maintained roads and the challenging terrain.
    - While turnpike acts aimed at improving access to these areas were passed, the roads remained in poor condition, discouraging tourism and leaving these regions relatively unexplored compared to their eastern counterparts.

The sources emphasize that road infrastructure played a crucial role in constructing the image of the Lake District during this period.

- The focus on the eastern region, fueled by improved road accessibility, contributed to a skewed perception, emphasizing its beauty while overlooking the more remote and challenging western valleys.
- The placement and condition of roads even influenced the specific viewpoints from which travelers observed the landscape, shaping their descriptions and, consequently, the image presented to readers.

This is exemplified by the accounts of Young and Pennant, who described the journey over Shap Fell, notorious for its challenging conditions, as "dreary" and "melancholy".

- Their descriptions, likely influenced by the road's location and state of repair, highlight how road infrastructure could directly shape travelers' experiences and perceptions.

The sources argue that understanding the material realities of travel, including the impact of road infrastructure, is essential for interpreting historical travelogues and gaining a more comprehensive understanding of how tourism and perceptions of specific regions evolved over time.