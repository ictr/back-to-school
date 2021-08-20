
# Mask or no mask: a decision for teachers, parents, and students

* August, 2021
* Institute for Clinical & Translational Research, Baylor College of Medicine


[**REPORT**]()

With the increasing incidences of [COVID-19 infections in the Greater Houston Area](https://www.tmc.edu/coronavirus-updates/daily-new-covid-19-positive-cases-for-the-greater-houston-area/) and all students are coming back to school, there has been an increasing debate on whether or not teacher and students should wear masks all the time.

As of today (August 20),
1. Gov. Abbott issued an executive order [Prohibiting Government Entities From Mandating Masks](https://gov.texas.gov/news/post/governor-abbott-issues-executive-order-prohibiting-government-entities-from-mandating-masks)
2. [Houston ISD](https://www.houstonisd.org/) is one of [a handful of schools in the Houston area](https://www.khou.com/article/news/health/coronavirus/masks-houston-school-districts-covid-coronavirus/285-25154fcd-97ae-4d8b-9444-be77a0b58f89) with a mask mandate
3. Colleges in the surrounding areas have different policies. Notably, the Rice University have [COVID policies that mandate mask wearing indoors](https://coronavirus.rice.edu/policies). However, during an intense oritentation week, there are already COVID-19 cases in one of its colleges, and all students are being tested.

We ran a small simulation using our [COVID-19 Outbreak Simulator](https://ictr.github.io/covid19-outbreak-simulator/) and try to compare number of COVID-cases for schools that mandate or does not mandate mask wearing.

# How to reproduce this simulation

1. Install [COVID-19 Outbreak Simulator]()
2. Install jupyterlab, and jupyterlab-sos, which will install the SoS Polyglot Notebook and SoS Workflow Engine.
3. After finishing the report, use command

  ```
  sos convert back_to_school.ipynb index.html --template sos-report-only
  ```
  to generate the report