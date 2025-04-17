# Characterising Topic Familiarity and Query Specificity Using Eye-Tracking Data
Eye-tracking data has been shown to correlate with a user's knowledge level and query formulation behaviour. While previous work has focused primarily on eye gaze fixations for attention analysis, often requiring additional contextual information, our study investigates the memory-related cognitive dimension by relying solely on pupil dilation and gaze velocity to infer users' topic familiarity and query specificity without needing any contextual information. Using eye-tracking data collected via a lab user study ($N=18$), we achieved a Macro F1 score of 71.25% for predicting topic familiarity with a Gradient Boosting classifier, and a Macro F1 score of 60.54% with a k-nearest neighbours (KNN) classifier for query specificity. Furthermore, we developed a novel annotation guideline -- specifically tailored for question answering -- to manually classify queries as Specific or Non-specific. This study demonstrates the feasibility of eye-tracking to better understand topic familiarity and query specificity in search.

## Description 

**query-spec-combined-sorted.csv** contains the annotation of the queries along with annotations from three annotators. The following describes the properties shown in the file:  

- **PID**: A numeric ID associated with users in the experiment.  
- **query**: User-formed queries.  
- **topic**: A numeric label associated with the topic and backstory given to the user during the experiment before forming the query.  
- **Specificity_{id}**: Query specificity classification given by an annotator.  
  - `1` = Non-specific  
  - `2` = Specific  
- **Specificity Level**: Combined query specificity based on the majority of annotators' specificity ratings.  

Additionally, the annotators' responses to each question are included to show their thought process during the annotation.  

```
@inproceedings{He2025peanut,
author = {Jiaman, He and Leng, Zikang and Dana, McKay and Johanne, R, Trippas and Damiano, Spina},
title = {Characterising Topic Familiarity and Query Specificity Using Eye-Tracking Data},
year = {2025},
doi = {10.1145/3726302.3730174},
booktitle = {Proceedings of the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR '25), July 13--18, 2025, Padua, Italy},
series = {SIGIR '25}
}
```
