**Unit 1: Review** <span id="1"></span> 
*In this unit, we will review some of the basic concepts you learned in
Introduction to Statistics
([MA121](http://www.saylor.org/courses/ma121/)), including probability
distribution, hypothesis testing, analysis of variance (ANOVA), basic
regression, and correlation. This unit serves as the foundation for the
subsequent units. Feel free to skim through subunits in which you are
confident of a thorough understanding of the topics covered. *  
  
 *In this unit, you will also learn to use R, a powerful statistical
programming language. The New York Times has a fascinating article about
R
[here](http://www.nytimes.com/2009/01/07/technology/business-computing/07program.html).
R is widely used by engineers, statisticians and scientists for data
analysis. The main factor distinguishing R from other statistical and
numerical languages like SAS, Matlab, Mathematica or SPLUS is that R is
freely available to everybody. It is developed for scientists and
maintained by scientists. Since its inception in 1996, the R-project has
been constantly upgraded by many contributors, which expand the
capabilities of the language through add-on packages. *

**Unit 1 Time Advisory**  
This unit will take you approximately 31 hours to complete.  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 1.1: 5 hours</span>  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 1.2: 8 hours</span>  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 1.3: 7 hours</span>  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 1.4: 11 hours</span>

**Unit1 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   <span dir="LTR">perform calculations with </span>binomial
    distribution, exponential distribution, Poisson distribution, and
    normal distribution;
-   <span dir="LTR">conduct hypothesis testing using student’s t-test
    and chi-square procedures;</span>
-   <span dir="LTR">perform one-way and two-way ANOVAs;</span>
-   <span dir="LTR">perform simple linear regression; and</span>
-   <span dir="LTR">explain correlation and covariance.</span>

**1.1 Overview of Probability Distributions** <span id="1.1"></span> 
-   **Reading: MIT: Dmitry Panchenko’s “Statistics for Applications”
    Lecture Notes: Lecture 1—“Overview of Some Probability
    Distributions”**
    Link: MIT: Dmitry Panchenko’s “Statistics for Applications” Lecture
    Notes: [Lecture 1—“Overview of Some Probability
    Distributions”](http://ocw.mit.edu/courses/mathematics/18-443-statistics-for-applications-fall-2006/lecture-notes/lecture1.pdf) (PDF)  
        
     Instructions: Download the PDF file of the lecture note of section
    \#1, “Overview of Some Probability Distribution.” The reading
    provides an overview of several important discrete and continuous
    probability distributions, including binomial distribution,
    exponential distribution, Poisson distribution, and normal
    distribution. Under which conditions can a binomial distribution or
    a Poisson distribution be approximated by a normal distribution?  
      
     Reading this lecture should take approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Activity: The Comprehensive R Archive Network’s “Getting Started
    with R”**
    Link: The Comprehensive R Archive Network’s [“Getting Started with
    R](http://cran.r-project.org/)[”](http://cran.r-project.org/)
    (HTML)  
        
     Instructions: Click on the link above, which will take you to the
    official website for R: The Comprehensive R Archive Network.
    Download and install the appropriate version of R for your computer.
    The installation procedure is very straightforward. Once R is
    installed, go back to the website and click on “Manuals” under
    “Documentation,” which will take you to various R manuals. Click on
    “An Introduction to R” (either HTML or PDF) and read it. This manual
    will give you basic commands in R. Pay careful attention to chapters
    7 and 8. Be sure to test out the R examples in the manual in the R
    command window to get used to R syntaxes.  
      
     Completing this activity should take approximately 4 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Activity: Dr. Alastair Sanderson’s “An Introduction to Using R”**
    Link: Dr. Alastair Sanderson’s [“An Introduction to Using
    R](http://www.sr.bham.ac.uk/~ajrs/R/r-getting_started.html)[”](http://www.sr.bham.ac.uk/~ajrs/R/r-getting_started.html)
    (HTML)  
      
     Instructions: Click on the above link. This webpage is a detailed
    tutorial for getting started with R. Copy and paste the R code from
    the webpage to the R command window. Make sure that you obtain
    similar results as shown on the webpage.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.2 Overview of Tests for Statistical Significance** <span
id="1.2"></span> 
**1.2.1 Basic Concepts** <span id="1.2.1"></span> 
-   **Reading: Vassar College: Richard Lowry’s *Concepts and
    Applications of Inferential Statistics*: “Chapter 7: Tests of
    Statistical Significance: Three Overarching Concepts”**
    Link: Vassar College: Richard Lowry’s *Concepts and Applications of
    Inferential Statistics*:  [“Chapter 7: Tests of Statistical
    Significance: Three Overarching
    Concepts”](http://vassarstats.net/textbook/) (HTML)  
      
     Instructions: Click on “Table of Contents” and read “Chapter 7:
    Tests of Statistical Significance: Three Overarching Concepts.” The
    reading will provide an overview of basic concepts in testing for
    statistical significance, including mean chance expectation, null
    hypothesis and research hypothesis, directional versus
    nondirectional research hypotheses, and one-way versus two-way tests
    of significance. What is the main difference between the null
    hypothesis and the research hypothesis? Think of a situation that
    you would prefer two-way testing over one-way testing. This section
    highlights the importance of coming up with the right question
    before figuring out which tool would be appropriate for answering
    the question.  
      
     Reading this chapter should take approximtely 1 hour.   
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.2.2 Chi-Square Procedures** <span id="1.2.2"></span> 
-   **Reading: Vassar College: Richard Lowry’s *Concepts and
    Applications of Inferential Statistics*: “Chapter 8: Chi-Square
    Procedures for the Analysis of Categorical Frequency Data”**
    Link: Vassar College: Richard Lowry’s *Concepts and Applications of
    Inferential Statistics*: [“Chapter 8: Chi-Square Procedures for the
    Analysis of Categorical Frequency
    Data”](http://vassarstats.net/textbook/) (HTML)  
      
     Instructions: Click on “Table of Contents” and read “Chapter 8:
    Chi-Square Procedures for the Analysis of Categorical Frequency
    Data.” The reading will provide an overview of applications of
    chi-square procedures. Chi-square procedures are often used for
    tests of goodness of fit and tests of independence. What are the
    limitations of chi-square procedures? Under which conditions is a
    Fisher Exact Probability Test more suitable than a chi-square
    test?  
      
     Reading this chapter should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.2.3 Student’s t-tests** <span id="1.2.3"></span> 
-   **Reading: Vassar College: Richard Lowry’s *Concepts and
    Applications of Inferential Statistics*: “Chapter 10. t-Procedures
    for Estimating the Mean of a Population,” “Chapter 11. t-Test for
    Two Independent Samples,” and “Chapter 12. t-Test for Two Correlated
    Samples”**
    Links: Vassar College: Richard Lowry’s *Concepts and Applications of
    Inferential Statistics*: [“Chapter 10. t-Procedures for Estimating
    the Mean of a Population,”](http://vassarstats.net/textbook/)
    [“Chapter 11. t-Test for Two Independent
    Samples,”](http://vassarstats.net/textbook/) and [“Chapter 12.
    t-Test for Two Correlated
    Samples”](http://vassarstats.net/textbook/) (HTML)  
        
     Instructions: Click on “Table of Contents” and read “Chapter 10:
    t-Procedures for Estimating the Mean of a Population,” “Chapter 11:
    t-Test for Two Independent Samples,” and “Chapter 12: t-Test for Two
    Correlated Samples.” These readings will provide an overview of
    student’s t-distribution and applications of t-tests for independent
    and correlated samples. Student’s t distribution arises when
    estimating the mean of normally distributed random variables of a
    sample with small size and the “true” standard deviation is
    unknown.  
      
     Reading these chapters should take approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: McGraw Hill: Bowerman, O’Connell, Schermer, and
    Adcock’s “Business Statistics in Practice: Multiple Choice Quiz for
    Chapter 14”**
    Link: McGraw Hill: Bowerman, O’Connell, Schermer, and Adcock’s
    [“Business Statistics in Practice: Multiple Choice Quiz for Chapter
    14”](http://highered.mcgraw-hill.com/sites/0070983755/student_view0/chapter14/multiple_choice_quiz.html)
    (HTML)  
        
     Instructions: Click on the link above and answer all questions in
    the quiz. Select your answer from choices given for each question.
    Click on “Submit Answers” at the bottom of the webpage when you have
    answered all the questions. The webpage will tell you whether your
    answer is correct and what the correct answer is.   
      
     Completing this quiz should take less than 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: The Saylor Foundation’s “One and Two-Sample Problems:
    Student’s T-Tests”**
    Link: The Saylor Foundation’s [“One and Two-Sample Problems:
    Student’s
    T-Tests](https://resources.saylor.org/archived/wp-content/uploads/2012/08/MA251-Assessment-for-Unit-1.2.FINAL_.pdf)[”](https://resources.saylor.org/archived/wp-content/uploads/2012/08/MA251-Assessment-for-Unit-1.2.FINAL_.pdf)
    (PDF)  
        
     Instructions: Complete the linked assessment, titled “One and
    two-sample problems: Student’s t-tests”. When you are done, check
    your work against The Saylor Foundation’s [“Answer Key for One and
    two-sample problems: Student’s
    t-tests](https://resources.saylor.org/archived/wp-content/uploads/2012/08/MA251-Assessment-AnswerKeyForUnit-1.2.FINAL_.pdf)[”](https://resources.saylor.org/archived/wp-content/uploads/2012/08/MA251-Assessment-AnswerKeyForUnit-1.2.FINAL_.pdf)
    in unit 1.2.   
      
     Completing this assessment should take you no longer than 4 hours.
    If you have not done so already, click on the following link
    [http://cran.r-project.org](http://cran.r-project.org/) to download
    and install R on your computer. R will be used throughout the course
    for computer assessments.

-   **Assessment: The Saylor Foundation’s “Subunit 1.2.3 Assessment”**
    Link: The Saylor Foundation’s [“Subunit 1.2.3
    Assessment”](http://school.saylor.org/mod/quiz/view.php?id=1316)  
        
     Instructions: Complete this assessment to gauge your understanding
    of the materials covered thus far in this course. When you click
    “submit,” you will be shown the correct answers.

**1.3 Overview of Analysis of Variance (ANOVA)** <span id="1.3"></span> 
*This subunit provides an overview of one-way and two-way analyses of
variance (or ANOVAs). The purpose of analysis of variance (ANOVA) is to
test for significant differences between means. In order to test for
statistical significance between means, we actually analyze
variances *– *hence the name “analysis of variance.” ANOVAs will enable
you to examine the amount of variability in a response variable and/or
understand where the variability is coming from. This unit will
specifically teach you how to use the one-way ANOVA to test for
differences between the means of several groups and to use* *the two-way
ANOVA and interpret the interaction effect.*

**1.3.1 Basic Concepts** <span id="1.3.1"></span> 
-   **Lecture: YouTube: Medical College of Wisconsin: Sergey Tarima’s
    “ANOVA: Comparing More Than Two Treatments”**
    Link: YouTube: Medical College of Wisconsin: Sergey Tarima’s
    [“ANOVA: Comparing More Than Two
    Treatments](http://www.youtube.com/watch?v=EVw7LlqYTkE&context=C3b9e00bADOEgsToPDskL7aO7nupBwBShFshhNdDNf)[”](http://www.youtube.com/watch?v=EVw7LlqYTkE&context=C3b9e00bADOEgsToPDskL7aO7nupBwBShFshhNdDNf)
    (YouTube). This content is also available in PDF format on the
    Medical College of Wisconsin's website  [“ANOVA: Comparing More Than
    Two
    Treatments”](http://www.mcw.edu/FileLibrary/Groups/Biostatistics/Publicfiles/LectureSeries/STANOVA1.pdf) (PDF)  
      
     Instructions: Click on the link for the video for the lecture on
    “ANOVA: Comparing More Than Two Treatments.” You may also want to
    download the presentation (in PDF) used for the lecture. In this
    lecture, Sergey Tarima discusses applications of one-way and two-way
    ANOVA in medical research. The lecture will cover content for
    subunits 1.3.1-1.3.3.  
      
     Watching this lecture and pausing to take notes should take
    approximately 1 hour.   
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Vassar College: Richard Lowry’s *Concepts and
    Applications of Inferential Statistics*: “Chapter 13: Conceptual
    Introduction to the Analysis of Variance”**

    Link: Vassar College: Richard Lowry’s *Concepts and Applications of
    Inferential Statistics*: [“Chapter 13: Conceptual Introduction to
    the Analysis of Variance”](http://vassarstats.net/textbook/) (HTML)

    Instructions: Click on “Table of Contents” and read “Chapter 13:
    Conceptual Introduction to the Analysis of Variance.” The reading
    will provide an overview of basic concepts in analysis of variance.
    The fundamental idea of ANOVA is that the observed variance of a
    variable can be decomposed into different sources of variations.
    Different ways of partitioning sources of variations are referred to
    as “statistical models.” The ANOVA depends on F-statistics, that is,
    the ratio of the variance of the means to the variance within the
    samples. What is the relationship between F-distribution and
    t-distribution?   
      
     Reading this chapter should take approximately 1 hour.

    Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.3.2 One-Way ANOVA** <span id="1.3.2"></span> 
*Note: This subunit is covered by the video lecture assigned beneath
subunit 1.3.1. The video lecture will provide an example illustrating
the use of one-way ANOVA in medical research.*

-   **Reading: Vassar College: Richard Lowry’s *Concepts and
    Applications of Inferential Statistics*: “Chapter 15: One-Way
    Analysis of Variance for Correlated Samples”**
    Link: Vassar College: Richard Lowry’s *Concepts and Applications of
    Inferential Statistics*: [“Chapter 15: One-Way Analysis of Variance
    for Correlated Samples”](http://vassarstats.net/textbook/) (HTML)  
      
     Instructions: Click on “Table of Contents” and read “Chapter 15:
    One-Way Analysis of Variance for Correlated Samples.” The reading
    provides an overview of one-way ANOVA for correlated samples, which
    can be considered to be an extension of correlated-samples
    t-test.   
      
     Reading this chapter should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Vassar College: Richard Lowry’s *Concepts and
    Applications of Inferential Statistics*: “Chapter 14: One-Way
    Analysis of Variance for Independent Samples”**
    Link: Vassar College: Richard Lowry’s *Concepts and Applications of
    Inferential Statistics*: [“Chapter 14: One-Way Analysis of Variance
    for Independent Samples”](http://vassarstats.net/textbook/) (HTML)  
      
     Instructions: Click on “Table of Contents” and read “Chapter 14:
    One-Way Analysis of Variance for Independent Samples.” The reading
    will provide an overview of using one-way ANOVA to compare means of
    two or more sampled using the F distribution for independent
    samples. The ANOVA tests the null hypothesis of the samples in two
    or more groups being drawn from the same population. What are the
    basic assumptions of one-way ANOVA? Why should the variance of the
    group means be lower than the variance of the samples?   
      
     Reading this chapter should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.3.3 Two-Way ANOVA** <span id="1.3.3"></span> 
*Note: This subunit is covered by the video lecture assigned beneath
subunit 1.3.1. The second half of the video focuses on the use of
two-way ANOVA in medical research.*

-   **Reading: Vassar College: Richard Lowry’s *Concepts and
    Applications of Inferential Statistics*: “Chapter 16: Two-Way
    Analysis of Variance for Independent Samples”**
    Link: Vassar College: Richard Lowry’s *Concepts and Applications of
    Inferential Statistics*: [“Chapter 16: Two-Way Analysis of Variance
    for Independent
    Samples](http://vassarstats.net/textbook/)[”](http://vassarstats.net/textbook/)
    (HTML)  
      
     Instructions: Click on “Table of Contents” and read “Chapter 16:
    Two-Way Analysis of Variance for Independent Samples.” Two-way ANOVA
    is an extension of the one-way ANOVA to examine the influence of
    different categorical independent variables on one dependent
    variable.  
      
     Reading this chapter should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: University of Chicago: Robert Brandon Gramacy’s
    “Applied Regression Analysis: Homework 1”**
    Link: University of Chicago: Robert Brandon Gramacy’s [“Applied
    Regression Analysis: Homework
    1](http://faculty.chicagobooth.edu/robert.gramacy/teaching.html)[”](http://faculty.chicagobooth.edu/robert.gramacy/teaching/ara/hw1.pdf)
    (PDF)  
      
     Instructions: Click on the link above and scroll down to Homework 1
    to complete this assignment. Follow the instructions for the
    problems closely, particularly the R-based assignments. The
    solutions to the homework are in the pdf file and the R code.  
      
     Completing this assessment should take approximately 3 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: McGraw Hill: Bowerman, O’Connell, Schermer, and
    Adcock’s “Business Statistics in Practice: Multiple Choice Quiz for
    Chapter 10”**
    Link: McGraw Hill: Bowerman, O’Connell, Schermer, and Adcock’s
    [“Business Statistics in Practice: Multiple Choice Quiz for Chapter
    10”](http://highered.mcgraw-hill.com/sites/0070983755/student_view0/chapter10/multiple_choice_quiz.html)
    (HTML)  
        
     Instructions: Click on the link above and answer all questions in
    the quiz. Select your answers from choices given for each question.
    Click on “Submit Answers” at the bottom of the webpage when you have
    answered all the questions. The webpage will tell you whether your
    answer is correct and what the correct answer is.  
      
     Completing this quiz should take less than 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Activity: John M Quick’s “R Tutorial Series: Two-Way ANOVA with
    Simple Interactions with Simple Main Effects”**
    Link: John M Quick’s [“R Tutorial Series: Two-Way ANOVA with Simple
    Interactions with Simple Main
    Effects](http://rtutorialseries.blogspot.com/2011/02/r-tutorial-series-two-way-anova-with.html)[”](http://rtutorialseries.blogspot.com/2011/02/r-tutorial-series-two-way-anova-with.html)
    (HTML)  
        
     Instructions: Click on the link and follow the instructions. This
    webpage contains a detailed tutorial for how to perform two-way
    ANOVA in R, it is attributed to John M Quick. Copy and paste the R
    code from the webpage to the R command window. Make sure that you
    obtain similar results as shown on the webpage.  
      
     Optional: Feel free to further explore other ANOVA tutorials:  
      
     - One-Way Omnibus ANOVA (HTML)  

    <http://rtutorialseries.blogspot.com/2010/10/r-tutorial-series-one-way-omnibus-anova.html>  
      
     - One-Way ANOVA with Comparisons (HTML)  

    <http://rtutorialseries.blogspot.com/2011/01/r-tutorial-series-one-way-anova-with.html>  
      
     - Two-Way ANOVA with Unequal Sample Sizes (HTML)  

    <http://rtutorialseries.blogspot.com/2011/02/r-tutorial-series-two-way-anova-with_28.html>  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed  
     on the webpage above

-   **Assessment: The Saylor Foundation’s “Subunit 1.3.3 Assessment”**
    Link: The Saylor Foundation’s [“Subunit 1.3.3
    Assessment”](http://school.saylor.org/mod/quiz/view.php?id=1317)  
        
     Instructions: Complete this assessment to gauge your understanding
    of the materials covered thus far in this course. When you click
    “submit,” you will be shown the correct answers.

**1.4 Overview of Regression** <span id="1.4"></span> 
*This subunit provides an overview of linear regression or the method of
using one variable to predict another variable using a linear function
(i.e. a straight line).  You will learn to calculate regression
coefficients, make inferences about the slope and correlation
coefficient, estimate mean values, and predict individual values.  *

**1.4.1 Regression Basics** <span id="1.4.1"></span> 
-   **Reading: Global Text: Thomas K. Tiemann’s *Introductory Business
    Statistics*: “Chapter 8: Regression Basics”**
    Link: Global Text: Thomas K. Tiemann’s *Introductory Business
    Statistics*: [“Chapter 8: Regression
    Basics”](https://resources.saylor.org/archived/wp-content/uploads/2012/03/Introductory-Business-Statistics.pdf)
    (PDF)  
      
     Instructions: Download the PDF file. Open the file and browse
    to“Chapter 8: Regression Basics.” Read pages 70-79. Linear
    regression models the relationship between a dependent variable (the
    response) and an independent variable (the cause) by fitting a
    linear equation to observed data. Define outliners and influential
    observations in a sample. How do you use F-score for testing a
    regression?  
      
     Reading this chapter should take approximately 1 hour.  
      
     Terms of Use: The above book is released under a [Creative Commons
    Attribution 3.0
    License](http://creativecommons.org/licenses/by/3.0/) (HTML). It is
    attributed to Thomas K. Tieman, and the original version can be
    found [here](http://globaltext.terry.uga.edu/booklist?cat=Business).

-   **Web Media: YouTube: Perdisco’s Introductory Statistics Textbook:
    “Chapter 10: Regression”**
    Link: YouTube: Perdisco’s Introductory Statistics Textbook:
    [“Chapter 10:
    Regression”](http://www.youtube.com/watch?v=MIqyiGvrUXE) (YouTube)  
      
     Instructions: This video provides a brief overview of regression.
    This lecture is optional if you already have a good understanding of
    regression.  
      
     Watching this video should take approximately 10 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.4.2 Correlation and Covariance** <span id="1.4.2"></span> 
-   **Reading: Global Text: Thomas K. Tiemann’s *Introductory Business
    Statistics*: “Chapter 8: Regression Basics”**
    Link: Global Text: Thomas K. Tiemann’s *Introductory Business
    Statistics*: [“Chapter 8: Regression
    Basics”](https://resources.saylor.org/archived/wp-content/uploads/2012/03/Introductory-Business-Statistics.pdf)
    (PDF)  
      
     Instructions: Download the PDF file. Open the file and browse to
    “Chapter 8: Regression Basics.” Read pages 79-82. Covariance
    measures how much two random variables change together. How does
    correlation relate to covariance? What are the connections among
    regression, correlation, and covariance?  
      
     Reading this chapter should take approximately 30 minutes.  
      
     Terms of Use: The above book is released under a [Creative Commons
    Attribution 3.0
    License](http://creativecommons.org/licenses/by/3.0/) (HTML). It is
    attributed to Thomas K. Tieman, and the original version can be
    found [here](http://globaltext.terry.uga.edu/booklist?cat=Business).

**1.4.3 Traps and Pitfalls of Regression** <span id="1.4.3"></span> 
-   **Reading: University of Otago: Jeff Miller and Patricia Haden’s
    *Statistical Analysis with the General Linear Model*: “Chapter 13:
    Traps and Pitfalls of Regression Analysis”**
    Link: University of Otago: Jeff Miller and Patricia Haden’s
    *Statistical Analysis with the General Linear Model*: [“Chapter 13:
    Traps and Pitfalls of Regression
    Analysis”](http://psy.otago.ac.nz/miller/index.htm#GLMBook) (PDF)  
      
     Instructions: Click on the link “Download the book as a PDF file”
    to download and save the textbook. You will use this textbook
    throughout the course. Read “Chapter 13: Traps and Pitfalls of
    Regression Analysis.” What does “regression towards the mean”
    actually mean?  
      
     Reading this chapter should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Massachusetts Institute of Technology: Cynthia Rudin’s
    “Statistical Thinking and Data Analysis Exam 4”**
    Link: Massachusetts Institute of Technology: Cynthia Rudin’s
    [“Statistical Thinking and Data Analysis Exam
    4”](http://ocw.mit.edu/courses/sloan-school-of-management/15-075j-statistical-thinking-and-data-analysis-fall-2011/exams/MIT15_075JF11_exam04.pdf) (PDF)  
        
     Instructions: Answer question 3, on page 4 of the exam.  
        
     Answering this question should take approximately 1 hour.  
        
     Terms of Use: These articles are licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/us/deed.en_US).
    They are attributed to Massachusetts Institute of Technology, and
    the original versions can be found
    [here](http://ocw.mit.edu/courses/sloan-school-of-management/15-075j-statistical-thinking-and-data-analysis-fall-2011/exams/).

-   **Assessment: McGraw Hill: Bowerman, O’Connell, Schermer, and
    Adcock’s “Business Statistics in Practice: Multiple Choice Quiz for
    Chapter 11”**

    Link: McGraw Hill: Bowerman, O’Connell, Schermer, and Adcock’s
    [“Business Statistics in Practice: Multiple Choice Quiz for Chapter
    11”](http://highered.mcgraw-hill.com/sites/0070983755/student_view0/chapter11/multiple_choice_quiz.html)
    (HTML)  
        
     Instructions: Click on the link above and answer all questions in
    the quiz. Select your answer from the choices given for each
    question. Click on “Submit Answers” at the bottom of the webpage
    when you have answered all the questions. The webpage will tell you
    whether your answer is correct and what the correct answer is.  
      
     Completing this quiz should take approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: The Saylor Foundation’s “Simple Linear Regression”**

    Link: The Saylor Foundation’s [“Simple Linear
    Regression](https://resources.saylor.org/archived/wp-content/uploads/2012/04/MA251-Assigment-for-Unit-1.4.FINAL_.pdf)[”](https://resources.saylor.org/archived/wp-content/uploads/2012/04/MA251-Assigment-for-Unit-1.4.FINAL_.pdf)
    (PDF)

    Instructions: Complete the linked assessment, titled “Simple Linear
    Regression.” When you are done, solutions can be
    found [here](http://www.zoologi.su.se/education/courseweb/statistics/exercises/),
    under “Exercise2RSolutions.pdf”. 

    Completing this assessment should take you no longer than 4 hours.
    If you have not done so already, click on the following
    link<http://cran.r-project.org> to download and install R on your
    computer. R will be used throughout the course for assignments.

**Unit 1 Assessment** <span id="1.5"></span> 
-   **Assessment: The Saylor Foundation’s “Unit 1 Assessment”**
    Link: The Saylor Foundation’s [“Unit 1
    Assessment”](http://school.saylor.org/mod/quiz/view.php?id=1318)  
        
     Instructions: Complete this assessment to gauge your understanding
    of the materials covered thus far in this course. When you click
    “submit,” you will be shown the correct answers.


