# Redesign Snow's Cholera Map

## Introduction
For the assignment 2, we were asked to redesign one of the three maps – John Snow’s Cholera Map, Minard’s Map or Nightingale’s Map. I have chosen to redesign John 
Snow’s Cholera map. John Snow's cholera map, created in 1854, is a groundbreaking example of using data to solve public health issues. During a cholera outbreak in 
London, Snow, a doctor, suspected contaminated water as the cause. To prove it, he mapped the locations of cholera cases, revealing a clear cluster around the Broad 
Street water pump. By removing the pump handle, he stopped the outbreak, demonstrating that cholera spread through water, not "bad air" as commonly believed. Snow’s 
map is now famous for advancing epidemiology and showing how data can guide public health actions to prevent disease spread.  

## Method 
I have used ArcGIS to redesign the snow’s cholera map. I chose “Light Gray Canvas” theme as a Basemap for the redesign and above it, I layered the Snow’s cholera 
map. I have incorporated may layers into the map to store information about various events of the outbreak, as the pop-ups. I will talk about this in detail in the 
second iteration. 

## Iterations
In the first iteration of my project on the 1854 cholera outbreak in Soho, London, my goal was to gather data and create a foundational map using ArcGIS. I started by researching the backstory of the outbreak, focusing on Baby Frances Lewis, the index patient, and how John Snow traced the outbreak to contaminated water sources. My research included sources like Wikipedia, Michigan State University's report *"Finding Baby Lewis"*, and a blog post from 2013, which provided digitized datasets and shapefiles. I also utilized the *HistData* dataset from R programming. After familiarizing myself with ArcGIS, I selected a Light Gray Canvas as the base map and began adding layers, including locations of water pumps, death points, and a marker for Soho. Initial layers included simple black circles for death points, which I later enhanced with color-coded legends to indicate death counts more clearly.

To make the map more insightful, I added a heatmap layer to highlight areas with high death densities and created a bubble chart to represent the relationship between death counts and geographic coordinates. I incorporated additional layers to provide contextual information, such as a grave symbol for Baby Frances’s location, a black pin for the Broad Street Pump, and a green-outlined building icon for the brewery, which served as an anomaly during the outbreak. Pop-up information was added for these points to explain their significance. Through this iteration, I effectively mapped critical elements like death distributions, key landmarks, and contextual historical information, creating a visually engaging and informative representation of the cholera outbreak.

## Final Output
![Image1](/assests/img/image(1).png)

![Image2](/assests/img/image(2).png)

![Image3](/assests/img/image(3).png)

![Image4](/assests/img/image(4).png)
