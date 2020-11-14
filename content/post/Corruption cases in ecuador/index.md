---
title: 'Corruption cases in ecuador: A Network Approach using Twitter Data'
subtitle: ''
summary: I made a Social Network Analysis of the main actors using Twitter data of hashtags about corruption in Ecuador.
authors:
#- admin
tags:
- Networks
categories: []
date: "2020-11-06T21:00:00Z"
#lastmod: "2019-04-17T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Set captions for image gallery.
---


I made a Social Network Analysis using _Twitter Data_ from 2020-04-01 to 2020-07-15 and used hashtags such as: _#corrupcionecuador_, _#iess_, _#danielsalcedo_ and others. In this analysis, I wanted to analyze the behavior of people on Twitter regarding corruption cases in Ecuador and discover which were the groups that dominated this topic on Twitter. I also used a Centrality Metric like **"Eigen Centrality"** and the Modularity as a metric for clustering.

### Network by clusters {style=text-align:center}
![Sentiment Metric](ima2.png)

The nodes and text size are based in the Eigen Centrality value; the links between nodes represent the number of mentions in a tweet. Also, the nodes color is based on the modularity metric. And using this clustering metric I found 20 clusters. As you can see, the main clusters are about state prosecutor's office, government, political parties, hospitals, statal assembly, TV channels.

Moreover, the main nodes in the network are:
- State prosecutor's office
  * Fiscalia Ecuador
  * Diana Salazar
- Hospitals
  * IessEc
  * Jorge Wated
- Government
  * Otto Sonnenholzner
  * Maria Paula Romo 
  * Juan Sebastián Roldán
  * Lenin
- Political parties
  * Mashi Rafael
- Statal assembly
  * Asamblea Ecuador
- TV channels
  * Teleamazonas


A few days later, I made a similar analysis but I used the hashtag #QuienRepartioLosHospitales, and this new data was from 2020-08-13 to 2020-08-16. During these days there were many corruption accusations directed to the Minister of Government (**Maria Paula Romo**) and caused that the main actor from the network change.

### Network by clusters {style=text-align:center}
![Sentiment Metric](ima3.png)


As you can see, in the network there are 2 groups that dominate the discussion on twitter on these days. The first group is in top of graph and its principal actors are Maria Paula Romo, Lenin, Fiscalia Ecuador. The second group is the bottom and its principal actors are Rafael Correa and many TV channels.


