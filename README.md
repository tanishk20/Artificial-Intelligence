# Artificial-Intelligence
Description of student marks
#Let's start analyzing from now.

#How Race/Group and Parent Degree is related to total scores??


#Insight 1: As we see, High school, some High school of parentDegree has less scores.... 
#Insight 2: Aso, As group Name is increasing, scores are increasing. Group A < Group B < Group C < Group D < Group E.

#Insight 3: As we can see, Female students perform better than Male students.
#Of course, in Maths, Male students outperform Female Students

#Now we can observe that,Parents degree is also crucial in student's score.

# So, I would like to generalize "parentDegree" column, with 'has_degree' and 'no_degree'.
# if parent Degree is in ("high school","some high school") then, I thought they don't have degree. or else they has degree

#Even Lunch affects student's scores
#Now we can observe that,Parents degree is also crucial in student's score

# As you can see above, I have generalized all features

# As you can see, Top students(mean) have completed their course, Took standard Lunch, Having parent_Degree is also + point.
# Bottom students(mean) didn't complete course, Didn't take good lunch, parent has no degree.
# Out of Top 10(mean), 7 are female students
# Interestingly, Out of Bottom 10(mean), 7 are male students

#Simply, if you complete course, Have standard lunch, you   can score good grade

#Simply, Lunch, Course are mandatory for scoring good. 

# Finally, What I observed is ,

# Students percentage is correlated with Groups Average Percentage.
#      ex: Average student from Group E have scored more compared to Group A's average Student.
# Parents Degree is also a bit correlated.
# Female Students Percentage is higher than Male Students.
# Students Who took courses have benefitted.
# Students who took standard lunch has scored well.
