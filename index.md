---
layout: default
---

# Special Topics in Data Science: Machine Learning for Healthcare (DS-GA.3001-005/ CSCI-GA.3033-083)

## Course Staff
* __Instructor:__ [Rajesh Ranganath](https://cims.nyu.edu/~rajeshr/)
* __Course Assistant:__  [Aahlad Puli](https://aahladmanas.github.io/)
* __Grader:__ [Mukund Sudarshan](https://cs.nyu.edu/~sudarshan/)

## Course Description
This is a seminar course that covers machine learning methods important for healthcare including causal inference, k-shot learning, time series models, and fairness. We will learn about important clinical questions and the data (such as from ICU monitors and imaging) that along with machine learning can help answer these questions. We will focus on recent work in machine learning for healthcare.

## Schedule and Reading Assignments

* __(Wednesday, September 9, 2020) Introduction and Opportunities and Challenges in Healthcare__  
	+  __Lab session__ : None
* __(Monday, September 14, 2020) Risk Scores and Survival__  
	+ [Opportunities in Machine Learning for Healthcare](https://arxiv.org/pdf/1806.00388.pdf)
	+ [Big Data In Health Care: Using Analytics To Identify And Manage High-Risk And High-Cost Patients](https://www.healthaffairs.org/doi/full/10.1377/hlthaff.2014.0041)
	+ [Prediction of Coronary Heart Disease Using Risk Factor Categories](https://www.ahajournals.org/doi/full/10.1161/01.cir.97.18.1837)
	+ __Lab session__ :  Probability
* __(Monday, September 21, 2020) Missing Data and the Electronic Health Record__  
	+ [Recurrent Neural Networks for Multivariate Time Series with Missing Values](https://arxiv.org/pdf/1606.01865.pdf)
	+ [Inference and missing data](https://academic.oup.com/biomet/article-abstract/63/3/581/270932)
	+ [Electronic Health Records](http://discovery.ucl.ac.uk/1598/1/A22.pdf) : A quick skim will suffice
	+ __Lab session__ :  Regression Models + Deep Learning
* __(Monday, September 28, 2020) COVID-19__  
	+ [Digital technology and COVID-19](https://www.nature.com/articles/s41591-020-0824-5)
	+ __Lab session__ :  Pytorch
* __(Monday, October 5, 2020) Feature Selection and Model Interpretation__  Warning, lots of reading this week!
	+ [Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization](https://arxiv.org/abs/1610.02391)
	+ [A Unified Approach to Interpreting Model Predictions](https://arxiv.org/pdf/1705.07874.pdf)
	+ [Panning for Gold: Model-X Knockoffs for High-dimensional Controlled Variable Selection](https://arxiv.org/pdf/1610.02351.pdf). Sections 1-4
	+ [Robust and Stable Black Box Explanations](https://proceedings.icml.cc/static/paper_files/icml/2020/5945-Paper.pdf)
	+ __Lab session__ :  Using MIMIC Data
* __(Monday, October 12, 2020) Clinical NLP (Guest Lecture)__  
	+ __Lab session__ : Building a Model with MIMIC Data
* __(Monday, October 19, 2020)  Causal Inference from Observational Data__  
	+ [Statistics and Causal Inference](https://www.jstor.org/stable/2289064)
	+ Chapter 2, Counterfactuals and Causal Inference, 2ed, Morgan and Winship.
	+ __Lab session__ :  Practical Causal Inference
* __(Monday, October 26, 2020) Fairness__  
	+ [Ensuring Fairness in Machine Learning to Advance Health Equity](https://www.acpjournals.org/doi/10.7326/M18-1990)
	+ [Fair Regression for Health Care Spending](https://arxiv.org/pdf/1901.10566.pdf)
	+ [Dissecting racial bias in an algorithm used to manage the health of populations](https://science.sciencemag.org/content/366/6464/447)
	+ [Machine Learning and Health Care Disparities in Dermatology](https://jamanetwork.com/journals/jamadermatology/article-abstract/2688587)
	+ [Creating Fair Models of Atherosclerotic Cardiovascular Disease Risk](https://dl.acm.org/doi/10.1145/3306618.3314278)
	+ __Lab session__ :  Causal Inference and Fairness
* __(Monday, November 2, 2020) Medical Imaging__  
	+ [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/pdf/1505.04597.pdf)
	+ [Classification and mutation prediction from non small cell lung cancer histopathology images using deep learning](https://www.nature.com/articles/s41591-018-0177-5) 
	+ [Transfusion: Understanding Transfer Learning for Medical Imaging](https://papers.nips.cc/paper/8596-transfusion-understanding-transfer-learning-for-medical-imaging.pdf)
	+ __Lab session__ :  Training a U-Net
* __(Monday, November 9, 2020) M-Health (Guest Lecture)__  
	+ __Lab session__ :  
* __(Monday, November 16, 2020) Physiologic Time Series__  
	+ [Understanding vasopressor intervention and weaning: risk prediction in a public heterogeneous clinical time series database ](https://academic.oup.com/jamia/article/24/3/488/2907906)
	+ [Interpolation-prediction networks for irregularly sampled time series](https://arxiv.org/pdf/1909.07782.pdf)
	+ __Lab session__ :  TBD
* __(Monday, November 23, 2020) Reinforcement Learning in Healthcare__  
	+ [Guidelines for reinforcement learning in healthcare](https://www.nature.com/articles/s41591-018-0310-5)
	+ [POPCORN: Partially ObservedPrediction Constrained Reinforcement Learning](https://arxiv.org/pdf/2001.04032.pdf)
	+ [Optimizing Medical Treatment for Sepsis in Intensive Care: from Reinforcement Learning to Pre-Trial Evaluation](https://arxiv.org/abs/2003.06474)
	+ __Lab session__ :  Basics of Reinforcement Learning
* __(Monday, November 30, 2020) Technical Aside : Efficiency Theory__  
	+ Semiparametric Theory and Missing Data, Anastasios A. Tsiatis, Chapter 2 ([Available via NYU library](https://link-springer-com.proxy.library.nyu.edu/book/10.1007%2F0-387-37345-4))
	+ __Lab session__ :  Influence Functions
* __(Monday, December 7, 2020) Final Project Presentations__  
	+ __No Lab session__
	
## Course Structure

* Typically each class would be structured as 1/3 lecture, 1/6 discussion, and 1/2 student presentations, but due to the mixed instruction this fall, the format for the class meetings will be tilted more towards discussion and student presentations.

* Every lecture will be pre-recorded and the students are expected to watch the lecture prior to the class.
	+ Both the required readings and the lecture video will be available at least one day prior to the lecture.
	+ The lecture videos will be available in NYU classes (access with your registered NYU email).
	+ Reading responses are due at the beginning of the class on Gradescope.

* Each class will be split up into two parts:
	+ Lecture Discussion (\~30min)
	+ Two student presentations of 35 min each (\~25 min + \~10 min for questions)
* Students can join the discussion and do their class presentations over zoom or in-person.
* A few lectures will be presentations from ML researchers in the industry working on health.
* The lab session will be both in-person and over zoom and will be recorded.

### Lecture Location
Monday, 2:00-3:40pm, in [CANT Room:200](https://www.nyu.edu/students/student-information-and-resources/registration-records-and-graduation/registration/classroom-locations.html)

### Recitation/Laboratory
Tuesdays, 1:00-1:50pm, in [SILV, 405](https://library.nyu.edu/services/campus-media/classrooms/silv-405/)

### Office hours
Monday 4:15pm-5:15pm, on zoom. Links will be posted on NYUClasses.

### Grading
The final project will be the majority of the grade. 
The project report is due on 12/14/20. There will be an
in class presentation on 12/7/20.
In addition to the research paper, a weekly reading response
is due before class. People will be required to make an in class
presentation at least once in the term. The presentation 
can be on a research paper, a dataset, a tool, or their 
current project. The grading is
  +  Reading Responses sets (10%)  
  +  Lecture scribe (10%)
  +  Class presentation (10%)
  +  Participation (5%)
  +  Final Project (65%)

### Piazza 
We will use [Piazza](http://piazza.com/nyu/fall2020/dsga3001005/) to answer questions and post announcements about the course. Please sign up [here](http://piazza.com/nyu/fall2020/dsga3001005). Students' use of Piazza, particularly for adequately answering other students' questions, will contribute toward their participation grade.
