# SSMA
This repository will soon contain content for the summer school in (model-based) multivariate analysis.

See https://bertv.folk.ntnu.no/index.html for more details.

## PROGRAM
**This is a preliminary program and thus subject to change**.

The days last from 09:00 to 17:00(ish), and a session after dinner. Each day will consist of a mix of lectures, in-class discussion, live demonstration, and interactive exercises / case studies.

## Monday (Background day)
* Welcome, logistics, and overview
* Some background of multivariate methods in ecology
* Generalised Linear Models and multispecies extensions
* Introduction to the gllvm R-package

## Tuesday (JSDMs day)
* Multispecies mixed effects Models
* Background of Joint Species Distribution Models
* Accommodating spatial or temporal autocorrelation
* Phylogenetic mixed models

## Wednesday (Ordination day)
* Background to ordination
* Accommodating nested study designs
* Bringing covariates into the ordination
* Unimodal/quadratic ordination 

## Thursday (Workflow/presentation day)
* GLLVMs from A-Z: application, results, inference
* Participant presentations (more details TBA, but will operate on a first-come basis) 
* Excursion
* (Re)analysing article Part I

## Friday ("What else is out there?" day)
* Concepts in model-based clustering
* Other packages for (model-based) multivariate analysis
* (Re)analysing article Part II & General Discussion
* Analysis of own data

# Detailed schedule
|   Day   |Time         |Subject                                                         |Lecturer|
|---------|-------------|:---------------------------------------------------------------|:-------|
|Monday   |<sub>09:00 - 09:30</sub>| Welcome, introduction, getting started              |Bert    |
|         |<sub>09:30 - 10:15</sub>| Recap of basic statistical concepts                 |        |
|         |<sub>10:15 - 10:45</sub>| ☕ Break                                             |        |
|         |<sub>10:45 - 11:45</sub>| Practical 1: Sampling variation and simulation      |        |
|         |<sub>11:45 - 12:30</sub>| Basics of Generalised Linear Models (GLMs)          |        | <!-- distributions and such-->
|         |<sub>12:30 - 13:30</sub>| 🍽 Lunch                                            |        |
|         |<sub>13:30 - 14:15</sub>| Practical 2: Fitting GLMs                           |        |
|         |<sub>14:15 - 15:00</sub>| Finding a good multispecies GLM                     |        |<!-- what it means to have multiple species -->
|         |<sub>15:00 - 15:30</sub>| ☕ Break                                             |        |
|         |<sub>15:30 - 16:30</sub>| Practical 3: Comparing multispecies GLMs            |        | <!-- model selection, hypo testing ?-->
|         |<sub>16:30 - 17:15</sub>| Introduction to the gllvm R-package                 |Pekka   |
|         |             |          |                                                     |        |
|         |<sub>19:00 - 20:00</sub>| Brainstorming properties of community data          |Bert    |
|---------|-------------|----------------------------------------------------------------|--------|
|Tuesday  |<sub>09:00 - 09:45</sub>| Multispecies mixed effects models                   |Jenni   |
|         |<sub>09:45 - 10:45</sub>| Practical 4: Fitting multispecies models            |        |
|         |<sub>10:45 - 11:15</sub>| ☕ Break                                             |        |
|         |<sub>11:15 - 12:00</sub>| Joint Species Distribution Models (JSDMs)           |Jenni/Pekka|
|         |<sub>12:00 - 13:00</sub>| 🍽 Lunch                                            |        |
|         |<sub>13:00 - 14:00</sub>| Practical 5: Fitting JSDMs                          |        |
|         |<sub>14:00 - 14:45</sub>| Accommodating spatial or temporal autocorrelation   |Francis/Pekka|
|         |<sub>14:45 - 15:15</sub>| ☕ Break                                             |        |
|         |<sub>15:15 - 16:15</sub>| Practical 6: Spatial or temporal JSDMs              |Pekka   |
|         |<sub>16:15 - 17:00</sub>| Hierarchical environmental responses                |Bert/Jenni|
|         |             |          |                                                     |        |
|         |<sub>19:00 - 20:00</sub>| Practical 7: Traits and the phylogenetic model      |Bert    |
|---------|-------------|----------------------------------------------------------------|--------|
|Wednesday|<sub>09:00 - 09:45</sub>| Model-based ordination                              |Bert    |
|         |<sub>09:45 - 10:45</sub>| Practical 8: Model-based unconstrained              |        |
|         |<sub>10:45 - 11:15</sub>| ☕ Break                                             |        |
|         |<sub>11:15 - 12:00</sub>| Bringing covariates into the ordination             |        |
|         |<sub>12:00 - 13:00</sub>| 🍽 Lunch                                            |        |
|         |<sub>13:00 - 14:00</sub>| Practical 9: Ordination with predictors             |        |
|         |<sub>14:00 - 14:45</sub>| Conditioning and nested designs                     |        |
|         |<sub>14:45 - 15:15</sub>| ☕ Break                                             |        |
|         |<sub>15:15 - 16:15</sub>| Practical 10: Partial ordination                    |        | <!-- bringing together 3 formula interfaces, and the ideas of partial, residual ordination, and accommodating nested designs -->
|         |<sub>16:15 - 17:00</sub>| Unimodal responses                                  |        |
|         |             |          |                                                     |        |
|         |<sub>19:00 - 20:00</sub>| Practical 11: Unimodal responses                    |        |
|---------|-------------|----------------------------------------------------------------|--------|
|Thursday |<sub>09:00 - 09:45</sub>| GLLVMs from A-Z                                     |Audun   |
|         |<sub>09:45 - 12:30</sub>| 🎤 Participant presentations                        |        |
|         |<sub>12:30 - 13:15</sub>| 🍽 Lunch                                            |        |
|         |<sub>13:15 - 17:00</sub>| 🚶 Excursion                                        |        |
|         |             |          |                                                     |        |
|         |<sub>19:00 - 20:00</sub>| (Re)analysing article Part I                        |Bert/Audun|
|---------|-------------|----------------------------------------------------------------|--------|
|Friday   |<sub>08:45 - 09:00</sub>| Wrap-up                                             |Bert    |
|         |<sub>09:00 - 09:45</sub>| [Concepts in model-based clustering](https://github.com/BertvanderVeen/SSMA/blob/main/Friday/modelbasedclustering.pdf)                  |Francis |
|         |<sub>09:45 - 10:30</sub>| Other packages for (model-based) multivariate analysis|Bert  |
|         |<sub>10:30 - 11:30</sub>| Practical 12: Comparing ordinations                 |        |
|         |<sub>11:30 - 12:30</sub>| 🍽 Early lunch                                      |        |
|         |<sub>12:30 - 14:00</sub>| (Re)analysing article Part II / Discussion          |        |
|         |<sub>14:00 - 16:00</sub>| Analysis of own data                                |        |



<!-- auxiliary topics 
a) How to choose an ordination
b) Cross-validation and prediction
c) Similarity of JSDMs, ordination, and what we can learn from each other
d) Random canonical coefficients

-->
