
# Mask or no mask: a decision for teachers, parents, and students

* August, 2021
* Institute for Clinical & Translational Research, Baylor College of Medicine


[**REPORT**](https://ictr.github.io/back-to-school/)

With  increasing incidences of [COVID-19 infections in the Greater Houston Area](https://www.tmc.edu/coronavirus-updates/daily-new-covid-19-positive-cases-for-the-greater-houston-area/) and  students returning to school, informed decisions must be made regarding teacher and student continuous masking recommendations.

As of today (August 21),
1. An executive order is in place which [prohibits Texas government funded entities from mandating mask wearing on premises](https://gov.texas.gov/news/post/governor-abbott-issues-executive-order-prohibiting-government-entities-from-mandating-masks).
2. [Houston ISD](https://www.houstonisd.org/) is one of [a handful of schools in the Houston area](https://www.khou.com/article/news/health/coronavirus/masks-houston-school-districts-covid-coronavirus/285-25154fcd-97ae-4d8b-9444-be77a0b58f89) which does have a mask wearing mandate in place.
3. Colleges in the our area have established differing policies. Notably, Rice University has [COVID policies that mandate mask wearing indoors](https://coronavirus.rice.edu/policies). 

To provide quantitative insight into these mixed stances, we ran a targeted simulation using our [COVID-19 Outbreak Simulator](https://ictr.github.io/covid19-outbreak-simulator/) to compare the number of COVID-cases that develop in schools that mandate or do not mandate mask wearing.

# How to reproduce this simulation

1. Install [COVID-19 Outbreak Simulator](https://github.com/ictr/covid19-outbreak-simulator)
2. Install [jupyterlab](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html), and [jupyterlab-sos](https://github.com/vatlab/jupyterlab-sos), which will install the [SoS Polyglot Notebook and SoS Workflow Engine](https://vatlab.github.io/sos-docs/).
3. Start a jupyter lab server and open the `back-to-school.ipynb` notebook.
4. After finishing the report, use command

  ```
  sos convert back_to_school.ipynb index.html --template sos-report-only
  ```
  to generate the report