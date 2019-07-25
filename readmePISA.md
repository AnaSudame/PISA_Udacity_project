
# PISA data exploration

## Dataset
 The PISA data consists of a survey of students' skills and knowledge as they approach the end of compulsory education.  Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.
Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. This dataset consists of over 2 million rows and 636 columns.

# Summary of findings

Since this is was a large dataset I loaded it in chunks and then divided each chunk into three main aspects of data that I was
planning to explore. The focus of my exploration is the math subject area out of math, reading and science skills survey. The three parts that I divided the pisa data are teacher data with teacher attributes, student data with student attributes and math score data.

The main features of my investigation of this data are the math score, student and teacher attributes relationships.
The only numeric variables that I needed to explore were the duration of math classes, number of math classes per week and the math score. I had to carry out some preliminary work for calculation the weighted score from the five plausible values for scores given for each observation. Thereafter I had one score for each student.

In the initial exploration I looked at the student and teacher attributes. Students who paid attention in class and considered school as important for future for college were high in number, about 100000 than the ones who did not think so. Lesser students enjoyed doing math. Students who did not look forward to the classes had diverse range of scores  from 250 to 700.

Exploring other behavioral attitudes of students like openness to problem solving, perseverance showed that students generally did not like to give up and the ratio of students who exceeded expectations was high to the ones who did so by about 1.5.
The proportion of working mothers was almost the same as working fathers in this dataset with more number of part time working than the fathers. Retired moms were also high in numbers than the fathers. I also found that female students were a little higher in number than the male students and also were the highest scorers.
Most data showed that teachers helped students, checked their understanding and set goals more often. The count for teaching not giving any feedback was high.

More number of students were anxious about math studies, this number being above 12000 and the ones who helped friends were about 160000. Math anxious students seemed to do better with some teacher help. 

In general, majority of the scores lied between 400 to 600 for students who paid attention in class, anxious students and the ones sho enjoyed math as well. Students who are open to problem solving and not giving up or exceed expectations are higher  peak at 500 for the score values; these may also include the anxious ones.

Other than the main features,one interesting thing I found that students who enjoyed math did not necessarily think that school prepares them for future. Students whose parents are both working full time had a better perceived sense of control over their studies than the ones who had part time or non working parents.



The number of math classes per week were average at 5 and the duration of math classes was around 50 minutes on average although I saw some outliers for duration and number of classes.There was a moderately positve correlation between math score and the number of classes per week but found a negative correlation between the duration of math class and the score.
Countries like China,Japan, Spain, Vietnam initially showed highest math score and low scoring were Brazil and Uruguay.


## Key insights for presentation

 Derive insight from the combined data for teacher, student and mat score that I had divided before with only interested features. Here I look at two behaviors one of the teacher and one of the student and their effects on math score based on my previous findings. I do this one by one for a few  such combinations. Then I look at the the countries combined with a student  and teacher attribute.
 
 #### Resources/references used for this project
 
 The link that I found on Medium blogpost is  
 https://towardsdatascience.com/why-and-how-to-use-pandas-with-large-data-9594dda2ea4c
 which I used to understand how I can efficiently handle a large data like the PISA. It helped me a lot. I came upon this until I struggled for a while because it was taking a very long time for the data to load in my dataframe.
 
 I used the information provided in the link I found below in my online research to find explanation on how to use the plausible values in the PISA data.
 (Reference:PISA data analysis manual http://archivos.agenciaeducacion.cl/Manual_de_Analisis_de_datos_SPSS_version_ingles.pdf and link provided for the PISA competition)

I also used the following link to understand how to calculate the weighted average in python.
https://pbpython.com/weighted-average.html
Additionally, I used the links provided by the Udacity project instructions page for contest on PISA data. I studied the R code 
used to find the weighted average for math. It was very helpful.
