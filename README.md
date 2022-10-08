# Data visualisations with the PISA dataset  


# Topic: Possible impact of sociodemographic characteristics on performance of students.
## by Mbang Ernest Ngong


## Dataset Introduction

The PISA dataset is part of the OECD's Programme for International Student Assessment. OECD is short for 'Organization for Economic Co-operation and Development'. It is a unique forum comprised of the governments of 37 democracies where market-based economies collaborate to develop policy standards so as to promote sustainable economic growth across these countries.

The PISA survey is a survey of students' skills and knowledge as they approach the end of compulsory education. Its main aim is to examine how well students have learned the school curriculum and how well they are prepared for life beyond school.

This danalysis focused on data collected for the PISA survey of 2012. In this survey, approximately 510,000 students in 65 economies took part in the assessment of reading, mathematics and science. This data represents about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.
The PISA 2012 dataset is a huge dataset comprising approximately 635 variables however, it was narrowed down to 18 variables of interest.
Preliminary wrangling mainly comprised of renaming the variables of interest to more descriptive names and deleting dupilcates that were observed. 
Along the data exploration path, cleaning was further done to remove spaces in certain a category that allowed for further generation of visualisations.  
## Structure  
This analyis comprised of both exploratory and explanatory analyis coupled with neccesay visualisations. The notebook progress can also be viewed on kaggle [HERE](https://www.kaggle.com/code/mbangernest/part-i-exploration-template)


## Summary of Findings


In our exploratory analsysis, we started by infering individual variables of interest(univariate visualisation) and we looked at at a total of 11 variables including countries that participated in the study of which Mexico was the country with most participation. We further accessed the OECd status of the participating countries to ascertain participation proportion from them as this survey is mainly part of the OECD. We looked at the proportion of studennts who repeated classes and it was observed that most of the students had not repeated classes. Further more we looked at the distribution of our continuos variables of interest(reading strength and weighted student score) of which a farely normal distribution was observed with student reading strength and a skewed distribution was observed for weighted student score. We used mainly histograms, bar charts and pie charts at this level. For bar charts, particular attention was given to norminal and ordinal variables, plotting accordingly with respect to ordering when it came to ordinal variables. Other variables plotted included variables that assessed studensts willingness to reason math, the time at which teachers start school and also to assess if studenst see school as a waste of time.  
Following on to bivariate analysis, correlation was ran to undertsand our main continuos varaibles of interest(reading strength and weighted student score). No correlation was observed with these varaibles, suggestive that perhaps a studenst ability to read is not neccesarily a predictor of life success. heatmaps, boxplots and clustered bar charts were also used to access variables such as Weighted student score and OECD status, math reasoning effort and gender as well as weather living with a father affected truancy possibility or not.  
Finally, the multivariate part consisted of mainly using seaborn's facet grid method to look at the correlation between weighted student score and reading strength as well as between OECD and non OECd countries as correlation that was bound to be correlated as it had previously been seen at the bivaraite level though insight as to how this occured between OECD and non OECd countries was gotten. Lastly under multivariate visualisations, seaborns catplot method was used to draw violin plots separated by gender in which reading strength was compared with class repetition.


## Key Insights for Presentation

For our presentation, we looked at the top 5 countries that had most participants in this study from our univariate analyis. Furthermore, we looked at polished relationships between studenst math reasoning effort and their gender and concluded with polishing our relationship between class repetition and reading strength, done between males and females.   
  
  _This was my third project and last technical project towards my ALX funded data analyst udacity nanodegree_