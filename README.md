# Person-Course-Prediction

### Goal:
Analyze student data to try to predict whether a student received a certification (completed) a course.

### Description
This dataset is at the level of one row per-person, per-course.
The dataset includes both administrative variables and variables generated from user-provided data. 
For a detailed description of the variables included in the de-identified dataset, please see the data dictionary excel file.

See Kaggle site for more dataset info: https://www.kaggle.com/c/csestat-416-21su-kaggle/overview

For more information about the existing analyses of these data and the courses, please see the HarvardX and MITx working paper “HarvardX and MITx: The first year of open online courses”: 
(http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2381263)


### Data Dictionary
- certified : our target variable
- registered " # 0/1; registered for course
- viewed : # 0/1; anyone who accessed the ‘Courseware’ tab
- explored : # 0/1; anyone who accessed at least half of the chapters in the courseware
- LoE_DI :  # highest level of education completed
- YoB : # year of birth
- gende : # Possible values: m (male), f (female) and o (other)
- grade : #  final grade in the course, ranges from 0 to 1
- start_time_DI : # date of course registration
- last_event_DI : # date of last interaction with course
- nevents : # number of interactions with the course
- ndays_act : # number of unique days student interacted with course
- nplay_video : # number of play video events within the course
- nchapters : # number of chapters (within the Courseware) with which the student interacted.
- nforum_posts : # number of posts to the Discussion Forum

