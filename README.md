# LifeSatisfaction
Investigating the aspects of life that have the greatest impact on life satisfaction

Most humans share an innate yearning to find satisfaction and happiness in their lives, and it is this yearning which led me to create this project. This project looks at the current happiness, annual income, and many other aspects of the lives of Somerville Residents to find out what has the greatest impact on life satisfaction. I use Multiple Linear Regression and Ordinal Logistic Regression models to find and analyze the aspects of life with the strongest relationships to life satisfaction. 

## Table of Contents
* [Installation](#Installation)
* [About Somerville](#About)
* [Project Motivation](#motivation)
* [File Description](#description)
* [Results and Insights](#Results)
* [Limitations and Further Questions](#Limitations)
* [Licensing, Authors, Acknowledgements](#licensing)

## Installation
To get started you will need a recent version of RStudio. Additionally, the packages used in the project can be downloaded running the following at the command line:
    
        install.packages(c("dplyr", "kableExtra", "knitr", 
                            "ggplot2", "stringr", "MASS", "caret"))
                            
## About Somerville <a name="About"></a>
Somerville is a city located in Massachusetts, United States. It is about three miles northwest of the city of Boston and has a population of 81,360 people. The residents of Somerville responded to a survey that asked about  the level of satisfaction they had towards their life in general. Additionally, a series of questions were asked about personal and environmental aspects of the individuals' lives.   

## Project Motivation <a name="motivation"></a>
My goal is to investigate the questions asked to the residents of Somerville in order to identify the aspects of life with the strongest relationship to happiness. Happiness is a state which is rather challenging to quantify and attribute, so I do not intend to find the source of happiness. However, I am excited to learn more about what the happy people of Somerville have in common. I am thrilled to see what interesting connections I will discover in this happiness survey.

## File Description <a name="description"></a>
This project includes:
1. one csv file with all the necessary data
2. R Markdown with all the code to clean and analyze the data titled Somerville-Life-Satisfaction-Project_Summary.Rmd
3. the pdf produced using the R Markdown titled Somerville-Life-Satisfaction-Project_Summary.pdf 

## Results and Insights <a name="Results"></a>
*The conclusions reached in this paper extend only to the residents of Somerville. Any recommendations made are based on reasoning but are not backed by statistical evidence given that the residents of Somerville are not representative of the general population. Please take these recommendations at your own risk and with a grain of salt.*  

1. Current happiness affects how satisfied Somerville residents are with their life.
- This comes as no surprise, considering that general life satisfaction is but an extension of momentary happiness. However, it is interesting to question to what extent our current state of happiness may affect our perception of life satisfaction. 

2. The people of Somerville are more satisfied with their life when they are satisfied with the place where they live.
- Although this conclusion cannot be extrapolated to everyone else in the world because Somerville is not a representative sample, there is something intuitive about the conclusion. 
- Next time you are looking to improve your life, maybe you can move to a place which you are highly satisfied with!
- If this is not a feasible option, then you can redecorate your house or room. This satisfaction could permeate to your state of happiness.

3. The people of Somerville are happier when they deem that those around them are similar to them.
- Oddly enough, this question does not specify whether people are similar in terms of ethnicity, socioeconomic background, or general interests. Therefore, I presume that the question is open to interpretation. Responses might simply translate to how much people feel like they fit in with the members of their community.
-  Maybe they share your cultural background, interests, or simply your sense of humor. If you are looking to improve your life then finding a group of people that you feel similar to is a good start!

## Limitations and Further Questions <a name="Limitations"></a>
**Limitations**  
1. The data had some promising variables, such as effectiveness of local police, that I was not able to use due to missingness. These variables were potentially important and could have told us more about what affects the life satisfaction of the residents of Somerville, but they had to be dropped.
2. The residents of Somerville are not representative of the general population of the United States. Somerville, Massachusetts is no representative in terms of racial composition, socioeconomic background, and many other important characteristics. This limits the implications of our findings to only the people of Somerville. 

**Further Questions**
1. How would a sample representative of the population of the United States respond to the questions asked in this study?
2. Is there a way to garner a higher response rate for the questions that seemed potentially important but that resulted in a lot of NAs? Could we redesign the questions or response type to make the questions more welcoming to a response?

## Licensing, Authors, Acknowledgements <a name="licensing"></a>
The data used for this project came from the following page:
[Somerville Happiness Survey responses - 2011, 2013, 2015](https://catalog.data.gov/dataset/somerville-happiness-survey-responses-2011-2013-2015) 

Feel free to play around and use the code used in this project!
