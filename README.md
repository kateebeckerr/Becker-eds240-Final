
# How Have Salmon Fisheries in Alaska Changed Since 1985

The overarching question of this analysis is “How have salmon fisheries in Alaska changed since 1985?”. In order to tackle this broad question, on a more finite scale, I asked: 
1. What is the distribution of yearly fish yields for all five species of salmonoid?
2. How have nine of the most commercially important fisheries changed in terms of yearly catch?
3. Can we see clear trends in the time series data that can be accounted for by changes in Alaskan fisheries management?

## The data
1. Publicly available data set provided by the Alaska Department of Fish and Game. The data set is composed of 9 variables: year, area, species name, number of fish(estimated), landed weight(lbs.), whole weight (lbs.), permit count, processor count, and vessel count. Although all variables are equally important, I modified my data set to only include year, species name, number of fish (estimated), and area in order to make R more computationally efficient. The data set is a .csv and was available through a report including harvest attributed to state managed fisheries, test fisheries, commercial sale o derby fish, and Annette Island fisheries. A better outline of the variables used in this analysis are listed below.

Year: the year the landings occurred as recorded on ADF&G fish tickets
Area: Areas define by groupings of statistical areas as recorded on ADF&G
Species name: The species as recorded on ADF&G fish tickets
Number of fish (estimated): Number of animals is a count of each species in the catch or harvest.

2. Alaska shapefile used to spatially map nine commercially important fisheries. The shapefile was publicly available and provided by iGISmap, an online data platform that provides GIS maps.

## Design elements
1. Graphic form: A radar plot, line chart, and a geo-spatial map. I wanted to explore more complex styles in this analysis, and I felt that the radar plot provided an aesthetically pleasing chart, one that resembled a sonar on a boat, for visualization of salmon catch by region in 1985 and 2023 to show change overtime. For the line graph I wanted to clearly show the distribution in salmon catch by year by species to create a visualization that included all components of my data set. I used this graph as my primary plot because I felt that any viewer of this info graphic would be able to gather the main takeaways of the analysis from a quick glance. Finally, I created a map to add a geographic context to show fisheries proximity to one another and locations in Alaska as well as provide the viewer with a non-complex visualization.

2. Text: For most of my visuals I changed the aesthetics of the labels and titles. I used limited text in most of my plots, except the line chart because I felt that the radar plot spoke for itself and would be crowded with excess information. A lot of information can be gathered from a radar plot with simply a categorical and numeric. For the map, I removed latitude and longitude values to make it look cleaner but included labels to clearly display the fisheries locations. Finally, the line chart included all text components except grid lines because I felt a viewer can still see clear patterns in the data set without minor and major lines. I also included all years on the x- axis for it to be an effective time series visualization.

3. Themes: I altered the theme elements pretty drastically in all three of my plots. This was necessary to have the text aesthetics, outlined above, that I wanted. Most theme elements included changes in legends, color bars, ticks, titles, the panel, and major and minor grid line.

4. Colors: I used salmon themed color palettes found online and a light blue background to resemble water.

5. Typography: I used the same font for each visualization so that it would be cohesive in the infographic.

6. General design in my infographic: I let the visualizations speak for themselves by only including brief comments in order to tie the visualizations together with more background information. As stated above, I also centered and increased the size of my question and the line chart so that the viewer focuses their attention on the most important aspects and the main takeaways from this info graphic. I also used the same color scheme (salmon color hex codes) for the text and the visualizations

7. Contextualizing the data: I was able to conceptualize the data by using the same time scale throughout all visualizations. I also stayed consistent with using number of fish (estimated) as the primary metric for fishery success.

8. Centering the primary message: I used my line graph as the center of my infographic and printed my primary question above it in order to highlight the main takeaway before a viewer dives deeper into the more complex visualizations.

9. Considering accessibility (e.g. colorblind-friendly palettes / contrast, alt text): I highlighted specific words in my infographic so that viewers can gather the main message by skimming the page rather than having to read through all of the text.

10. Applying a DEI lens to your design: Salmon fisheries are a major part of Alaska’s economy and have provided native tribes with food for the last century. Unfortunately, overfishing of Alaska salmon and other native fish, by international fishing companies, have diminished food resources as well as impacted historic cultural significance. Although this analysis was able to provide insight into the change in fisheries overtime, it doesn’t dissect the sustainability of these fisheries, who profits the most, who receives the majority of the catch, or how indigenous populations are affected. This is a primary analysis and can be greatly improved in terms of a DEI lens.
