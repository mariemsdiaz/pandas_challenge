# pandas_challenge


In this assigment we used and created Pandas DataFrames to analyze school and standardized test data.
Code was generated with the help of past class activities, and online search tools to modify syntex. In particular
the use of ChatGPT to help define the code logic and arithmetic. 


The following is an analysis of the PyCitySchools. 


I started with merging the school_data scv with the student_data csv file, so this way we only one summarized dataframe to reference.
We want to focus on how our distric is doing, as opposed to Charter School. I create another dataframe that summarizes students performace 
across the board, with school types being Disctric and Charter. This data frame is large, so we have to continue zooming in to see what trends we can deduct and compare. We take a look at Highest Performing Schools in Math and Reading by getting  %Overall Passing Scores, Math Passing Scores, and Reading Passing Scores. We do the same for the Lowest Performing Schools.
We break it down further to see these scores based on the students grade, and also what the budget is for each student in the Charter and Distric School. This to say, how much money is each school spending per student, and is their a correlation. We then take into consideration the factor of school size, and we create a dataframe for that as well, comparing small, medium, and large schools against one another. Finally, our last snapshot is comparing Charter and Distric against eachother when it comes to average math, average reading, math passing, reading passing, and overall scores. 



Conclusions

Based on our data frames we can come to several conclusions about the students overall success in Distric as compared to Charter Schools. One conclusion that is very ovious is that Charter Schools are outperforming Distric Schools in all categories across the board.
Charter Schools, which tend to be smaller, seems to outperform larger schools. We can assume that a smaller school can give greater focus and individualized mentorship to students because they have a smaller pool to work with. Another interesting finding is that larger school spend alot more per capita on students education, yet this does not seem to make correlation when it comes to positive performance. Charter schools spend less per student, yet they perform better than the their bigger budget counterparts. 







Screenshots

<img width="1230" alt="Screenshot 2024-06-24 at 9 05 51 PM" src="https://github.com/mariemsdiaz/pandas_challenge/assets/167847362/37678010-d165-4353-956e-029b8125e244">
<img width="1228" alt="Screenshot 2024-06-24 at 9 06 11 PM" src="https://github.com/mariemsdiaz/pandas_challenge/assets/167847362/d3161aa8-ee63-464d-8f5f-cbaa45391ca0">
<img width="1244" alt="Screenshot 2024-06-24 at 9 06 26 PM" src="https://github.com/mariemsdiaz/pandas_challenge/assets/167847362/87c1b98a-9307-410d-9e30-03f16b0dc92d">
<img width="1242" alt="Screenshot 2024-06-24 at 9 06 37 PM" src="https://github.com/mariemsdiaz/pandas_challenge/assets/167847362/2bb6c142-2d3b-48e0-9ab2-9b5c7d834c90">
<img width="1254" alt="Screenshot 2024-06-24 at 9 07 20 PM" src="https://github.com/mariemsdiaz/pandas_challenge/assets/167847362/5310598b-5b60-48ba-a6a1-ea5c39953b45">
<img width="1254" alt="Screenshot 2024-06-24 at 9 07 37 PM" src="https://github.com/mariemsdiaz/pandas_challenge/assets/167847362/9446e529-44b9-48b9-b0d8-8ac861347e98">
