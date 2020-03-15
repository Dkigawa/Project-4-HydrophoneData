# Project-4-HydrophoneData

Links to stuff

# Introduction:
The goal of project 4 was to work with and understand the uses and applications of Hydrophone data. The data was sourced from the Ocean Obervatories Initiative (OOI) website which provides select an instrument and access the data they have collected from various locations. Part 1's task was to analyze how the weather could effect underwater noise, to do this we compared two statations at during different weather situations, comparing the Oregon Shelf site and the Oregon Offshore site. In part 2 the task was to plot spectograms of specific sounds captured by different hydrophones; specifically an air gun going off, marine mammal vocalization, and a earthquake or volcanic eruption. Then compare the bandwidths from the specograms with the Wenz Curve. 

# Part 1)

## PSD vs Frequency graphs:


### Calm weather at each location
![](https://github.com/Dkigawa/Project-4-HydrophoneData/blob/master/Shelf%20Calm%20Weather%20PSD.png)
![](https://github.com/Dkigawa/Project-4-HydrophoneData/blob/master/Offshore%20Calm%20PSD.png)

### Rainy weather at each location
![](https://github.com/Dkigawa/Project-4-HydrophoneData/blob/master/Shelf%20Rainy%20PSD.png)
![](https://github.com/Dkigawa/Project-4-HydrophoneData/blob/master/Offshore%20Rainy%20PSD.png)

### Windy weather at each location
![](https://github.com/Dkigawa/Project-4-HydrophoneData/blob/master/Shelf%20Windy%20PSD.png)
![](https://github.com/Dkigawa/Project-4-HydrophoneData/blob/master/Offshore%20Windy%20PSD.png)

### Stormy weather at each location
![](https://github.com/Dkigawa/Project-4-HydrophoneData/blob/master/Shelf%20Stormy%20PSD.png)
![](https://github.com/Dkigawa/Project-4-HydrophoneData/blob/master/Offshore%20Stormy%20PSD.png)

## part 1 analysis:
#### What is the effect of wind and rain on underwater noise? Explain any behavior you observe in your result
When focusing on the shelf data this compairson is difficult, this is because our control calm weather, exhibits the highest (loudest) measurement. For the shelf location the rainy graph trend is almost entirely below 0 dB, meaning that most of the underwater noise is unaudible to humans. This suggests that rain would not have a signifigant effect on the underwater noise. This is supported by that raindrops would create pressure wave when they hit the water, however since each individual drop is small they do not make much sound. The windy graph suggests that there is a correlation between windy times and higher underwater noise. The average in the windy graph is aproximately 45 dB, which is a signifigant difference from the rain dB. 

However when analyzing the Offshore graphs this pattern does not continue. Instead all the graphs exhibit the same general trend, making it hard to atribute any major differences due to the weather. Interestingly for the Offshore location, that all the graphs except the rainy graph, exhibit two peaks around the same two frequencies. One around 11,000 Hz and the other around 14,000 Hz, this would need further study to draw any conclusions because it could be sourced from many lurking variables. Things like ships or marine creatures could atribute for these shared traits amount graphs

#### Which one has the highestimpact? Rain or wind?
The largest differnces can be seeen in the Shelf Graphs, the Windy graph averages around 45 dB, where for rainy weather in the same location, the average is below 0. This suggests that wind would have a much higher impact than rain. However the average for stormy weather, rain and wind present, is below 0 dB as well. Meaning even though wind is present the sounds is much quiter, this suggests that either the rain dampens sounds in the ocean, or that there is an external factor independent of weather on the sound. It is possible that on the day for the windy measurement there was a boat festival which could cause lots of external sound without us being able to tell. 


#### What are the main reasons for observing different spectral levels in Oregon shelf compared to Oregon offshore? 
The depth for the shelf station is 80m below sea level, whereas the Offshore location is 500m deaper. while these devices are reletively close to eachother it allows us to compare what sounds are relevant at different depths. This allows us to visualize a sound profile for the ocean, allowing us to study the effects of sound on specific depths and locations. This could especially important for specific types of marine life that spend the majority of their life at specific depths. 

# Part 2)

![](https://github.com/Dkigawa/Project-4-HydrophoneData/blob/master/MMSpectogram%20Big.png)

![](https://github.com/Dkigawa/Project-4-HydrophoneData/blob/master/MMSpectogram%20Zoomed.png)

![](https://github.com/Dkigawa/Project-4-HydrophoneData/blob/master/Airgun%20Spectogram%20Big.png)

![](https://github.com/Dkigawa/Project-4-HydrophoneData/blob/master/Airgun%20Spectogram%20Zoomed.png)

![](https://github.com/Dkigawa/Project-4-HydrophoneData/blob/master/Earthquake%20Spectogram.png)

![](https://github.com/Dkigawa/Project-4-HydrophoneData/blob/master/Wenz%20Curve.png)

# References:
[1] Shima Abadi. In Class Lecture

[2] Discovery of Sound in the Sea. 2020. What Are Common Underwater Sounds?. [online] Available at: https://dosits.org/science/sounds-in-the-sea/what-are-common-underwater-sounds/

