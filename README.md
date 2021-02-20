<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Artificial intelligence helps maintain a healthy forest

Final project for the Building AI course - Building AI course project

## Summary

Extreme weather as a result of climate change is about to challenge the forest industry. Artificial intelligence has the capabilities to compare aerial and satellite images before and after a storm. This could make it profitable for forest landowners in for example Sweden to handle storm felled timbers. 


## Background

Climate changes in combination with modern forestry could imply an increased risk of storm felled trees. Climate changes could unstable the weather which results in increased storm frequency. Storm felled trees that remains in the forest makes it easier for bugs such as the European spruce bark beetle to attack and damage healthy trees. The global warming with higher temperatures accelerates the attacks of trees. The modern forestry with large interconnected areas with timber felling creates landscapes where the wind could accelerate and result in even more storm felled trees.

My personal motivation for this subject lies in the fact that I am a forest landowner and affected by storm felled trees. Most of the times there are small quantities of storm felled trees which makes it hard to hire an entrepreneur with the proper forest machines. The cost overruns and there is not profit. Besides I work full time as a software engineer so my time in the forest is limited.

I live in Sweden and in this country there are approximately 300,000 small scale forest landowners who could benefit from this AI solution.


## How is it used?
This AI solution could be used by the forest industry or forest owners associations to coordinate the logistics of storm felled timber and deliver it to the sawmill. Hopefully so that a profitability arises.

Each year around springtime the forest should be photographed by airplane or satellite. AI compares the images with previous years images and identifies storm felled trees. Furthermore AI will be able from the x, y coordinates to identify soil conditions and road networks. Soil conditions are needed for which kind of forest machines to use, for example tyres or tracks. Road networks are needed for information about logistics. AI will also analyze the detected areas in combination with scheduled felling in the neighborhood to coordinate the best route.


## Data sources and AI methods
Supervised learning is used.

The process, training:
- Create training data based on my home area.
- Build a model that classifies area of storm felled trees.
- Adjust and validate the model

The process, testing:
- Aerial images over a test area photographed both before and after a storm.
- Data from the Swedish Forest Agency containing soil conditions and scheduled felling for the test area.
- Data from the Swedish National Land Survey containing roadmaps, forest property maps and property owners.
- Generate test data from sources above
- Run the model
- Validate the predictions with forest industry, forest owners or forest entrepreneurs.


## Challenges
Sweden is a large county by forest area and photographing needs to be done every year between the snow melting and the leaves budding for best result. 


## What next?
Contact forest industry or the forest owner association in Sweden and pitch the idea. Start with a test project in a delimited region in Sweden.


## Acknowledgments
* The two courses [Introduction to AI](https://course.elementsofai.com) and [Building AI](https://buildingai.elementsofai.com) at the University Of Helsinki
