# Predicting Bank Telemarketing Outcomes

## Introduction

### Background and Motivation

In the wake of COVID-19, EU banks have experienced a notable surge in deposits from June 2017 to June 2021. This period highlighted the potential for significant financial growth and stability through strategic marketing and customer engagement practices. Traditional telemarketing methods, however, have not kept pace with the evolving landscape, often resulting in inefficient and ineffective client acquisition efforts.

![EU Deposit Trends](media/image1)

*Fig 1. EU deposit trend by geography*

Our project aims to harness machine learning techniques to predict customer responses to telemarketing campaigns for term deposits, facilitating a more targeted, efficient, and personalized approach to bank marketing.

### Business Problem

The core challenge for Portuguese banks lies in modernizing their telemarketing strategies to effectively compete within the EU banking sector. Our objective is to develop a machine learning model capable of generating predictive insights to:
- Enhance the success rate of term deposit promotions.
- Optimize marketing resources by focusing on clients most likely to subscribe.
- Personalize client interactions to improve engagement and conversion rates.

---

## Data Understanding and Preparation

![](2.png)
The dataset comprises 41,188 client records from Portuguese banking telemarketing campaigns, featuring 20 input attributes and a binary target variable indicating the outcome (subscription to a term deposit).

### Data Exploration Insights

Our analysis revealed several key insights:
- The dataset exhibits an imbalance, with a predominance of 'no' responses.
- Optimal telemarketing periods are identified as April to August, aligning with the timing of Portuguese bonuses.

### Preparation

Data preparation involved cleaning, duplicate removal, and encoding of categorical variables, setting the stage for model development and evaluation.

---

## Model Design and Results

We explored a variety of classification models to predict potential term deposit subscriptions:

### Logistic Regression (LR)

Provided a foundational benchmark with an accuracy of 85%, highlighting key predictive features such as euribor rates and employment status.

### Decision Trees (DT)

Offered intuitive insights into decision-making processes, underscoring the importance of call duration.

### Random Forest (RF)

Emerged as the most effective model, achieving an 88.2% accuracy, and providing a robust mechanism for identifying potential subscribers.

### Support Vector Machine (SVM), Multi-layer Perceptron (MLP), and Voting Classifier

These models further diversified our analytical approach, each contributing unique perspectives on the data and prediction outcomes.

---

## Discussion and Concluding Remarks

Our project underscores the transformative potential of machine learning in refining bank telemarketing strategies. By identifying key variables influencing term deposit subscription likelihood, such as call duration and economic indicators, banks can significantly enhance their marketing effectiveness.

### Implications for Practice

The findings advocate for a more data-driven, analytical approach to customer engagement, promoting efficiency and personalization in marketing efforts.

### Future Directions

The evolving nature of the financial landscape, coupled with technological advancements, presents ongoing opportunities for innovation in customer relationship management and marketing strategy development.

---

