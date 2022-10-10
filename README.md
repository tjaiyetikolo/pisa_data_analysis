# PISA 2012 Data Exploration
## by Tioluwani Jaiye-Tikolo


## Dataset

> PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.
Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy. The dataset can bee found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip), with its data dictionary dound [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv).


## List of libraries used

> numpy
> pandas
> matplotlib 
> seaborn


## List of files included

> Part_I_exploration_template.ipynb is the jupyter notebook file used in exploratory and explanatory analysis.

> Part_I_exploration_template.html is the .html file of Part_I_exploration_template.ipynb

> Part_II_slide_deck_template.ipynb is the jupyter notebook file for the slideshow created using the finding from Part_I_exploration_template.ipynb

> Part_II_slide_deck_template.html is the .html file of Part_II_slide_deck_template.ipynb

> pisa2012.csv is the dataset used for the analysis

> pisadict2012.csv is the dictionary file of pisa2012.csv containing all the columns and description


## Summary of Findings

> Numerical features of interests were explored against categorial variables. Total scores was explored more in this section with parents schooling for instance. In this case Level 3A was stated in the previous section as one of intrest and it was proved correct as most students fell under parents with this level. Also in the case of troublesome attitude, students whoa agreed to this had higher rates of disagreement from maths intrested and vice versa proving the assumption of troublesome attitude not beeing associated with math interest. On out of study subjects of maths and science. Students of high scores pass the mean who studied more of science studied less of maths across multiple hours and students of socres less than the mean did not study much either maths or science except in the 6+ hours mark of science which had a higher rate. The correlation of maths, reading, and science scores are is strong showing that instance of math lessons, students who strongly agreed to it rised as much as students who disagreed. As such, it is expected that this could be applied to other categorical variables to since the correlation between the three features are quite high. Lastly it is summarised that no late turancies truly improve the total scores of students, mother with part-time jobs and fathers with full time jobs have childer with higher total scores. This seems intresting as parents job stability played a part in the scores of students.


## Key Insights for Presentation

> For the presentation, I focus on the influence of the most looked at features against math, science, read, and total scores and introduce them in order. Aftewards the categorical features of interest are to be plotted against total scores one by one with violin, box, and scatter plots.