# teacher_friendship_network
This project experiments on how network measuring methods work on the dataset teacher friendship network. The package that I used in this one is igraph.
# Table of content

  1. title, author information, and a table of contents
  
  2. narrative summary of the project (1 - 2 paragraphs explaining what you did)
  
  3. a code chunk showing your setup process, including the packages used and reading of the data sets and creating graph objects
  
  4. network plots for each data set used include narrative summaries of my strategies for each network above the code chunk that includes the plot
  
  5. a final (1-2 paragraph) summary of what I want readers to take away from my work 
  
#   Summary:

  The dataset used in this project was from Cohesion and Centrailty, which is teacher friendship network. I think I can advance the skills by utilizing this dataset. I utilized the skills combined from that assignment, along with advancing the dataset with the markdown and the knowledge that I learnt from community assignment. I think after having chance to take part in doing these assignments, I really enjoy the combination of plot visualizations with markdown, it is perfect for R!! 
  The steps that I approach this assignments are:
  
  1. Load package and dataset, then convert into data and graph object
  
  2. Find the weak components, density, compactness, global clustering (transitivity), in degree, betweenness, then finish this part with a plot of betweenness
  
  3. Moving on to the next interesting part with lots of plots, which are fast greedy, dendrogram, edge betweenness, multilevel, infomap, then par those plots together
  
  4. Finish up with heatmap (this is someting new and really interesting!!)

  Personally, I think the assignment altogether brings me a totally new experiences with the dataset. I learned a lot by every step of the assignment. Especially the later part (3,4), the plots help explain the 1,2 part as well since it is visually explained. There are some nodes that are not connected to each other, but mostly are teacher who know each other pretty well, that is why it forms a big cluster in the plot. If i have to pick the part that I think that really makes used in real life experiences us part 3, I think it explains well every other part by just looking at the plot. 

  About the dataset:
  
  - friendship: this matrix shows directed friendship ties among teachers (i.e., a directed tie, i->j, is present if teacher i indicates they are friends with teacher j.
  - attribute_file: contains node-level characteristics of the teachers (and principal) in the network. 
