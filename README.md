  # Predicting myopia in a population 👓

In this analysis we will use a set obtained in a study of a population of children that in which their habits have been followed looking for the characteristics that can predict the appearance of myopia. The different predictive classification models will be studied for the best performance.

  The dataset is a subset of data from the Orinda Longitudinal Study of `Myopia` (OLSM), a cohort study of ocular component development and risk factors for the onset of myopia in children. Data collection began in the 1989–1990 school year and continued annually through the 2000–2001 school year. All data about the parts that make up the eye (the ocular components) were collected during an examination during the school day. Data on family history and visual activities were collected yearly in a survey completed by a parent or guardian. The dataset used in this text is from 618 of the subjects who had at least five years of follow-up and were not myopic when they entered the study. All data are from their initial exam and the dataset includes 17 variables. In addition to the ocular data there is information on age at entry, year of entry, family history of myopia and hours of various visual activities. The ocular data come from a subject’s right eye.

  The dataset `myopia.csv` is collected from https://rdrr.io/github/emilelatour/purposeful/man/myopia.html:  

  A data frame with 618 observations and 18 variables:

  * id: Study ID
  * studyyear: Year subject entered the study
  * myopic: Myopia within the first five years of follow up (No/Yes)
  * age: Age at first visit (years)
  * gender: Gender (Male/Female)
  * spheq: Spherical Equivalent Refraction (diopter)
  * al: Axial Length (mm)
  * acd: Anterior Chamber Depth (mm)
  * lt: Lens Thickness (mm)
  * vcd: Vitreous Chamber Depth (mm)
  * sporthr: Time spent engaging in sports/outdoor activities (hours per week)
  * readhr:Time spent reading for pleasure (hours per week)
  * comphr:Time spent playing video/computer games or working on the computer (hours per week)
  * studyhr:Time spent reading or studying for school assignments (hours per week)
  * tvhr: Time spent watching television (hours per week)
  * diopterhr: Composite of near-work activities (hours per week)
  * mommy: Was the subject’s mother myopic? (No/Yes)
  * dadmy: Was the subject’s father myopic? (No/Yes)
