---
layout: default
title: "MA251: Statistics II"
course_description: "A review of basic statistics and an application of statistical tools and techniques that are routinely used by modern statisticians for building models to analyze complex, multivariate problems."
next: ../Unit01
previous: ../../../
---
Course Syllabus for "MA251: Statistics II"
------------------------------------------

**Please note: this [legacy course](https://sayloracademy.zendesk.com/hc/en-us/articles/206089967) does not offer a certificate and may contain 
broken links and outdated information.** Although archived, it is open 
for learning without registration or enrollment. Please consider contributing 
updates to [this course on GitHub](https://github.com/saylordotorg/course_ma251) 
(you can also adopt, adapt, and distribute this course under the terms of 
the [Creative Commons Attribution 3.0 license](http://creativecommons.org/licenses/by/3.0/)). **To find fully-supported, current courses, [visit our 
Learn site](https://learn.saylor.org).**

This course will introduce you to a number of statistical tools and
techniques that are routinely used by modern statisticians for a wide
variety of applications. First, we will review basic knowledge and
skills that you learned in [MA121: Introduction to
Statistics](http://www.saylor.org/courses/ma121/). Units 2-5 will
introduce you to new ways to design experiments and to test hypotheses,
including multiple and nonlinear regression and nonparametric
statistics. You will learn to apply these methods to building models to
analyze complex, multivariate problems. You will also learn to write
scripts to carry out these analyses in R, a powerful statistical
programming language. The last unit is designed to give you a grand tour
of several advanced topics in applied statistics.

### Learning Outcomes

Upon successful completion of this course, the student will be able to:

-   <span dir="LTR">apply statistical hypothesis testing for one
    population;</span>
-   <span dir="LTR">conduct statistical hypothesis testing and
    estimation for two populations;</span>
-   <span dir="LTR">apply multiple regression analysis to analyze a
    multivariate problem;  </span>
-   <span dir="LTR">analyze the outputs for a multiple regression model
    and interpret the regression results;  </span>
-   <span dir="LTR">conduct t</span>est hypotheses about the
    significance of a multiple regression model and test the
    significance of the independent variables in the model;
-   <span dir="LTR">select appropriate multiple regression models using
    automatic model selection, forward selection, backward elimination,
    and stepwise selection;</span>
-   <span dir="LTR">recognize and address issues when using multiple
    regression analysis;</span>
-   <span dir="LTR">identify situations when nonparametric tests are
    appropriate;</span>
-   <span dir="LTR">conduct nonparametric tests; and</span>
-   <span dir="LTR">explain the principles underlying General Linear
    Model, Multilevel Modeling, Data Mining, Machine Learning,
    </span>Bayesian Belief Networks, Neural Network, and Support Vector
    Machine.

### Course Requirements

In order to take this course, you must:  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">√
   </span>have access to a computer;</span>  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">√
   </span>have continuous broadband Internet access;</span>  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">√
   </span>have the ability/permission to install plug-ins or software
(e.g., Adobe Reader or Flash);</span>  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">√
   </span>have the ability to download and save files and documents to a
computer;</span>  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">√
   </span>be able to download and install R;</span>  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">√
   </span>have the ability to open Microsoft files and documents (.doc,
.ppt, .xls, etc.);</span>  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">√
   </span>be competent in the English language;</span>  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">√
  </span> have read the [Saylor Student
Handbook](http://www.saylor.org/site/wp-content/uploads/2012/05/Saylor-StudentHandbook.pdf);
and  
  
 <span dir="LTR"><span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; text-align: left; -webkit-text-size-adjust: none; ">√
   </span>have completed the following course: </span>[MA121:
Introduction to Statistics](http://www.saylor.org/courses/ma121/).

### Course Information

Welcome to MA 251. Below, please find some general information on the
course and its requirements.  
    
 **Course Designer:** Tuan Dinh  
    
 **Primary Resources**: This course is comprised of a range of different
free, online materials. However, the course makes primary use of the
following:  

-   MIT: Dmitry Panchenko’s “[Statistics for
    Applications](http://ocw.mit.edu/courses/mathematics/18-443-statistics-for-applications-fall-2006/lecture-notes/)”
    Lecture Notes;
-   University of Florida: Alan Agresti’s “[Statistical Methods for the
    Social Sciences II](http://www.stat.ufl.edu/~aa/sta6127/)” course;
    and
-   Jeff Miller and Patricia Haden’s “[Statistical Analysis with the
    General Linear
    Model](http://psy.otago.ac.nz/miller/index.htm#GLMBook)”.

**Requirements for Completion**: In order to complete this course, you
will need to work through each unit and all of its assigned materials.
The quizzes are designed to test your knowledge of the topics covered in
the readings and the video lectures. The assignments are designed to
teach you how to apply what you learn through the readings and the video
lectures to solve real-world statistical problems, using R package. In
order to complete this course, you will need to earn a 70% or higher on
the Final Exam. Your score on the exam will be tabulated as soon as you
complete it. If you do not pass the exam, you may take it again.  
    
 **Time Commitment**: The materials for this course will take
approximately **188 hours** to complete. Note that the time advisory for
each unit also contains a time advisory for creating the element of
courseware described in that unit.  
  
**Table of Contents:** You can find the course's units at the links below.

- [Unit 1](https://legacy.saylor.org/ma251/Unit01/)
- [Unit 2](https://legacy.saylor.org/ma251/Unit02/)
- [Unit 3](https://legacy.saylor.org/ma251/Unit03/)
- [Unit 4](https://legacy.saylor.org/ma251/Unit04/)
- [Unit 5](https://legacy.saylor.org/ma251/Unit05/)
- [Unit 6](https://legacy.saylor.org/ma251/Unit06/)
- [Unit 7](https://legacy.saylor.org/ma251/Unit07/)
- [Final Exam](http://saylordotorg.github.io/LegacyExams/MA/MA251/MA251-FinalExam.html), [Answers](http://saylordotorg.github.io/LegacyExams/MA/MA251/MA251-FinalExam-Answers.html)
