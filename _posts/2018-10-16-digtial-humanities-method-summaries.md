---
layout: post
published: true
category: commentary
title: Digtial_Humanities method summaries
author: Tyler
tags:
  - Digital_Humanities
---
## **CULTURAL ANALYTICS, AGGREGATION, AND DATA-MINING SUMMARY:**

**What cultural analytics is**
This is about using computational methods and data visualization to analyze very large, and often unstructured cultural data sets. 

**Media that is analyzed**
The type of media that’s analyzed can range from images and film, to magazine covers and advertisements, to more contemporary sources like real time streams of data from twitter, texts, and search trends. Basically, anything involving social interaction and/or artistic work (in almost every sense).

**Worries and concerns about analysis**
A primary concern is how we choose our parameters for our computational models. In English: what do we tell the computer to look at when it sees an advertisement? The palette of colors? The placement of text? The text itself? How we incorporate cultural artifacts into data sets is the first stepping stone to creating responsible analyses.

**The state of data**
The data — however that may be defined — in cultural analytics is constantly expanding.
1. Volume: how much data do we have?
2. Data type: text? image? video? behavioral? biometric?
3. Production / Consumption: are the data coming from books? social media? magazines? films? IOT devices?

Because each of these properties of cultural data is constantly changing, it becomes more important for humanists to engage with the actual design of the algorithms and visualizations that analyze them. Obviously there’s a barrier to entry here with computational literacy, but high level implementation details can surely be discussed in non technical terms.

**Techniques**
To clarify, data-mining covers a range of techniques for extracting meaning and patterns from data. It is at the intersection of machine learning, AI, and statistics.
Some of the primary methods we use are:

- Association rule learning: Finding relationships and associations between different variables. If I read a lot of self-help books, what other books am I likely to buy? 
- Clustering: Finding hidden patterns. How do all of my books group together?
- Classification: Predicting information. What genre is my book?

In my own work, we do a lot of stuff with vector space models, which is an awesome way to measure the “distance” between data points and calculate how similar things are. Particularly a great example is Word2Vec, where words are represented by vectors, and their similarity can be calculated using cosine distance. This allows you to find some interesting patterns in language, such as doing algebra with words.

For example, in Word2Vec:
King - Man + Woman = Queen. Semantic concepts can be mapped and calculated much in the same way with traditional spatial data.


## **VISUALIZATION AND DATA DESIGN SUMMARY:**
Basic definition: 
Visualization and data design are representational methods, used to visually explain and clarify concepts. Obviously visualization methods employ artistic freedom, but illustration and art are obviously more free form overall. 

**History**
Initially, simple bar and pie charts came from the world of 18th century “political arithmetic.” They developed from more traditional visualization methods like diagrams, grids, and trees (although these are still obviously useful for other purposes).

**Pitfalls of cultural data visualization**
As stated earlier, these kinds of analyses are predicted on interpretation. The clarity, precision, and perspective of the data analysis all influences what the visualization says and how it is then used in analyses.

**Some common techniques cited**
Apart from more traditional techniques used for general statistical visualization, the reading cites mapping and experiential visualization as two frontiers specifically suited to visualize cultural data well.

1. Mapping
    1. In the humanities, this ranges from:
        1. “Time-layers” of historical events (similar to layer cake)
        2. Memory maps
        3. Conceptual mapping
        4. Community-based maps
        5. Counter-mapping that attempt to “un-ontologize cartography” and imagine new worlds. 
3. Experiential visualization
    1. Uses movement through the time and space of a 3D world as the primary mode of engagement. 
    2. Psychogeography: immersive and experiential wandering, coined by the Situationist group in the 50s
    3. Historical simulations: deliberately not a reconstruction of events or augmentation of the real world. it is an investigation and something that promotes new thought and analysis.

**What are some other applications? “Design thinking”?**
The reading cites that visualization can be used in many other ways, specifically to sketch out arguments, map its constituent parts or even to model its initial formulation. This process is very similar to what many “design thinking” evangelists say about the design process and how it can be applied to more abstract concepts like arguments, rather than just the layout of a page or the graphing of a data set. At the end of the day, knowing what to read and visualize as well as how to read and visualize forms is at the basis of digital literacy and the assessment of meaning in these new formats 