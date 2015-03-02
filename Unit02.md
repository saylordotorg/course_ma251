---
layout: default
title: "MA251: Statistics II"
course_description: "A review of basic statistics and an application of statistical tools and techniques that are routinely used by modern statisticians for building models to analyze complex, multivariate problems."
next: ../Unit03
previous: ../Unit01
---
**Unit 2: Multiple Regression and Correlation** <span id="2"></span> 
*The term “multiple regression” was first introduced by Pearson in 1908.
Since then, multiple regression has evolved to be a powerful statistical
technique used in all fields of research, ranging from biology,
sociology, psychology, to engineering. Multiple regression enables you
to learn about the relationship between several independent or predictor
variables and one dependent variable. For instance, multiple regression
has been used to understand how housing price depends on location, the
size (in square feet), the number of bedrooms, the number of bathrooms,
the architecture style, the average income of the respective
neighborhood, the crime statistics, and so forth. In this unit, you will
learn several fundamental concepts of multiple regression, including
R<sup>2</sup> and partial correlation. You also will learn to perform
and interpret results of multiple regression.*

**Unit 2 Time Advisory**  
This unit will take you approximately 24 hours to complete.  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.1: 9 hours</span>  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.2: 2 hours</span>  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.3: 2 hours</span>  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.4: 5 hours</span>  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 2.5: 6 hours</span>

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   perform multiple regression on numerical and categorical variables;

<!-- -->

-   <span dir="LTR">explain the significance of R<sup>2</sup></span>;

<!-- -->

-   perform inference for multiple regression and coefficients; and

<!-- -->

-   evaluate partial correlation.

**2.1 Introduction to Multiple Regression** <span id="2.1"></span> 
-   **Lecture: YouTube: EconDrD’s “Multiple Regression Lecture Notes
    1”**
    Link: YouTube: EconDrD’s [“Multiple Regression Lecture Notes
    1”](http://www.youtube.com/watch?v=nFL-1cg74nA&list=PL6303CF42EE0C3074&index=2)
    (YouTube)  
        
     Instructions: Click on the link for “Multiple Regression Lecture
    Notes 1”. The video will introduce you to multiple regression.  
      
     Watching this video and pausing to take notes should take
    approximately 30 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Jeff Miller and Patricia Haden’s *Statistical Analysis
    with the General Linear Model*: “Chapter 14: Multiple Regression”**
    Link: Jeff Miller and Patricia Haden’s *Statistical Analysis with
    the General Linear Model*: [“Chapter 14: Multiple
    Regression”](http://psy.otago.ac.nz/miller/index.htm#GLMBook)
    (PDF)  
      
     Instructions: Click on the link “Download the book as a PDF file”
    to download and save the textbook. You will use this textbook
    throughout the course. For many problems, it is unreasonable to
    expect that there is only one independent variable that influences
    the behavior of the dependent variable. Multiple regression is
    designed to address this type of problem. What are the basic steps
    of multiple regression? Compare these steps to linear regression.  
      
     Reading this chapter should take approximately 3 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of Florida: Alan Agresti’s Statistical Methods
    for the Social Sciences II: “Chapter 11: Multiple Regression and
    Correlation”**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

-   **Lecture: YouTube: EconDrD’s “Multiple Regression for Dummy
    Variables”**
    Link: YouTube: EconDrD’s [“Multiple Regression for Dummy
    Variables”](http://www.youtube.com/watch?v=1RBj8ii39kY&list=PL6303CF42EE0C3074&index=7)
    (YouTube)  
        
     Instructions: Click on the link for “Multiple regression dummy
    variables”. The lecture will introduce you to multiple regression
    for categorical and qualitative variables. Sometimes we want to
    include a categorical variable (e.g., gender or education level) in
    our model. These types of variables can be represented by dummy
    variables – variables with only two values, 0 and 1. The number of
    dummy variables for each categorical variable is k-1, where k is the
    number of levels of the original variable.  
      
     Watching this video and pausing to take notes should take
    approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: University of Chicago: Robert Brandon Gramacy’s
    “Applied Regression Analysis: Homework 5”**
    Link: University of Chicago: Robert Brandon Gramacy’s [“Applied
    Regression Analysis: Homework
    5”](http://faculty.chicagobooth.edu/robert.gramacy/teaching.html)
    (PDF)  
      
     Instructions: Click on the link above, which will take you to the
    website of BUS 41100. Scroll down to Homework 5 and complete all
    problems in the homework. Follow the instructions for the problems
    closely. The solutions to the homework are in the R code. The
    comments in the R code are helpful for understanding the results.  
      
     Completing this assessment should take approximately 3 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2 Multiple Correlation and R2** <span id="2.2"></span> 
-   **Reading: University of Florida: Alan Agresti’s Statistical Methods
    for the Social Sciences II: “Chapter 11: Multiple Regression and
    Correlation”**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**2.3 Inference for Multiple Regression and Coefficients** <span
id="2.3"></span> 
-   **Reading: University of Florida: Alan Agresti’s Statistical Methods
    for the Social Sciences II: “Chapter 11: Multiple Regression and
    Correlation”**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**2.4 Relationships between Predictors** <span id="2.4"></span> 
-   **Reading: Jeff Miller and Patricia Haden’s *Statistical Analysis
    with the General Linear Model*: “Chapter 16: Relationships among
    Predictors”**
    Link: Jeff Miller and Patricia Haden’s *Statistical Analysis with
    the General Linear Model*: [“Chapter 16: Relationships among
    Predictors”](http://psy.otago.ac.nz/miller/index.htm#GLMBook)
    (PDF)  
      
     Instructions: Click on “Download the book as a PDF file” to save
    and download the textbook. You will use this textbook throughout the
    course. Read “Chapter 16: Relationships among Predictors.” This
    chapter will address an important aspect of regression analysis,
    that is, the relationships between the different predictor
    variables. You will learn about the “context effect,” which is a
    situation when the usefulness of a predictor depends on which other
    predictor variables are included in the model. You will also learn
    about the use of the Venn diagram to visualize the relationships
    between predictors that lead to redundancy, error reduction, and
    suppressor effects.   
      
     Studying this chapter should take approximately 4 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of Florida: Alan Agresti’s Statistical Methods
    for the Social Sciences II: “Chapter 11: Multiple Regression and
    Correlation**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**2.5 Partial Correlation** <span id="2.5"></span> 
-   **Reading: University of Florida: Alan Agresti’s Statistical Methods
    for the Social Sciences II: “Chapter 11: Multiple Regression and
    Correlation”**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

-   **Assessment: McGraw Hill: Bowerman, O’Connell, Schermer, and
    Adcock’s “Business Statistics in Practice: Multiple Choice Quiz for
    Chapter 12”**
    Link: McGraw Hill: Bowerman, O’Connell, Schermer, and Adcock’s
    [“Business Statistics in Practice: Multiple Choice Quiz for Chapter
    12”](http://highered.mcgraw-hill.com/sites/0070983755/student_view0/chapter12/multiple_choice_quiz.html)
    (HTML)  
        
     Instructions: Select your answer from choices given for each
    question and click on “Submit Answers” at the bottom of the webpage
    when you have answered all the questions. The webpage will tell you
    whether your answer is correct and what the correct answer is.   
      
     Completing this quiz should take approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: The Saylor Foundation’s “Multiple Regression Model”**

    <span style="font-family: Arial, sans-serif; font-size: 9pt; ">Link:
    The Saylor Foundation’s </span>[“<span
    style="font-size: 9pt;">Multiple Regression
    Model</span>](http://www.saylor.org/site/wp-content/uploads/2012/08/MA251-Assessment-for-Unit-2.5.FINAL_.pdf)<span
    style="font-size: 9pt; font-family: Arial, sans-serif;">[”](http://www.saylor.org/site/wp-content/uploads/2012/08/MA251-Assessment-for-Unit-2.5.FINAL_.pdf)
    (PDF)</span>

    <span
    style="font-size: 9pt; font-family: Arial, sans-serif; ">Instructions:<span
    class="apple-converted-space"> C</span></span><span
    style="font-size: 12px;"><span
    style="font-family: Arial, sans-serif;">omplete the linked
    assessment, titled </span>“<span
    style="font-family: Arial, sans-serif;">Multiple Regression
    Model</span></span>”<span style="font-family: Arial, sans-serif;">.
    When you are done, check your work against The Saylor
    Foundation’s </span>[“Answer Key for Multiple Regression
    Model”](http://www.saylor.org/site/wp-content/uploads/2012/08/MA251-Assessment-AnswerKeyForUnit-2.5.FINAL_.pdf) <span
    style="font-family: Arial, sans-serif;">(PDF) in subunit
    2.5.</span><span class="apple-converted-space"
    style="font-family: Arial, sans-serif; font-size: 10pt;"> </span>

    Completing this<span style="font-family: Arial;"> assessment should
    take you no longer than 4 hours. If you have not done so already,
    please click on the following link </span>[<span
    style="font-family: Arial; color: rgb(17, 85, 204);">http://cran.r-project.org</span>](http://cran.r-project.org/)<span
    style="font-family: Arial;"> to download and install R on your
    computer. R will be used throughout the course for
    assignments.</span>

**Unit 2 Assessment** <span id="2.6"></span> 
-   **Assessment: The Saylor Foundation’s “Unit 2 Assessment”**
    Link: The Saylor Foundation’s [“Unit 2
    Assessment”](http://school.saylor.org/mod/quiz/view.php?id=1319)  
        
     Instructions: Complete this assessment to gauge your understanding
    of the materials covered thus far in this course. When you click
    “submit,” you will be shown the correct answers.


