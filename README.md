# Team Project

## Description

The team project consists of two modules. Each module requires participants to apply the skills they have learned to date, and explore a dataset of their choosing. The first part of the team project involves creating a simple program with a database in order to analyze a dataset from an open source, such as Kaggle. In the second part of the team project, teams will come together again and apply the skills developed in each of the data science or machine learning foundations certificate streams. Teams will either create a data visualization or a machine learning model.

Participants will work in assigned teams of 4-5.

#### Project Descriptions

- [First Team Project Description](./team_project_1.md)
- [Second Team Project Description](./team_project_2.md)

## Learning Outcomes

By the end of Team Project Module 1, participants will be able to:

- Resolve merge conflicts
- Describe common problems or challenges a team encounters when working collaboratively using Git and GitHub
- Create a program to analyze a dataset with contributions from multiple team members

By the end of Team Project Module 2, participants will be able to:

- Create a data visualization as a team
- Create a machine learning model as a team

### Contacts

**Questions can be submitted to the _#cohort-3-help_ channel on Slack**

- Technical Facilitator:

  - **Phil Van-Lane**(he/him)
    phil.vanlane@mail.utoronto.ca

- Learning Support Staff:
  - **Taneea Agrawaal** (she/her)
    taneea@cs.toronto.edu
  - **Farzaneh Hashemi** (she/her )
    fhashemi.ma@gmail.com
  - **Tong Su** (she/her)
    tong.su@mail.utoronto.ca

### Delivery of Team Project Modules

Each Team Project module will include two live learning sessions and one case study presentation. During live learning sessions, facilitators will introduce the project, walk through relevant examples, and introduce various team skills that support project success. The remaining time will be used for teams to assemble and work on their projects, as well as get help from the facilitator or the learning support to troubleshoot any issues a team may be encountering.

Work periods will also be used as opportunities for teams to collaborate and work together, while accessing learning support.

### Schedule

| Day 1                 | Day 2                 | Day 3      | Day 4       | Day 5       |
| --------------------- | --------------------- | ---------- | ----------- | ----------- |
| Live Learning Session | Live Learning Session | Case Study | Work Period | Work Period |

## Requirements

- Participants are expected to attend live learning sessions and the case study as part of the learning experience. Participants are encouraged to use the scheduled work period time to complete their projects.
- Participants are encouraged to ask questions and collaborate with others to enhance learning.
- Participants must have a computer and an internet connection to participate in online activities.
- Participants must not use generative AI such as ChatGPT to generate code to complete assignments. It should be used as a supportive tool to seek out answers to questions you may have.
- We expect participants to have completed the [onboarding repo](https://github.com/UofT-DSI/onboarding/tree/main/onboarding_documents).
- We encourage participants to default to having their camera on at all times, and turning the camera off only as needed. This will greatly enhance the learning experience for all participants and provides real-time feedback for the instructional team.

### How to get help

![image](/steps-to-ask-for-help.png)

## Folder Structure

### Project 1

```markdown
|-- data
|---- processed
|---- raw
|---- sql
|-- reports
|-- src
|-- README.md
|-- .gitignore
```

### Project 2

```markdown
|-- data
|---- processed
|---- raw
|---- sql
|-- experiments
|-- models
|-- reports
|-- src
|-- README.md
|-- .gitignore
```

dev_Katya
- **Data:** Contains the raw, processed and final data. For any data living in a database, make sure to export the tables out into the `sql` folder, so it can be used by anyone else.
- **Experiments:** A folder for experiments
- **Models:** A folder containing trained models or model predictions
- **Reports:** Generated HTML, PDF etc. of your report
- **src:** Project source code
- README: This file!
- .gitignore: Files to exclude from this folder, specified by the Technical Facilitator

* **Data:** Contains the raw, processed and final data. For any data living in a database, make sure to export the tables out into the `sql` folder, so it can be used by anyone else.
* **Experiments:** A folder for experiments
* **Models:** A folder containing trained models or model predictions
* **Reports:** Generated HTML, PDF etc. of your report
* **src:** Project source code
* README: This file!
* .gitignore: Files to exclude from this folder, specified by the Technical Facilitator


### Team Project Week 1 Video Links

- Jes: https://www.youtube.com/watch?v=jW25EXwkkh8
- Katya: https://drive.google.com/file/d/1Mf_1ckG_bjio2REA2NCYTYtKZy-3ahVA/view?usp=sharing
- Zoey: https://drive.google.com/file/d/1mFkRBGdUwbk8QBUrvyQ2JPL7VIjgmc-M/view?usp=drive_link
- Lynn: https://drive.google.com/file/d/190gJv4thgMIOYNTUbpBMdbryMI_hBkTv/view?usp=drive_link


Team Project Week 1 Video Links
Jes: https://www.youtube.com/watch?v=jW25EXwkkh8

#### Approach
Experiment with different machine learning models on the sales transaction data to identify customer segmentations and sales by each segment.

### Rules of Engagement
Making decisions as a group on next steps in the evening working sessions
Documenting our thought process and required tasks for task assignment
Notifying team members if you have difficulties with a task or meeting deadlines through Slack
Daily touch points to discuss progress and adjust plans as needed to stay on schedule

## Team Project Week 2 Video Links

- Lynn: https://drive.google.com/file/d/1b2OYET_xIkvFSSFwHkNXgD5dbmj0dpPG/view?usp=sharing

## Team Project Week 2 - Machine Learning Model Guiding Questions

- Lynn: 

1. Objectives and Success Criteria:
The primary objective is to predict sales based on customer demographics.Success is measured by minimizing prediction errors (e.g., mean squared error) and accurately categorizing customers into segments that drive the most sales.

2. Feature Selection:
Selected features are city, age, and income because they provide essential insights into customer demographics and purchasing power. 

3. Handling Missing Values and Outliers:
Ensured all missing values were handled through imputation techniques, and outliers were identified and either transformed or removed. Proper data cleaning ensured that the model could learn effectively without biases.

4. Algorithm:
Using a neural network model because of its ability to capture complex relationships between input and target variables. 

5. Hyperparameter Tuning:
Hyperparameter tuning method are used like Grid Search and by adjusting learning rates, batch sizes, and layer configurations. Cross-validation was also used to ensure that the model generalized well.

4. Data Splitting:
The dataset was split into training, validation, and test sets, with 20% of the data reserved for testing. This split ensures that the model’s performance is evaluated on unseen data and helps prevent overfitting.

5. Ethical Considerations:
Considered the potential biases, especially those related to demographic features like income and city to ensure that the model does not unfairly favor or disadvantage specific groups.

6. Documentation:
The machine learning pipeline from data preprocessing to model tuning was documented in the model doc, including the rationale behind feature selection, the steps taken for data cleaning, and the architecture of the neural network.