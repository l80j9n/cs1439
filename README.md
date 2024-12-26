java c
• This assignment is worth 8% of your total mark.
• To get full marks, show your working including 1) R commands and outputs you use, 2) mathematics derivation, and 3) rigorous explanation why you reach conclusions or answers. If you just provide final answers, you will get zero mark.
• The assignment you hand in must be typed (except for math formulas), and be submitted using LMS as a single PDF document only (no other formats allowed). For math formulas, you can take a picture of them. Your answers must be clearly numbered and in the same order as the assignment questions.
• The LMS will not accept late submissions. It is your responsibility to ensure that your assignments are submitted correctly and on time, and problems with online submissions are not a valid excuse for submitting a late or incorrect version of an assignment.
• We will mark a selected set of problems. We will select problems worth ≥ 50% of the full marks listed (≥ 12 out of 24 for this assignment). For example, if we select 1-(b), (c), (e) and 2-(a) for marking, they will contribute 47(= 15/7 × 100), 20(= 15/3 × 100), 13(= 15/2 × 100), 20(= 15/3 × 100)) to the full marks of 100 for the assignment 1.
• If you need an extension, please contact the lecturer before the due date with appropriate justification and supporting documents. Late assignments will only be accepted if you have obtained an extension from the lecturer before the due date. To ensure that the lecturer responds to your extension request email before the due date, please contact 24h before the due date. Under no circumstances an assignment will be marked if solutions for it have been released.
• Also, please read the “Assessments” section in “Subject Overview” page of the LMS.
1. Fit a binomial regression model to the O-rings data from the Challenger disaster, using a complementary代 写regression modelC/C++
代做程序编程语言 log-log link. You must use R (but without using the glm function); I want you to work from first principles.
(a) (3 marks) Compute MLEs (maximum likelihood estimates) of the parameters in the model.
(b) (7 marks) Compute 95% CIs for the estimates of the parameters. You should show how you derived the fisher information.
(c) (3 marks) Perform. a likelihood ratio test for the significance of the temperature coeffi-cient.
(d) (3 marks) Compute an estimate of the probability of damage when the temperature equals 31 Fahrenheit (your estimate should come with a 95% CI, as all good estimates do).
(e) (2 marks) Make a plot comparing the fitted complementary log-log model to the fitted logit model. To obtain the fitted logit model, you are allowed to use the glm function.
2. The data frame. ‘pima subset’ contains a subset of the pima data set. For details of the pima data set, please see the practical problem 2 for the week 2. You can obtain ‘pima subset’ using the commands:
> library(faraway)
> missing <- with(pima, missing <- glucose==0 | diastolic==0 | triceps==0 | bmi == 0)
> pima_subset = pima[!missing, c(6,9)]
> str(pima_subset)
’data.frame’: 532 obs. of 2 variables:
$ bmi : num 33.6 26.6 28.1 43.1 31 30.5 30.1 25.8 45.8 43.3 ...
$ test: int 1 0 0 1 1 1 1 1 1 0 ...
Using the ‘pima subset’ data set, we will fit a binomial regression with a logit link with test as a response and bmi as a predictor to see the relationship between the odds of a patient showing signs of diabetes and his/her bmi. The odds o and probability p are related by

(a) (3 marks) Please estimate the amount of increase in the log(odds) when the bmi in-creases by 5.
(b) (3 marks) Compute a 95% CI for the estimate.
You are allowed to use the glm function.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
