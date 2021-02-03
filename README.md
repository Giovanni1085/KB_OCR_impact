# Is your OCR good enough?

This repository contains code developed as part of the KB residency project: "Is your OCR good enough? A comprehensive assessment of the impact of OCR quality on downstream tasks." Refer to [this blog post](https://lab.kb.nl/about-us/blog/your-ocr-good-enough-comprehensive-assessment-impact-ocr-quality-downstream-tasks) for more info on the project.

## Goals of the project

Is an average OCR quality of 70% enough for my study? What OCR quality should we ask from external suppliers? Should we re-do the OCR of our collections to bring it from 80% to 85%? Libraries and researchers alike face the same dilemma in our times of textual abundance: when is OCR quality good enough? User access, scientific results and the investment of limited resources increasingly depend on answering this question.

This project focuses on a comprehensive assessment of the impact of OCR quality in Dutch newspaper, journal and book collections, comparing it with published results for English and French. This is be done via *extrinsic evaluation*: assessing results from a set of representative downstream tasks, such as text classification or clustering. The ultimate goal of the project is to contribute guidelines detailing when OCR quality is to be considered good enough, in order to inform the development and use of textual collections.

The project's proposal can be found [here](https://github.com/Giovanni1085/KB_OCR_impact/blob/master/documentation/application_form_rir_call_2020_colavizza_submitted.pdf).

## Contents

### Datasets

The datasets we use are documented in the repository's wiki. See [here](https://github.com/Giovanni1085/KB_OCR_impact/wiki/Datasets) for details on the datasets, and [here](https://github.com/Giovanni1085/KB_OCR_impact/wiki/Evaluations) for the assessment of their OCR quality.

* The [Data frames - setup](https://github.com/Giovanni1085/KB_OCR_impact/blob/master/Data%20frames%20-%20setup.ipynb) notebook contains code to exemplify how we pre-processed KB data in order to then use it for the project.
* The [Data frames - Evaluation](https://github.com/Giovanni1085/KB_OCR_impact/blob/master/Data%20frames%20-%20evaluation.ipynb) notebook contains code to show the outcomes of the assessment of the OCR quality of these datasets which we conducted as part of the project. See [here](https://github.com/Giovanni1085/KB_OCR_impact/wiki/Evaluations) for more details. 
* The folder [data frames evaluation](data_frames_evaluation/) contains the final datasets which we used for our experiments.

### Tasks

This repository contains results for two tasks:
* [Topic modelling](https://github.com/Giovanni1085/KB_OCR_impact/blob/master/%5BANALYSIS%5D%20Topic%20modelling.ipynb)
* [Document classification](https://github.com/Giovanni1085/KB_OCR_impact/blob/master/%5BANALYSIS%5D%20Classification.ipynb)

## How to run

You can use the `requirements.txt` file to create a `pip` or `conda` environment. The easiest way to replicate results is to use the datasets in the [data_frames_evaluation](data_frames_evaluation/) folder.

For any question, or for reporting a bug/improvement, please open an issue or do a pull request. You can contact me at g.colavizza@uva.nl.
