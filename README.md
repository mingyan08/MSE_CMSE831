# CMSE 831: Computational Optimization (3 Credits)

## Spring 2021

Instructor: [Ming Yan](http://users.math.msu.edu/users/yanm/) [[email: myan@msu.edu](mailto:myan@msu.edu)]

+ Time: Monday and Wednesday 4:10 pm -- 5:30 pm EST
+ Location: Zoom (see [D2L](https://d2l.msu.edu/d2l/loginh/) for Zoom access information)
+ Office Hours: Monday and Wednesday 5:30 pm -- 6:30 pm EST. Additional Zoom office hours by appointment.
+ Textbook: none

Discussions in [Piazza: https://piazza.com/msu/spring2021/cmse831](https://piazza.com/msu/spring2021/cmse831) 

### Course Description

This course aims at providing students optimization algorithms and their applications in big data analysis, with a special emphasis on deep understanding on various optimization algorithms. Mathematics is heavily involved in this course. 

### Course Objectives

After this course, students should be able to

+ formulate a scientiﬁc problem into an optimization problem that can be solved;
+ understand the mathematical background for diﬀerent optimization methods (convergence analysis and the motivation of the algorithms);
+ numerically implement optimization algorithms;
+ solve scientiﬁc problems using optimization methods.

### Recommended Background

+ Math: In this course, linear algebra, matrix computation, and analysis will be heavily involved. 

+ Programming: You will be using Matlab or Python for programming. 

### References

+ First-Order Methods in Optimization, Amir Beck (2017), SIAM
+ Numerical Linear Algebra, Trefethen and Bau (1997), SIAM
+ Convex Optimization Boyd and Vandenberghe (2004), Cambridge University Press 
+ Numerical Optimization, Nocedal and Wright (2006), Springer
+ Convex Optimization Algorithms, D. Bertsekas, Athena Scientiﬁc
+ Parallel and Distributed Computation, D. Bertsekas and J. Tsitsiklis, Athena Scientiﬁc
+ Introductory Lectures on Convex Optimization: A Basic Course, Y. Nesterov, Kluwer
+ Introduction to Optimization, B. T. Polyak, Optimization Software
+ Sparse Modeling for Image and Vision Processing, Mairal, Bach and Ponce (2014), Foundations and TrendsR
  in Computer Graphics and Vision, Vol. 8, pp 85-283
+ First-order and Stochastic Optimization Methods for Machine Learning, Lan (2020), Springer

### Zoom and Online Resources

The lecture meetings will be in Zoom. There are workshops on online resources from MSU IT  https://iteach.msu.edu/iteachmsu/groups/iteachmsu/stories/1389

+ Student Semester Kick-oﬀ: January 11th Session 1: 10 AM to 11:15 AM; Session 2: 2 PM to 3:15 PM
+  D2L Basics for MSU Students: January 15th Session 1: 10 AM to 11:15 AM; Session 2: 2 PM to 3:15 PM

### Homework

+ There will be **FIVE** homework in total.
+ It will be assigned on D2L.
+ **No late homework will be accepted**

### Course Project

+ Group size: up to **three** students

+ Topics (anything related to the computational optimization):
  + Applications: 
    + Identify an application problem, formulate it into an application problem, solve this optimization problem using one or more optimization algorithms. 
    + For example, phase retrieval, compressive sensing, matrix factorization, regression, classification.
  + Algorithms: Usually, many different algorithms can solve the same optimization problem.  
    + Identify an optimization problem, compare several optimization algorithms for this problem theoretically or numerically.  
    + For example, decentralized consensus problem; distributed algorithms with compression, algorithms with differential privacy.
  + Theory: 
    + Identify an optimization algorithm and write a report on this algorithm's theoretical analysis (convergence and rates).
    + For example, ADAM for training neural networks, variance reduction algorithms (SARAH, STORM, and SVRG).

+ Feel free to talk to me about the project during all stages.

+ The project proposal is **DUE March 1st**. (Two-page report includes group members, the problem, the
  approaches, and the distribution of the work among the group members and the milestones.)

+ Final report is **DUE April 30th**. 

+ Group presentation at the end of this semester (**April 21st and April 19th (if needed)**).

  

### Grading

+ Participation: 20%
+ Homework: 40%
+ Project: 40%

### Tentative Topics

+ Review of numerical linear algebra
+ Optimization terms, types, and global vs local solutions
+ Convexity: sets, functions, key inequality, duality
+ First order optimization methods: Gradient method, Quasi-Newton methods, Subgradient method, Proximal gradient method, Accelerated proximal gradient methods, Proximal point method, Douglas-Rachford splitting and ADMM, Primal-dual proximal methods, Frank-Wolfe methods, Mirror descent algorithm, etc
+ Stochastic gradient methods
+ Parallel, distributed, and decentralized optimization
+ Monotone-operator and operator splitting methods

### Tentative Schedule

|      | Date          | Topics                                                       | Remark |
| ---- | ------------- | ------------------------------------------------------------ | ------ |
|      | 01/11-15/2021 | **Review Week**                                              |        |
|      | 01/18/2021    | **MLK Day (No Class)**                                       |        |
| 1    | 01/20/2021    | Introduction + Linear Algebra (1)                            |        |
| 2    | 01/25/2021    | Linear Algebra (1)                                           |        |
| 3    | 01/27/2021    | Convex Optimization (2)                                      |        |
| 4    | 02/01/2021    | Convex Optimization (2)                                      |        |
| 5    | 02/03/2021    | Gradient Method (3)                                          |        |
| 6    | 02/08/2021    | Gradient method (3)                                          |        |
| 7    | 02/10/2021    | Subgradients (4)                                             |        |
| 8    | 02/15/2021    | Subgradients (4)                                             |        |
| 9    | 02/17/2021    | Subgradient Method (5)                                       |        |
| 10   | 02/22/2021    | Subgradient Method (5)                                       |        |
| 11   | 02/24/2021    | Proximal gradient method (6)                                 |        |
| 12   | 03/01/2021    | Accelerated proximal gradient method (7)                     |        |
|      | 03/03/2021    | **Break Day (No Class)**                                     |        |
| 13   | 03/08/2021    | Accelerated proximal gradient method (7)                     |        |
| 14   | 03/10/2021    | Accelerated proximal gradient method (7)                     |        |
| 15   | 03/15/2021    | Conjugate Functions + Proximal mapping (8)                   |        |
| 16   | 03/17/2021    | Proximal point methods (9)                                   |        |
| 17   | 03/22/2021    | Proximal point methods (9) + Dual proximal gradient method (10) |        |
| 18   | 03/24/2021    | Dual proximal gradient method (10) + Smoothing (11)          |        |
| 19   | 03/29/2021    | Smoothing (11)                                               |        |
| 20   | 03/31/2021    | Smoothing (11) + Stochastic gradient method (12)             |        |
| 21   | 04/05/2021    | Stochastic gradient method (12)                              |        |
| 22   | 04/07/2021    | Stochastic gradient method (12)                              |        |
| 23   | 04/12/2021    | DRS- ADMM (13)                                               |        |
| 24   | 04/14/2021    | DRS- ADMM (13)                                               |        |
| 25   | 04/19/2021    | Project Presentation                                         |        |
| 26   | 04/21/2021    | Project Presentation                                         |        |

## Course Policies

### Course Announcements

+ Announcements will be emailed to the course mailing list (D2L). If you do **NOT **receive the welcome message before the first class, please let me know.

### Policy for Missing a Required Assignment
+ Excused absences will be given only with documentation and only for valid medical reasons, university business, or appearances in court.
+ Any unexcused work will be counted as a 0, including the ﬁnal exam if there is one.
+ Any student with a valid reason to be excused from a work must contact the instructor prior to the work or due date and present documentation in the next class session attended.

### Grading Complaints

+ If you notice a mistake, you have to bring it to my attention within one week after the day your work was returned.
+ Grading complaints not initiated within this period of time will not be considered.

### Regrading

+ If you believe a question has been graded incorrectly, please submit an explanation on a separate sheet of paper, attach it to the work in question, and submit it to me within one week after the day your work was returned.

### Academic Honesty

+ Cheating of any kind is wrong.
+ Academic dishonesty includes, but is not limited to: copying homework solutions, cheating on any of the exams (including using material not allowed to be used).
+ The students are allowed to discuss homework problems with each other, but they must write their solutions on their own.
+ For more detailed information, visit the Ombud’s website for academic integrity: https://ombud.msu.edu/resources-self-help/academic-integrity.

### Students with Disabilities

If you have a disability that requires some kind of accommodation, you should contact the Resource Center for Persons with Disabilities (RCPD) as soon as possible.

+ To make an appointment with a specialist, contact: (517) 353-9642 or TeleTYprewriter (TTY): (517) 355-1293
+  Web site for RCPD: http://MYProﬁle.rcpd.msu.edu 

### Changes in the Syllabus
There may be changes to the syllabus during the semester. These changes will be mentioned in class or by email, but it is ultimately the responsibility of the student to remain aware of any changes.
