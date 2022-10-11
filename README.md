# Paper-Airplane-Experiment
Fill in your answers to the items below to describe your Project 2 experiment. questions in your document.
General/Specific Question
1. [1] What is the general question you are looking to study?
Please leave the original
 Can changing different aspects of a paper airplane affect how long it stays in the air?
2. [1] What is the specific question your experiment will study? (This comes from using your choices for the response, the conditions, and the units.)
Which combination of paper material and folding method used to make a paper airplane results in the greatest amount of airtime?
Three Choices (following Notes 1)
3. [1] Identify your response: Airtime in seconds
4. [1] Identify your conditions/treatments. Since they are required to come from crossing two factors,
replace the entries of the table below (adding more rows and/or columns if necessary) to identify your factor variables, the levels of each factor, and the treatments.
Method
123
       Paper
Computer C, 1 Notebook N, 1
Treatments: C/1, C/2, C/3, N/1, N/2, N/3 Factors: Paper used and Folding Method Levels of factors:
Paper: computer paper and notebook paper Method: 1, 2, and 3
C, 2 N, 2
C, 3 N, 3
            5. [1] Identify your experimental units: Paper Airplanes If your design is SP/RM, identify both the large units and the small units.
6. Also, regarding your response:
a) [2] Describe how you will measure the response, including what you will do to improve its
reliability and minimize measurement error.
I will measure my response by throwing the paper airplane and recording with a stopwatch (on my phone) how long it stays in the air. I will stop the time when it touches the ground.
b) [1] Explain why your response has validity.
The purpose of this experiment is to find out which treatment will result in the greatest airtime, so recording the number of seconds the airplane is in the air before it touches the ground is a valid response.
7. Also, regarding your conditions/treatments:
a) [1] For each factor, identify whether it is an observational factor or an experimental factor. It is
required that at least one of the factors be an experimental factor.
Both factors are experimental.
b) [2] Recall that we want to isolate the effect(s) of interest by treating the experimental units in the same ways except for the differing treatments. Identify at least 2 ways you will treat your units the same.
1. Both the computer and notebook paper will be from the same source. I.e. all notebook paper from the same notebook and all computer paper from the same pack.
2. I will try my best to make sure each airplane per treatment looks the same/folded as similarly
as possible.
c) [1] If your design is SP/RM, identify which is the large-units factor and which is the small-units factor. Otherwise, write “N/A”.
N/A
8. Also, regarding your experimental units:
a) [1] Describe what you will do to improve the uniformity of your units.
As mentioned before, I will try my best to make sure each airplane of the same folding method looks the same.
b) [1] Explain how representative your units are. (It may be beyond the scope of your study to make them truly representative, but it is at least important to acknowledge that.)
The units are representative as we would use ordinary types of paper that we use everyday to record the airtime.
Anticipating sources of variation and bias
9. [2] Identify at least 4 sources of variation/bias that you anticipate in your experiment and discuss
what you plan to do to reduce their influence. (Hint: you may have discussed some of these earlier regarding how to limit measurement error, isolate the effect(s) of interest, or make units more uniform. You are allowed to repeat these.) It also may help to collect preliminary data.
-the stillness of the air will not be perfect constantly (such as air conditioning emitted into the room that might affect the airtime)
-the paper airplanes will not be folded perfectly the same
-the capability to measure how long it’s in the air perfectly
-the motion of which we are dropping the paper airplanes may not be the same
10. [1] Do you plan to incorporate blocking in your design to help control variation or bias? If so, explain how, including what variable(s) blocking will be based on.
No, I do not plan on incorporating blocking.
11. [1] Identify which are your factors of interest and which are your blocking factors (if you have any blocking factors).
N/A
The Design and Random assignment
12. [1] What is the design name? Your options are:
a. two-way completely randomized (CR[2]) design
b. two-way complete block (CB[2]) design
c. two-way Latin square (LS[2]) design
d. split plot / repeated measures (SP/RM) design
13. [1] How many treatments do you have? How many replications (units) per treatment? How many total observations?
6 treatments
2 replications (paper airplanes made) per treatment
12 total observations
14. [1] Show output from PROC PLAN that you will use in randomly assigning treatments to units. Do not supply a seed in your PROC PLAN code.
Notebook
   
Computer
 15. [1] Be specific in describing how you will use this PROC PLAN output to randomly assign treatments to units. You should identify each of your treatments by name and your units by their original number in this description.
- 6 pieces of notebook paper
- 6 pieces of computer paper
Notebook papers: 5 and 1 will be assigned to method 1 Notebook papers: 2 and 3 will be assigned to method 2 Notebook papers: 6 and 4 will be assigned to method 3 Computer papers: 3 and 4 will be assigned to method 1 Computer papers: 5 and 2 will be assigned to method 2 Computer papers: 6 and 1 will be assigned to method 3
Data structure: factor diagram and df
16. [2] Draw a table (without response values) upon which you will base your factor diagram. (The rows
and/or columns should correspond to different levels of the factors.) You should label the data table so it is clear which levels correspond to each row and/or column.
  17. [2] Based on this data table, draw the factor diagram for your design as in Assignment 3.
 
18. [1] What are the degrees of freedom associated with each factor? You are required to have at least 8 degrees of freedom for residual error (exceptions given in the Project 2 prospectus).
     Factors Grand Avg Paper Method Interaction
Outside Factors # levels None 1 Grand avg 2 Grand avg 3 Grand avg, paper, 6 method
Sum df
0 1–0=1 1 2–1=1 1 3–1=2 4 6–4=2
                      Residual Error
    Interaction, grand avg, paper, method
  12
    6
   12 – 6 = 6
 Conducting your experiment
19. [2] Include at least two photos here that help to describe your experiment, writing about what they
show.
Computer paper and notebook paper are utilized for the making of the Hang Glider airplanes.
Three different folding types of the World Record Paper Airplane, Blunt Dart Airplane, and the Hang Glider Airplane are shown in the photo above from right to left. We can also see that I’ve used both paper types for each folding method.
   
20. [3] What other details about your experiment need to be mentioned (in addition to those you’ve already provided) for your experiment to be reproducible? This means that you should provide enough information that someone else with limited knowledge of your experimental context can repeat your experiment.
To repeat this experiment, one would have to use the Up&Up (Target) brand of wide ruled notebook paper and “Office Depot White Copy Printer Paper.”
If someone else wanted to repeat this experiment they would also have to refer to the same YouTube video that I followed to fold the paper airplanes: https://youtu.be/54noZe-0B1c
The method 1 airplanes follow the World Record Paper Airplane tutorial. The method 2 airplanes follow the Blunt dart tutorial.
The method 3 airplanes follow the Hang Glider tutorial.
21. [1] Copy and paste the Excel data table you input into SAS for your experiment, including your observed response values.
Graphical analysis and Assumption Checking
22. [2] Copy and paste a parallel dot plot of the dataset. The x-axis should have locations for each of the
treatments and the y-axis should show the response. Use formats and labels so the variables and treatments are described clearly (and are not shown as abbreviations). If your experiment used blocking, this plot should be a connected parallel dot plot1; if you used multiple blocking variables, you should make a connected parallel dot plot for each.
    1 But not for a SP/RM design.

 23. Interpret this parallel dot plot in terms of
a. [1] the means of the responses for each of the treatments
The lowest seconds of airtime come from the treatments Computer Paper/World Record Paper Airplane and Computer Paper/Hang Glider. The biggest difference comes from these two treatments and Notebook Paper/Blunt Dart. The highest seconds of airtime come from the treatments Notebook Paper/Blunt Dart and Notebook Paper/Hang Glider. There is a smaller difference between Computer Paper means than the Notebook Paper means
b. [1] the spreads of the responses for each of the treatments
The treatments that have a wider spread are Computer Paper/Blunt Dart, Notebook Paper/Blunt Dart, and Notebook Paper/Hang Glider. The other three treatments have a tighter spread.
c. [1] if applicable, the usefulness of the blocking variable(s) in explaining variation in the response.
24. Check the assumptions. Copy and paste each plot mentioned below and state why it gives evidence the given assumption is satisfied or violated.
a. [2] Residual vs. predicted plot and the constant standard deviation assumption

  The constant standard deviation assumption is not met for the plot with the untransformed data. The spread is much smaller at the ends and larger in the middle. The log-transformed data did not improve as the spreads look virtually the same as the untransformed data.
b. [2] normal quantile plot and the normality assumption

 Untransformed
Log Transformed
The histogram and box plot for the untransformed data is symmetric, and the points on the normal quantile plot generally follow the line, therefore the normality assumption is satisfied. The log-transformation looks the same as the untransformed data, besides the fact that the histogram is following a bell-shape.
Interaction
25. [1] Copy and paste a table of the means of the response for each treatment combination.
  
 26. [2] Copy and paste an interaction plot made by SAS.
The method 1 airplanes follow the World Record Paper Airplane tutorial. The method 2 airplanes follow the Blunt dart tutorial.
The method 3 airplanes follow the Hang Glider tutorial.
27. Explain whether or not there is evidence of interaction2 in your data in terms of both
a. [1] The interaction plot
There is greater interaction between method 1 (World Record Paper Airplane) and method 3 (Hang Glider) because the lines are less parallel, thus being a strong interaction. However, Method 2 (Blunt Dart) and Method 3 (Hang Glider) are much more parallel to each other, creating a weaker interaction.
b. [1] The table of means
Method 1: 1.09-0.84=0.25 Method 2: 1.77-1.175=0.595 Method 3: 1.505-0.82=0.685
  2 This need not be a definitive answer, but you must demonstrate that you know what interaction means.

We can see that the Blunt Dart airplane and Hang Glider airplane have close values of 0.595 and 0.685 concluding that there is not a difference between the differences and no interaction. This also explains why they are parallel on the interaction plot. However, the World Record Paper Airplane has a value of 0.25, which is much difference than the other two methods, which concludes that there is an interaction between that and the Hang Glider.
ANOVA
28. (Optional: for +1 extra credit)
a. Calculate and show the decomposition: fill in the factor diagram with estimated effects for each factor and observation.
 b. Show how each entry of the ANOVA table can be calculated starting from this decomposition.
29. [2] Fill an ANOVA table below with
- rows including each factor in the factor diagram
- columns including Source, df, SS, MS, F-ratio, and P-value
Source df Grand avg 1 Paper 1 Method 2 Interaction 2 Residuals 6 Observed values 12
SS
0.79 0.53 0.11
0.00675
MS F-ratio X X 0.79 698.14 0.26 235.12 0.053 47.25 0.001125 X X X
P-value X <.0001 <.0001 0.0002 X X
            30. [1] Show SAS output that contains every value in your ANOVA table above (other than the Grand Average/Observed values rows).
31. Choose one of the factors in your ANOVA table and a. [1] Interpret the F-ratio
 
The average variability in the response due to interaction between paper type and folding
method is about 47 times the average variability due to residual error.
b. [1] Interpret its p-value
The p-value for the interaction is 0.0002, which is less than 0.05, indicating that there is statistically significant evidence that the interaction between paper type and folding method have an effect on the airtime.
32. [2] Find the residual standard deviation and interpret it within the context of the experiment.
Root mse= 0.033541
On average, the time between the observed and predicted airtime for the planes is 0.033541 seconds.
33. [1] If you used blocking, describe how effective it was in reducing the unexplained variation – i.e. the sum of squares due to residual error. N/A
Effects of factors of interest
34. [2] Should you interpret the main effects or simple effects of the factors of interest? (This decision
should be based on a hypothesis test at the 0.05 significance level.) Justify your decision.
The simple effects should be interpreted because the p-value for the interaction between paper type and folding method is 0.0002, or less than 0.05, which means that there is sufficient evidence of interaction in the dataset.
35. [3] Regardless of your answer above, find point estimates of all of the main effects (Hint: these are all differences in sample means; be sure to state which levels are greater/less)
  a. For folding method:
2 vs 1: 1.475-1.0075= 0.4675 (method 2 >method 1)
On average, the airtime from using a Blunt Dart airplane is 0.4675 seconds greater than using a World Record Paper Airplane.
1 vs 3: 1.1625-1.0075= 0.155 (method 3> method 1)
On average, the airtime from using a Hang Glider airplane is 0.155 seconds greater than using a World Record Paper Airplane.
2 vs 3: 1.475-1.1625= 0.3125 (method 2>method 3)
On average, the airtime from using a Blunt Dart airplane is 0.3125 seconds greater than using a Hang Glider airplane.
b. For paper type:
Computer vs Notebook: 1.457-0.945=0.512 (notebook>computer)
On average, the airtime from using the notebook paper is 0.512 seconds greater than using computer paper.
Method 1= (0.84+1.09)/2= 1.0075 Method 2= (1.175+1.775)/2=1.475 Method 3= (0.82+1.505)/2=1.1625 Computer Paper= (0.84+1.175+0.82)/3=0.945 Notebook Paper= (1.09+1.775+1.505)/3=1.457
The method 1 airplanes follow the World Record Paper Airplane tutorial.
The method 2 airplanes follow the Blunt dart tutorial.
The method 3 airplanes follow the Hang Glider tutorial.

36. [3] Find point estimates of all of the simple effects. (These are also differences in treatment means.) Separate these simple effects into groups: for instance for the pigs experiment, you would state the simple effects of antibiotics separately at 0 mg of vitamin B and 5 mg of vitamin B.
a. For Folding:
When it’s computer paper
2 vs 1: 1.175-0.84=0.335 (method 2> method 1) 1 vs 3: 0.84-0.82= 0.02(method 1> method 3)
2 vs 3: 1.175-0.82= 0.355 (method 2> method 3) When it’s notebook paper
2 vs 1: 1.177-1.09=0.087 (method 2> method 1) 1 vs 3: 1.505-1.09=0.415 (method 3>method 1) 2 vs 3: 0.685-0.595=0.09 (method 3> method 2)
b. For Paper Type:
When it’s method 1: 1.09-0.84=0.25 (Notebook>computer) When its method 2: 1.77-1.175=0.595 (notebook>computer) When its method 3: 1.505-0.82=0.685 (notebook>computer)
37. [3] Report 95% confidence intervals for all the main effects. Making your own tables so it’s clear what levels are being compared for each interval.
 
 a. For Folding Method: Method
1 vs 2 1 vs 3 2 vs 3
b. For Paper Type Paper
Computer vs Notebook
-0.57 -0.45 -0.26 -0.14 0.25 0.37
-0.56 -0.46
                        38. [2] Choose one of these confidence intervals for a main effect and interpret it within the context of your experiment.
For paper type: 0.56, 0.46
We are 95% confident that the average airtime of paper airplanes flown using computer paper is between 0.56 and 0.46 seconds greater than airplanes flown using notebook paper over the average levels of folding methods.
 
 39. [3] Report 95% confidence intervals for all the simple effects (again making your own tables)
a. For folding method:
b. Paper Type
40. [2] Choose one of these confidence intervals for a simple effect and interpret it within the context of Summarizing your experiment’s results
41. [5] Summarize the results of your experiment in a paragraph, answering the question: how did each
of your factors of interest affect the response? (You must summarize your results; you will not receive credit for a listing of the interpretations of all of the confidence intervals.)
I wanted to know which combination of paper material and folding method used to make a paper airplane results in the greatest amount of airtime. We can see in the parallel dot plot that the paper type of computer paper vs notebook paper has an apparent difference in the height of the spreads, which means that the type of paper affected the response. From the interaction plot, we can see that World Record Paper Airplane and the Hang Glider airplane perform very similarly with airtime, as they are parallel. The notebook paper for the Blunt Dart folding method had the greatest mean of 1.77 seconds in the air.
Conclusion / What you learned
42. [1] What did you expect the results of your experiment to be and is that what happened?
I expected for the computer paper airplanes to stay in the air for longer because it’s a sturdier material/be more wind resistant. However, it makes sense that computer paper had a shorter airtime than notebook paper because they have a larger mass.
43. [1] What problems arose during data collection and what would you have done differently if you could do your experiment again?
It was difficult to launch the paper airplanes uniformly and it took numerous tries to get recordable data- the airtime of the paper airplanes that didn’t hit the wall of the narrow hallway. If I were to do this experiment again I would do it in a more open area.
[1] What further questions/study are inspired by your experiment?
It’d be interesting to do this experiment exploring different sizes of paper airplanes.
Appendix: SAS code
44. [1] Display all the SAS code you used. Please format it to be as neat and concise as possible.
   
   
