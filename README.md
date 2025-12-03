# Data Visualization Project

## Data

The data I propose to visualize for my project is a dataset that describes information about individuals and how much they pay in health insurance charges. From this dataset, some informaqtion like age, sex, smoker, and region are things that stand out as interesting. I obtained this data set from https://www.kaggle.com/datasets/mosapabdelghany/medical-insurance-cost-dataset.


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * How do insurance charges change as people get older?
 * Is there a correlation between being a smoker and how much insurance charges are?
 * Are there are any relationships between health insurance charges and what region a person is from?

## Sketches

![Sketch 1](Sketch1.png)

This first sketch is a very basic graph comparing age to insurance charges, predicting that charges will increase with age.

![Sketch 2](Sketch2.png)

This iterated sketch adds colors indicating whether the individual is a smoker, as well as adding a tooltip that displays more information about the individual.

## Prototypes

Week 5: I first created a proof of concept visualization of this data. It's a scatterplot and it shows the relationship between age, smoking, and health insurance charges. It also shows a trendline for smokers and non-smokers and includes a tooltip showing more information.

[![Prototype 1](Prototype1.png)](https://vizhub.com/john-ngo1/cf3553cf31a34670b4a6ec399b1ac4ff)

Week 6: I also created another visualization that describes that relationship between number of children, region, and insurance charges through grouped bar graphs.

[![Prototype 2](Prototype2.png)](https://vizhub.com/john-ngo1/294330fd3d8747a9bc5e04efd7143974)

Week 7: I then went back and edited my original prototype in order to make a cleaner look using boxplots. Since there are so many datapoints, it would be easier to understand statistics like median using boxplots. I also added the number of indidividuals in each category.

[![Prototype 3](Prototype3.png)](https://vizhub.com/john-ngo1/b7481502477d47c1b96a41bcd4fac29e)

Week 9: Going back, I tried to fully understand my data and attempted to find the most interesting relationships. Here, I visualized BMI and number of children in the graph comparing age and insurance charges.

[![image](BMI_Prototype.png)](https://vizhub.com/john-ngo1/1ff4b4979bc64d7a81d240d7a0bdd29c)
[![image](Children_Prototype.png)](https://vizhub.com/john-ngo1/9246d31387f14f6c9487755326dbfab7)

Week 10: After seeing these visualizations, I wanted to create a new visualization that combined all of this information, leading to my fourth prototype, which includes a attribute selection pane that allows all attributes to be visualized.

[![Prototype 4](Prototype4.png)](https://vizhub.com/john-ngo1/6f4b0d2034f5430a8a705d39c4e7d6ff)

Finished Product: I made small changes to the graph in order to increase visiblity, such as making all the points slightly transparent and adding jitter, which helps to differentiate between points better. This visualization shows the clear positive correlation between age and insurance charges, as well as the very prominent correlation between smoking and insurance charges. However, none of the other attributes seemed to have a strong correlation with insurance charges.

[![Final Draft](Rough_Draft.png)](https://vizhub.com/john-ngo1/758f14b8770f4af6a08c54e60b9eff18)

## Results

I was able to create an in-depth visualization that has the capability to see the relationships between multiple different attributes. Focusing on age and insurane charges, the visualization allows for coloring by other attributes like BMI and number of children. From this, we have learned that there is no significant relationship between BMI, number of children, or region and insurance charges, but that age and being a smoker do have a large impact on the amount of insurance charges an individual pays for. 

## Future Goals

Some of the goals that I was not able to implement that might be able to be added in the future are adding more data and adding more attributes. The dataset that was used had 1338 instances, which is relatively small for how many people in the US pay health insurance. Furthermore, the dataset contained age, BMI, smoker, region, and number of children, but I would love to delve further and explore attributes like race, gender, health status, economic status, and other demographics.
