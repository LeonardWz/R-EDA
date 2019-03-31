# Exploratory Analysis of Red Wine Quality

Analysis and Visualization of the Effects of Components on the Quality of Red Wine by R Language

## Preparation in advance
1. You need to install R. You can download and install R from CRAN.
2. After installing R, you need to download and install R Studio. Choose the right way to install your operating system.
3. Finally, you need to install some packages. We recommend that you open R Studio and install the following packages from the command line：
+ install.packages("ggplot2", dependencies = T)
+ install.packages("knitr", dependencies = T)
+ install.packages("dplyr", dependencies = T)

## Summary
This data set contains 1,599 red wines and 13 variables about the chemical composition of wine. Three less wine experts rated the quality of each wine, with scores ranging from 0 (constant poor) to 10 (constant good).
+ Fixed acidity: Most wine-related acids or fixed or non-volatile acids (not easy to evaporate),g / dm ^ 3;
+ Volatile acidity: Excessive acetic acid content in wine can lead to unpleasant vinegar taste,g / dm ^ 3;
+ Citric acid: A small amount of citric acid is found to add "freshness" and flavor to wine,g / dm ^ 3;
+ Residual Sugar: The amount of sugar left after fermentation stops. Very few wines can be found below 1 g/l. Wines over 45 g/l are considered sweet,g / dm ^ 3;
+ Chloride: Salt Content in Wine,g / dm ^ 3;
+ Free sulfur dioxide: Free form of SO2 has a balance between molecule SO2 (as a dissolved gas) and bisulfite ion; it can prevent the growth of microorganisms and oxidation of wine,mg / dm ^ 3;
+ Total sulfur dioxide: the amount of free and bound SO2; at low concentrations, SO2 can hardly be detected in wine, but when the concentration of free SO2 exceeds 50 ppm, SO2 becomes apparent in the taste and taste of wine,mg / dm ^ 3;
+ Density: According to the percentage of alcohol and sugar content, the density of water is close to the density of water,g / cm ^ 3;
+ PH: Describes how the acidity or alkalinity of wines ranges from 0 (very acidic) to 14 (very alkaline); the pH of most wines ranges from 3 to 4;
+ Sulfate: A wine additive that produces sulfur dioxide gas (SO2) levels and can be used as an antimicrobial and antioxidant,g / dm3;
+ Alcohol: Percentage of alcohol content in alcohol,Volume%;
+ Mass (fractions between 0 and 10)

## Design
1. Univariate Analysis,Distribution of each component in red wine was listed by bar chart.
2. Bivariate Analysis,Using box diagram, draw the relationship between each component in red wine;Among them, the correlation coefficient between pH value and tartaric acid content in red wine was the largest, 0.68.
3. Multivariate Analysis,The correlation among the three variables was studied by adding color information to the bivariate analysis chart. From exploratory analysis and drawing of multiple variables, it can be clearly seen that the quality of red wine is getting higher and higher in citric acid and sulphate content under the condition of certain alcohol concentration, while in the same case, tartar has obvious negative effect on the taste of red wine. Acids and acetic acid weaken the quality of red wine.

## Reflection
1. Red wine, as one of the wines, is accepted and even loved by most people all over the world; it originated in France and is popular in the contemporary era, especially for high-quality red wine, the identity symbols and expensive prices behind it have evolved into a consensus.
2. Although the composition of red wine is very simple, there are many factors affecting its quality; through careful study and exploration of these factors, we can find that some components can improve the quality and taste of red wine, such as citric acid and sulfate content in wine; while some components can reduce the quality of red wine, such as volatile acidity (acetic acid), SO2 concentration in wine, and so on.
3. In the process of exploring this project, we encountered too many difficulties and helplessness; especially in the process of exploring and analyzing multiple variables, we are most impressed by the difficulties. Firstly, when analyzing the quality of red wine as the third variable, we did not take into account the need to convert it into factor (), resulting in no gradient of color in the image; secondly, when using ggpairs function. Not taking into account some details, such as setting the size of the graphics and so on, it was found that the effect of the image was greatly affected. Others included some text instructions after the image, which could help the reader understand the author's intention very well.
4. For the expansion of the data set, I think we can do some daily store prices of several types of red wine, and then do a market survey to see the different needs of families of all classes for daily purchases of red wine.
5. They all say that red wine is a "diamond" drink, so in the end, quote a famous saying from the diamond industry to conclude this exploratory analysis, "diamond lasts forever, red wine accompanies beauty"!

## Resources
https://github.com/udacity/new-dand-advanced-china/blob/master/%E6%8E%A2%E7%B4%A2%E6%80%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90/%E9%A1%B9%E7%9B%AE/%E6%8E%A2%E7%B4%A2%E6%80%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90_%E6%95%B0%E6%8D%AE%E9%9B%86.md
