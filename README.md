# Stack Overflow 2020 Survey Quick Analysis
## Project Description

This project analyzes the Data provided by [StackOverflow Annual Developer Survey](https://insights.stackoverflow.com/survey) and it's part of the [Udacity Data Science Nano Degree](https://www.udacity.com/course/data-scientist-nanodegree--nd025).

See the [Medium post](https://hanslemm.medium.com/the-best-languages-to-begin-your-dev-career-based-on-so-2020-survey-6716df14e6c1).

The main questions aimed to answer in this notebook are:

- What are the biggest dev communities in 2020 (according to SO 2020 Survey)?
- Which languages pay the biggest salaries and have more developers?
- What are the top 10 languages by income for those with 1 or less years of professional experience? How does the salary of these languages develop along with experience?

### Requirements

- Please check requirements.txt

## Getting started

Clone this repository

```shell
git clone https://github.com/hanslemm/Stack-Overflow-Survey-2020
```

Create a virtualenv

```shell
python3 -m venv ve
````

Activate the virtualenv

```shell
$ source venv/bin/activate
```

Install the requirements in your virtualenv:

```shell
pip install update pip
pip install -r requirements.txt
```

### Project tree

    .
    ├── .vscode
        ├── settings.json - Settings for VSCode
    ├── data - Repository with all information regarding Stack Overflow 2020 Survey
        ├── README_2020.txt - SO 2020 details
        ├── so_survey_2020.pdf - SO 2020 PDF
        ├── survey_results_public.csv - survey dataset
        └── survey_results_schema.csv - dataset descriptions
    ├── images
        ├── Community Size and Average Income per Language.png
        ├── Community Size per Language.png
        └── Top 10 Initial Income Languages and its Income Development.png
    ├── ve - Virtual Enviroment repo
    ├── data_analysis.ipynb - Jupyter Notebook with all the Data Analysis and code
    ├── README.md - This file
    └── requirements.txt - requirements for pip


## Acknowledgment

[Stack Overflow 2020 Developer Survey](https://insights.stackoverflow.com/survey)
[Udacity Data Science Nano Degree](https://www.udacity.com/course/data-scientist-nanodegree--nd025)

## Contact

My [LinkedIn Profile](linkedin.com/in/hcrlemm)