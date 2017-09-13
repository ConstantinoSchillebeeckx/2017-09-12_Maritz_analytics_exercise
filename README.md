2017-09-12_Maritz_analytics_exercise
==============================

Maritz analytics exercise used for the interview process for the Senior Analytics position. 

Original instructions:

> The federal government maintains a publicly available database of consumer complaints for financial services. The data is available here:
http://catalog.data.gov/dataset/consumer-complaint-database

> Act as if your client is the Consumer Financial Protection Bureau. Create a persuasive presentation that convinces the CFPB to take an action. Don’t just tell what happened, tell them what they should do about it. It could be where to market services, what types of companies to sanction, what types of people to compensate, what state law should be changed, etc.  Be creative and explain your recommendation using data-backed insights and evidence. 

> Requirements and Details:

> -   You will have the floor for 20 minutes during your interview to present your findings.
> -   Make at least one strategic recommendation and back up your position using evidence from the dataset.
> -   The presentation must contain a forecast for the number of complaints over the next 12 months. You may use whatever data and methodology you see fit.
> -   You may use any program or application to complete the analysis. You may also use any additional data you see as relevant. Be prepared to send any files and/or code used.
> -   Note that Maritz does not allow USB flash drives for security reasons, so either email your work ahead of time or have it accessible on the web.


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make clean`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── interim        <- Data generated during the data analysis process, e.g. stats file.
    │   ├── final          <- Final data results which designate what was learned from teh analysis.
    │   ├── pcoa           <- Generated PCOA plots.
    │   ├── phylo          <- Generated phylogenetic trees.
    │   └── raw            <- The original, immutable data dump including OTU table and mapping file.
    │
    ├── docs               <- MkDocs
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │   |                     a short `-` delimited description, and initials (if needed) e.g.
    │   |                     `1.0-jqp-initial-data-exploration-CS`.
    │   ├── explore        <- Initial exploratory work
    │   └── reports        <- Polished work that can be exported as html to the reports directory
    │       |
    │       └── figures    <- Any figure referenced in a reports notebook should use this dir as
    │                         the reference src directory; this acts as a symlink to the main
    │                         reports/figures/ directory.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── setup          <- Scripts generically used at time of project setup
    │   │   └── setup_git_repo.sh
    │   │
    │   └── viz            <- Scripts to create exploratory and results oriented visualizations
    │
    └── test_environment.py
