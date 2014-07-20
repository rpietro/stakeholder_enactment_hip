# Randomized controlled trial comparing the "stakeholder enactment" online educational methodology vs. traditional online learning, applied to the training on classification, biomechanics and therapeutic planning of low back pain


Ana Paula Bonilauri Ferreira
Carlos Maçaneiro
Bruno Melo
João Ricardo Vissoci
Ricardo Pietrobon

## Abstract
<!-- will write at the end -->

## Introduction
Low back pain is not only highly prevalent among the general population, but lead to a high level of disability <!-- ref -->. Despite its high prevalence and significant disability, clinicians in general are usually not aware of the latest evidence regarding its diagnosis and treatment <!-- ref -->. While modern online educational methods could potentially alleviate this problem, to our knowledge no previous online educational randomized trials have evaluated the efficacy of such protocols.

* previous studies on variation in diagnostic and treatment procedures for low back pain
* previous studies on education regarding Clinical Practice Guidelines applied to low back 

In face of so much variation in diagnostic and treatment of low back pain, the aim of the online, reproducible randomized controlled trial is to compare the "stakeholder enactment" educational methodology versus a traditional learning with texts in relation to knowledge, satisfaction with learning experience and impact on clinical practice.

## Methods
#### Trial design
This is an educational, parallel randomized controlled trial comparing the use of the stakeholder enactment methodology (enactment arm) in an online learning environment for 4 weeks vs. standard training (control arm), evaluated in a sample of healthcare professionals who interfaced with low back pain. Outcomes included measures of (1) knowledge about evidence-based diagnostic and therapeutic procedures, (2) learning experience including satisfaction with the platform and the course content, and (3) self-reported impact of course content on clinical practice. We hypothesize that measures of knowledge, satisfaction and impact on clinical practice will all be significantly increased in the enactment arm compared to the control arm.

Per CONSORT Statement recommendations, any eventual changes to trial design occurring throughout the trial were recorded in our versioning system ([Github](https://github.com/)), thus ensuring full reproducibility. Our trial was also registered under both the [http://clinicaltrials.gov/](http://clinicaltrials.gov/) and the Brazilian Clinical Trials Registry ([Registro Brasileiro de Ensaios Clínicos, ReBEC](http://www.ensaiosclinicos.gov.br/)) <!-- add number -->

####  Participants

Participants included those registering through a series of emails circulated through a campaign of dissemination of the best evidence in musculoskeletal conditions as well as through other mailing lists reaching out to general practitioners and students. <!-- might need to improve this later --> . 



####  Study settings

The study was conducted using the online [Open edX](http://code.edx.org/) platform Learning Management System. 


Briefly, potential participants went through the following steps: (1) All persons willing to participate were offered informed consent, with a reassurance that their non-participation did not have any effect on their educational programs and/or professional activities, (2) registered and logged into the platform, (3) both study arms logged at least once/week to receive educational material as well as fill out questionnaires about each of the trial outcome measures. 

<!-- add figure -->

Participants were recruited through email using previously existing mailing lists as described in the Participants section. Three waves of recruitment were conducted, each email allowing potential participants to be excluded from the mailing list if they might have desired. 


#### Interventions

The interventions involving stakeholder enactment (enactment arm) and standard training (control arms) were structured as follows:

##### Standard training (control arm)
When participants logged into the Open edX platform, they will receive standard Clinical Practice Guideline documentation, in Portuguese, regarding diagnostic a treatment recommendations. <!-- additional details -->



##### Stakeholder enactment model intervention (enactment arm)

The educational intervention was also delivered through the Open edX platform through weekly modules over four weeks. 

<!-- 
conduct qualitative study to see what works best:

1. case in text and recommendation in text
1. case in text and recommendation in video
1. case in video and recommendation in video

 -->

Similar to what happened in the control group, participants had the opportunity to interact with each other and the instructors. Interactions across the two intervention arms will not occur as this would lead to contamination in the experiment. 

####  Outcome variables

Our study had three main categories of outcome variables: Knowledge, User eXperience (UX) and impact on clinical practice, all described under the subsequent sections. Per CONSORT Statement guidelines, any eventual changes to outcome measures deviating from the initial plan and occurring throughout the trial were recorded in our versioning system ([Github](https://github.com/rpietro/stakeholder_enactment_hip)), thus ensuring full reproducibility. However, changes were avoided unless strictly necessary.

##### Knowledge

Knowledge was measured through a group of questions (items) under three main domains, namely: fracture diagnosis, biomechanics and therapeutic planning. Given that there are no standardized scales to measure knowledge within each of these domain areas, we will conduct a parallel validation using a combination of Classical Psychometric Theory and Item Response Theory, both methods having been extensively used in previous publications by two of our investigators specialized in psychometric methods and latent variable modeling (RP and JRV).

An item (question) pool was initially created by the orthopedic surgeons in this proposal (TB, TY, RP), covering all four types of fractures (pediatric elbow, adult wrist, adult cervical spine and adult ankle) in all three areas of the clinical path (diagnosis, biomechanics and therapeutic planning), ultimately constituting 12 (3 times 4) items sets with 30 items (questions) each, for a total of 360 (12 times 30) items (questions). 

A randomly selected subset of this item pool of 840 items were exposed to the participants in our trial, using an anchoring approach for linked scales where each set contains a constant group of items that is repeated in every set, thus ensuring that all sets are connected. Subsequently, a sequence of exploratory and confirmatory factor analyses, reliability evaluation within each individual construct, and validity triangulating across different items were used to achieve a psychometrically valid summed construct-specific and overall scores to serve as the variables representing the knowledge outcome of our trial. Details about each of these analyses are presented within the Data Analysis section.

Knowledge evaluation occurred at baseline and then at the end of weeks two and four. These assessments are automatically recorded within the edX Code platform under two databases ([MySQL](http://www.mysql.com/) for participant information and [MongoDB](https://www.mongodb.org/) for exercise information), both with a common id.

##### User eXperience

In this study we will primarily measure User eXperience (UX) as participant satisfaction while participating in each of the two interventions. While the literature on the measurement of satisfaction within online education is vast, (see @banks2007reduction, @dibiase2005scaling and @ summers2005comparison for a few examples)  <!-- see http://www.westga.edu/~distance/ojdla/Fall133/sampson_ballenger133.html (Banks & Faul, 2007; Debourgh, 1998; Dibiase & Rademacher, 2005; Enockson, 1997; Heiman, 2008; McCabe, 1997; Summers, Waigandt, & Whittaker, 2005; Walker & Kelly, 2007). Several other studies focused on student and teacher interactions and perceptions of learning (Heiman, 2008; Rovai & Barnum, 2003); and social presence (Richardson & Swan, 2003) as part of students’ satisfaction. --> we have elected to use the scale developed by [Kuo et cols](http://www.irrodl.org/index.php/irrodl/article/view/1338/2416) since it is not only comprehensive but has also been shown to be psychometrically valid. The Sampson scale covers seven satisfaction sub-constructs, namely satisfaction with learner-learner interaction, learner-instructor interaction, learner-content interaction and overall satisfaction. Cronbach's alpha reliability was found to be above 0.88 for all subscales, the Kuo scale also having been validated against student self-efficacy. 

Satisfaction was assessed at the end of weeks two and four using a set of questionnaires provided within the Open edX platform. These assessments are automatically recorded within the platform.

##### Impact on clinical practice

The last evaluated construct was the impact on clinical practice. Given that, to our knowledge, no previously validated scale has been devised to measure the impact of online learning on clinical practice, we have also devised a concomitant validation strategy. 

Impact on clinical practice was measured through a group of questions (items) under one single domain (unidimensional scale). The item (question) will focus on "How much has the knowledge you gained in this course has positively or negatively influenced your clinical practice in {{setting}}, where 0 means no influence at all and 10 means an extremely influence," where {{setting}} represents different settings such as ambulatory, emergency, floor and discussions with colleagues. A five-point Likert alternative pattern will then cover the spectrum of positive or negative influence.

This group of items were exposed to the participants in our trial. Similar to the knowledge domain, a sequence of exploratory and confirmatory factor analyses, reliability evaluation within each individual construct, and validity triangulating across different items were used to achieve a psychometrically valid summed score serving as the outcome measuring impact on clinical practice for our trial. Further details on how each of these analyses were conducted are presented within the Data Analysis section.

Knowledge evaluation occurred at the end of weeks two and four. These assessments are also automatically recorded within the platform.


####  Sample size

Given the absence of preliminary efficacy data, we calculated our sample size based on an assumption of a two-sample t-test for an index representing the worst case scenario for each of the three outcomes, with an effect size of 55%, a significance level and statistical power set at the traditional levels of 0.05 and 80%, respectively. Under these assumptions the estimated required sample size is of 52.9 per group, which we have rounded to 53, ultimately leading to a total sample size of 106 participants in total. Taking into account a worst case scenario dropout rate of approximately 20%, we therefore planned to enroll 150 participants.


####  Interim analyses and stopping guidelines

Given the relatively short duration of our trial, we do not intend to perform an interim analyses. In addition, given the low risk associated with the intervention, our guidelines will only recommend that the trial be stopped in case of an unlikely loss of confidentiality that might compromise participants privacy.

####  Randomization: sequence generation

All randomization schedules were delivered through [Planout](http://facebook.github.io/planout/). Briefly, Planout makes use of a pseudorandom number generator from the [Python language](https://www.python.org/), which has been extensively tested. <!-- need ref --> Randomization was blocked at 10 participants, thus decreasing the likelihood of a possible imbalance.

All randomization was delivered through the Open edX platform, thus ensuring that participants and investigators were blind to the allocation. Data analysts (RP, JRV) received a dataset from one the computer scientists (BM) where the two randomization arms were designated by unspecific letters, thus ensuring that the analysis was also conducted in a blind fashion.


#### Statistical methods 

All analyses were conducted by the members in our team with experience and graduate degrees related to Data Science (RP, JRV). The data analysis started with an overall evaluation of individual fields to assess distributions for continuous variables (e.g., participant's age) in terms of their distributions, as well as the frequency/percentage for categorical variables (e.g., gender). 

Missing values were handled differently if they happened to individual variables or full encounters, e.g., an entire evaluation for a week. Individual variables were imputed starting by an exploratory visual analysis to better understand the potential underlying pattern behind missing values for each variable. This analysis was conducted using the [VIM package](http://cran.r-project.org/web/packages/VIMGUI/vignettes/VIM-Imputation.pdf) within the [R language](http://www.r-project.org/). Depending on the pattern of missing data, we might then choose one of several alternatives, ranging from not imputing when the percent missing might be negligible, imputing using predictive models from variables that were hypothesized to be associated with the missing values (e.g., age predicting residency year), or multiple imputation in cases where missing patterns were happening at random (MAR or missing at random) (@rubin1976inference).

We evaluated for potential confounding of the intervention effect by assessing balance across baseline variables between the enactment and control arms. This evaluation occurred for the overall study. While imbalances are unlikely given that we are using a series of preventive measures (blinding, concealed allocation, blocking and stratification), imbalances were evaluated on an individual basis to judge whether adjusting in our modeling strategy would be required (see below for details).

The psychometric analysis for parallel validation of our scales started with an Exploratory Factor Analysis to evaluate the underlying dimensional structure of our item pool. We then conducted a Confirmatory Factor Analysis using the hypothesized domains (see Outcome Variable section for details). Once domains were established we used Cronbach's alpha to measure internal reliability within each construct. Validity was measured by triangulation across different domains. For example, it is believed that if a professional is able to understand the biomechanics of a given fracture, then the construct for therapeutic planning should be highly associated with that previous construct.

Given that all of our outcomes had multiple endpoints over time, we used a combination of mixed models and survival analysis to measure the efficacy associated with the enactment arm in comparison with the control arm. To formally test trends in each of our outcome variables over time (knowledge, User eXperience and impact on clinical practice) we developed mixed models that accounted for multiple measures as random a effect. For each time period we also assessed differences in scores, comparing the three subgroups. These bivariate analyses incorporated robust standard errors to account for the clustering effect. Survival models included Cox Proportional Hazards models measuring time until an information reached clinical practice. The hazards assumption were tested prior to analyses and eventual ties were resolved. 


## Results


## Discussion