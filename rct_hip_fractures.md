# Randomized controlled trial comparing the "stakeholder enactment" online educational methodology vs. traditional online learning, applied to the training on classification, biomechanics and therapeutic planning of hip fractures.

Ana Paula Bonilauri Ferreira
Carlos Maçaneiro
Ricardo Pietrobon

## Abstract
<!-- will write at the end -->

## Introduction
Hip fractures are not only highly prevalent among the elderly, but lead to a high level of morbidity as well as an overall mortality rate reaching x% within one year <!-- ref -->. Despite its high prevalence and significant morbidity and mortality, orthopedic surgeons and residents have a substantial degree of disagreement when it comes to its classification <!-- ref --> and, as a consequence, the appropriate therapeutic planning. While modern online educational methods could potentially alleviate this problem, to our knowledge no previous online educational randomized trials have evaluated the efficacy of such protocols.

* previous studies on agreement on hip fractures
* previous studies on treatment variability of hip fractures

In face of so much discrepancy on how hip fractures are diagnosed and therefore treated, the aim of the online, reproducible randomized controlled trial is to compare a novel educational methodology named "stakeholder enactment" versus a traditional learning with texts in relation to knowledge, satisfaction with learning experience and impact on clinical practice.

## Methods
#### Trial design
This is an educational, parallel randomized controlled trial comparing the use of the stakeholder enactment methodology (enactment arm) in an online learning environment for 4 weeks vs. standard training (control arm), evaluated in a sample of family orthopedic surgeons, healthcare students and healthcare providers interested in or interfacing with hip fractures. Outcomes included measures of (1) knowledge about biomechanics, diagnosis and therapeutic planning evaluated through clinical cases, (2) learning experience including satisfaction with the platform and the course content, and (3) self-reported impact of course content on clinical practice. We hypothesize that measures of knowledge, satisfaction and impact on clinical practice will all be significantly increased in the enactment arm compared to the control arm. As a secondary hypothesis, impact will be greater among students and non-orthopedic practitioners than among orthopedic surgeons and residents. We justify our secondary hypothesis since orthopedic surgeons and residents already have a pre-existing background within their formal training and therefore the degree of improvement would be smaller when compared to controls.

Per CONSORT Statement recommendations, any eventual changes to trial design occurring throughout the trial were recorded in our versioning system ([Github](https://github.com/)), thus ensuring full reproducibility. Our trial was also registered under both the [http://clinicaltrials.gov/](http://clinicaltrials.gov/) and the Brazilian Clinical Trials Registry ([Registro Brasileiro de Ensaios Clínicos, ReBEC](http://www.ensaiosclinicos.gov.br/)) <!-- add number -->

####  Participants

Participants included those registering through a series of emails circulated through Brazilian Society of Orthopedic Surgery and Trauma as well as through other mailing lists reaching out to general practitioners and students. <!-- might need to improve this later --> . This diverse sample will allow us to conduct subgroup analyses comparing the efficacy across the two previously mentioned subgroups (see section on Sample Size calculation for how this subgroup analysis has been accounted).




####  Study settings

The study will be conducted using the online Learning Management System [Open edX](http://code.edx.org/) platform. As previously described in the Preliminary Studies section, we have already conducted extensive usability and navigability studies with this platform, as well as being in the midst of an international trial with the University of Basilicata (Italy). (see Figure)

![](images/edx.png)


Briefly, potential participants will go through the following steps: (1) All persons willing to participate will be offered informed consent, with a reassurance that their non-participation will not have any effect on their educational programs and/or professional activities, (2) will register and log into the platform, (3) both study arms will log at least once/week to receive educational material as well as fill out questionnaires about each of the trial outcome measures. 

<!-- add figure -->

Participants will be recruited through email using previously existing mailing lists already obtained by our research group. Three waves of recruitment will be conducted, each email allowing potential participants to be excluded from the mailing list if they so might desire. In the event that the recruitment does not reach our expected sample size, additional groups from the community in the metropolitan region of São Paulo will be asked to participate, including other residency programs as well as professional mailing lists from Health Management Organizations.


#### Interventions

The interventions involving 3D modeling/animation (3D arm) and standard training (control arms) will be structured as follows:

##### Standard training (control arm)
When participants log into the Open edX platform, they will receive standard documentation as commonly found in textbooks, in Portuguese, regarding the common types of pediatric and adult bone fractures. We will present information on four groups of fractures (one fracture group per week), including elbow pediatric fractures, while for adults we will include wrist, ankle, and cervical spine. For each of these fracture patterns there will be additional information regarding the care of open fractures. 

Each text will contain a graphical representation of the fractures as well as textual explanations about biomechanics and therapeutic planning, thus mimicking what is encountered in standard training programs. Educational texts will be progressively delivered on a weekly basis, for a total of four weeks. 

Participants will have the opportunity to interact with each other and the instructors.


##### 3D models/animation intervention (3D arm)

The educational intervention will also be delivered through the Open edX platform through weekly modules over four weeks. The exact same set of fractures will be covered, although each module will be entirely focused on clinical cases making use of 3d models/animations as follows:

1. Each clinical case will be presented using an interactive interface using the [canvas tag](http://www.w3schools.com/tags/ref_canvas.asp) delivered through HTML5 as described under aim 1. 
2. Diagnosis: The interactive visualization will simulate the fracture mechanism in its different types and classifications.
3. Biomechanics: The interactive visualization will allow participants to observe the underlying biomechanics and why a given fracture might be related to a certain type of treatment, be it conservative or surgical. 
2. Therapeutic planning: The interactive visualization will display how different treatments can provide stability so that the fracture can appropriately heal and restore function.

Similar to what happened in the control group, participants will have the opportunity to interact with each other and the instructors. Interactions across the two intervention arms will not occur as this would lead to contamination in the experiment. 

####  Outcome variables

Our study will have three main categories of outcome variables: Knowledge, User eXperience (UX) and impact on clinical practice, all described under the subsequent sections. Per CONSORT Statement guidelines, any eventual changes to outcome measures deviating from the initial plan and occurring throughout the trial will be recorded in our versioning system ([Github](https://github.com/)), thus ensuring full reproducibility. However, changes will be avoided unless strictly necessary.

##### Knowledge

Knowledge will be measured through a group of questions (items) under three main domains, namely: fracture diagnosis, biomechanics and therapeutic planning. Given that there are no standardized scales to measure knowledge within each of these domain areas, we will conduct a parallel validation using a combination of Classical Psychometric Theory and Item Response Theory, both methods having been extensively used in previous publications by two of our investigators specialized in psychometric methods and latent variable modeling (RP and JRV).

An item (question) pool will be initially created by the orthopedic surgeons in this proposal (TB, TY, RP), covering all four types of fractures (pediatric elbow, adult wrist, adult cervical spine and adult ankle) in all three areas of the clinical path (diagnosis, biomechanics and therapeutic planning), ultimately constituting 12 (3 times 4) items sets with 30 items (questions) each, for a total of 360 (12 times 30) items (questions). 

A randomly selected subset of this item pool of 840 items will be exposed to the participants in our trial, using an anchoring approach for linked scales where each set contains a constant group of items that is repeated in every set, thus ensuring that all sets are connected. Subsequently, a sequence of exploratory and confirmatory factor analyses, reliability evaluation within each individual construct, and validity triangulating across different items will be used to achieve a psychometrically valid summed construct-specific and overall scores to serve as the variables representing the knowledge outcome of our trial. Details about each of these analyses are presented within the Data Analysis section.

Knowledge evaluation will occur at baseline and then at the end of weeks two and four. These assessments are automatically recorded within the edX Code platform under two databases ([MySQL](http://www.mysql.com/) for participant information and [MongoDB](https://www.mongodb.org/) for exercise information), both with a common id.

##### User eXperience

In this study we will primarily measure User eXperience (UX) as participant satisfaction while participating in each of the two interventions. While the literature on the measurement of satisfaction within online education is vast, (see @banks2007reduction, @dibiase2005scaling and @ summers2005comparison for a few examples)  <!-- see http://www.westga.edu/~distance/ojdla/Fall133/sampson_ballenger133.html (Banks & Faul, 2007; Debourgh, 1998; Dibiase & Rademacher, 2005; Enockson, 1997; Heiman, 2008; McCabe, 1997; Summers, Waigandt, & Whittaker, 2005; Walker & Kelly, 2007). Several other studies focused on student and teacher interactions and perceptions of learning (Heiman, 2008; Rovai & Barnum, 2003); and social presence (Richardson & Swan, 2003) as part of students’ satisfaction. --> we have elected to use the scale developed by [Kuo et cols](http://www.irrodl.org/index.php/irrodl/article/view/1338/2416) since it is not only comprehensive but has also been shown to be psychometrically valid. The Sampson scale covers seven satisfaction sub-constructs, namely satisfaction with learner-learner interaction, learner-instructor interaction, learner-content interaction and overall satisfaction. Cronbach's alpha reliability was found to be above 0.88 for all subscales, the Kuo scale also having been validated against student self-efficacy. 

Satisfaction will be assessed at the end of weeks two and four using a set of questionnaires provided within the Open edX platform. These assessments are automatically recorded within the platform.

##### Impact on clinical practice

The last evaluated construct will be the impact on clinical practice. Given that, to our knowledge, no previously validated scale has been devised to measure the impact of online learning on clinical practice, we have also devised a concomitant validation strategy. 

Impact on clinical practice will be measured through a group of questions (items) under one single domain (unidimensional scale). The item (question) will focus on "How much has the knowledge you gained in this course has positively or negatively influenced your clinical practice in {{setting}}, where 0 means no influence at all and 10 means an extremely influence," where {{setting}} represents different settings such as ambulatory, emergency, floor and discussions with colleagues. A five-point Likert alternative pattern will then cover the spectrum of positive or negative influence.

This group of items will be exposed to the participants in our trial. Similar to the knowledge domain, a sequence of exploratory and confirmatory factor analyses, reliability evaluation within each individual construct, and validity triangulating across different items will be used to achieve a psychometrically valid summed score serving as the outcome measuring impact on clinical practice for our trial. Further details on how each of these analyses will be conducted are presented within the Data Analysis section.

Knowledge evaluation will occur at the end of weeks two and four. These assessments are also automatically recorded within the platform.


####  Sample size

Given that our study involve subgroup analyses for each of the professional groups (nursing practitioners, students and residents, family physicians and orthopedic residents), our sample size is calculated for each group and then multiplied by three. Given the absence of preliminary efficacy data, we calculated our sample size based on an assumption of a two-sample t-test for an index representing the worst case scenario for each of the three outcomes, with an effect size of 55%, a significance level and statistical power set at the traditional levels of 0.05 and 80%, respectively. Under these assumptions the estimated required sample size is of 52.9 per group, which we have rounded to 53, ultimately leading to a total sample size of 106 participants in total for each subgroup. When we take into account all three subgroups (nursing practitioners, students and residents, famility physicians and orthopedic residents), our final sample size for the study comes to 318 (106 times 3). Taking into account a worst case scenario dropout rate of approximately 20%, we therefore plan to enroll 380 participants.


####  Interim analyses and stopping guidelines

Given the relatively short duration of our trial, we do not intend to perform an interim analyses. In addition, given the low risk associated with the intervention, our guidelines will only recommend that the trial be stopped in case of an unlikely loss of confidentiality that might compromise participants privacy.

####  Randomization: sequence generation

All randomization schedules will be delivered through [Planout](http://facebook.github.io/planout/) as outlined under Aim 1. Briefly, Planout makes use of a pseudorandom number generator from the [Python language](https://www.python.org/), which has been extensively tested and therefore should be adequate for the purposes of this trial. <!-- need ref --> Randomization will be blocked at 10 participants, thus decreasing the likelihood of a possible imbalance. Finally, randomization will be stratified by each one of the subgroups (family physicians, nursing practitioners, students and residents and orthopedic residents), thus also decreasing the likelihood of an imbalance among them. 

All randomization will be delivered through the Open edX platform, thus ensuring that participants and investigators are blind to the allocation. Data analysts (RP, JRV) will receive a dataset from one the computer scientists (SI, JF) where the two randomization arms are designated by unspecific letters, thus ensuring that the analysis is also conducted in a blind fashion.


#### Statistical methods 

All analyses will be conducted by the members in our team with experience and graduate degrees related to Data Science (RP, JRV). The data analysis will start with an overall evaluation of individual variables to assess distributions for continuous variables (e.g., participant's age) in terms of their distributions, as well as the frequency/percentage for categorical variables (e.g., gender). 

Missing values will be handled differently if they happen to individual variables or full encounters, e.g., an entire evaluation for a week. Individual variables will be imputed starting by an exploratory visual analysis to better understand the potential underlying pattern behind missing values for each variable. This analysis will be conducted using the [VIM package](http://cran.r-project.org/web/packages/VIMGUI/vignettes/VIM-Imputation.pdf) within the [R language](http://www.r-project.org/). Depending on the pattern of missing data, we might then choose one of several alternatives, ranging from not imputing when the percent missing might be negligible, imputing using predictive models from variables that are hypothesized to be associated with the missing values (e.g., age predicting residency year), or multiple imputation in cases where missing patterns might be happening at random (MAR or missing at random) (@rubin1976inference).

We will evaluate for potential confounding of the intervention effect by assessing balance across baseline variables between the 3D and control arms. This evaluation will occur for the overall study as well as within individual subgroups of family medicine practitioners as well as orthopedic residents and nursing practitioners, students and residents. While imbalances are unlikely given that we are using a series of preventive measures (blinding, concealed allocation, blocking and stratification), eventual imbalances will be evaluated on an individual basis and might require adjusting in our modeling strategy (see below for details).

The psychometric analysis for parallel validation of our scales will start with an Exploratory Factor Analysis to evaluate the underlying dimensional structure of our item pool. We will then conduct a Confirmatory Factor Analysis using the hypothesized domains (see Outcome Variable section for extensive details). Once domains are established we will use Cronbach's alpha to measure internal reliability within each construct. Validity will be measured by triangulation across different domains. For example, it is believed that if a professional is able to understand the biomechanics of a given fracture, then the construct for therapeutic planning should be highly associated with that previous construct.

Given that all of our outcomes have multiple endpoints over time, we will use a combination of mixed models and survival analysis to measure the efficacy associated with the 3D in comparison with the control arm. To formally test trends in each of our outcome variables over time (knowledge, User eXperience and impact on clinical practice) we will  develop mixed models that account for multiple measures as random a effect. For each time period we will also assess differences in scores, comparing the three subgroups. These bivariate analyses will incorporate robust standard errors to account for the clustering effect. Survival models will include Cox Proportional Hazards models measuring time until an information reached clinical practice. The hazards assumption will be tested prior to analyses and eventual ties will be resolved. 


## Results


## Discussion