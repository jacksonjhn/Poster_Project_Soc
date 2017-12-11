# Poster_Project_Soc


### Project Topic and Relevance


The topic I originally wanted to work on was relating social capital to educational attainment in students. I originally wanted to see if different social capital measures affected the choice in majors that students selected in their educational experience at Universities. However, this project changed into seeing if different cultural capital measures change how students view their potential of obtaining graduate degrees. 


The relevance of understanding education has become a more contemporary topic in recent years due to under performing schools and the cutting of budgets to schools that are already disadvantaged. As Sociologists it should be important to understand education and attempt to find what works and doesn't work for educating people. Education is an invaluable resource not being given as effectively as it could and by studying the machinations of education more in depth we can see in what ways we can improve our current and future education systems.


The area of research into education at collegiate level is still a relatively under researched area in Sociology. Cultural capital in the context of my project was examining the effect of cultural capital imposed by parents (or guardians) onto their children. These measures are things such as punishing children for bad grades, checking children's homework, etc,. The importance of seeing how various cultural capital measures affect students' beliefs in their capabilities of obtaining higher education is a very important topic to study. By examining what processes parents can do in order to develop their children into having a mindset of obtaining a high degree of education (such as a graduate degree) can be very beneficial not only to the parents but also to their children. 


### Finding Data


I initially had a very hard time finding my dataset, the National Longitudinal Study of Freshman Dataset (NLSF). This dataset, once found, gave me the impression I was in the clear. However, the NLSF dataset is an oddly arranged dataset since many of the variables are not consistent throughout all five waves of the study. The dataset would most likely be excellent for someone interested in studying racial disparities in higher education, but there was a mismatch between what I was hoping to get from the set and what the study the dataset was actually made for wanted. 


Midway through my quarter I considered changing my dataset to the NELS, however, I decided to stick with the NLSF for sake of the time constraint I had. Due to the NLSF not having the variables I wanted to use consistently measured throughout the whole study, I decided to do a cross sectional analysis of the wave one dataset.


As the quarter went on I had developed three general questions I wanted to try and answer using my dataset. The first is, are different demographics of students underrepresented at different types of institutions? Second, do students perception of their capabilities of completing a Graduate degree depend on different identifying characteristics? Lastly, are student’s perceptions of their capability of completing a Graduate degree dependent on different types of cultural capital placed upon students by adults in their household? The three questions I ended up analyzing are primarily out of exploratory analysis in order to help me develop an avenue of research I can read into in order to generate a thesis question. My questions developed more towards the end of the quarter as my research thesis for my sociology honors class ran into more and more roadblocks along the way. However, I feel this research project helped me generate some idea into what I may be able to potentially research.


### Data Structure and Data Munging


Now that I look back I realize fairly clean and required little transformations of the structure of the data. The NLSF dataset had a large swath of variables to choose from, which is most likely the reason the dataset was hard to work with. The large quantity of variables caused me to spend a lot of time reading through each of the five codebooks to see what variables I could use. I think the time spent looking into the NLSF dataset codebooks could have been better spent by looking at other data sources, such as the National Education Longitudinal Study (NELS). By dedicating so much time into looking only at the NLSF, I could have looked at the NELS, which has social capital measures. The only reason I didn't switch to looking at the NELS dataset was because the dataset looks only at children from 8th grade to 12th grade and sometime after. In retrospect I should have used the NELS dataset instead of the NLSF dataset. When it came to cleaning the data the process was fairly easy. The two biggest challenges in cleaning NLSF was creating new variables by combining and dividing two new variables to represent museum visits and the second challenge was transforming all of the variables into numeric variables so I could use them to conduct data analysis and visualizations.


Creating visualizations was by far the most difficult part of working with my NLSF subset. The biggest difficulty was creating meaningful visualizations, due to my data being mostly categorical. To help relive the difficulty of working with only categorical data I used an R package called vcd to create a mosaic plot. The only problem with working with vcd is that there was not a ton of examples to help me learn how the package works. The other difficulty was creating violin plots for my data, by the time I started working on creating them I had little experience working with ggplot2, due to spending too much time messing around with vcd. I was most surprised in this project process with how difficult creating meaningful visualizations is for data analysis. I honestly thought generating visualizations would be the easiest part of the process.


Running statistical analyses in r was fairly easy and straightforward with my dataset, with the only issue coming from having categorical variables in the dataset. I overcame categorical variables by factoring them, however, by factoring the variables another problem arose that I knew how to fix but realized it too late. Two of the variables I factored were race and college choice, both of which are ordinal. If I could go back and knew I would be factoring race further on in my analysis, I would have recoded race into a series of dummy variables and have each one indicating the category of race the respondent falls into. I would have done the same process for college selection as well. By factoring these variables in my analysis the first ordinal ranking is removed from the variable, thus losing a certain parameter of the variable. However, I still feel that by factoring these variables I did the next best thing. The factoring of the variables still divides the rest of the levels of the variable into individual analyses which is most likely still accurate than just analyzing the variable as a whole.


### Reproducible Research


The most value aspect of reproducible research is to be able to confirm another researcher's result is true and the result can be reconfirmed by other researchers. Along with being able to be tested, the research methods and program code from a previous researcher could be valuable in helping other researchers in knowing what has already been tested and how they can continue research into the topic at hand. If researcher's leave details of their analysis of a topic they can give in depth insight into how their analysis was conducted and how their specific methods influenced their results.


My project included two different ways in enabling my research to be reproducible. The most important of the two is my utilization of github. Github allowed me to upload the process of myself working with the data and share my progression through researching my topic of interest. The second way I created reproducible research is from my answers to questions in the labs for the class, by answering questions I was able to look back and see how I thought about the problems then. The only issue blocking some of my reproducible research is due to the dataset I was working with, the NLSF dataset had stipulations on what I could show. Therefore, some of the labs and code I conduceted for this course could not be uploaded to github for viewing.


In the future, I have two different methods I would want to use for reproducible research. The first would be to upload my practice R markdown files, which I use to manipulate longer strings of code so errors don't interfere with the original file. The reason I could not upload my practice R markdown files for this project is because they had information on them the NLSF dataset said could not be shown. The second change I would want to do would be not to remove any code from these practice files, leave my initial comments, and organizae them separately by topic. I believe by leaving detailed strings of code showing my process of finding what works and doesn't work would be helpful to fellow researchers trying to work with my code.




