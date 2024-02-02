# Long-COVID
Understanding Predictive Factors of Long-COVID

## Background
Long-COVID is a chronic, multisymptom condition that develops after one or more COVID-19 infections. The diagnostic definition is 12+ weeks since initial infection, one or more new persistent symptoms, and a report of affect on daily functioning. Primary complaints include physical fatigue and brain fog, along with sleep dysfunction and mental health symptoms.
## Methods
In this analysis, various aspects of long-COVID are explored in a sample of 793 people. First, a binary classification model (long-COVID vs. healthy) was trained and tested to identify biopsychosocial features of a long-COVID diagnosis. The input features include the following domains: various types of stress, social support, mental health symptoms, cogntive complaints, physical complaints, health history, pain, and demographics. Second, another binary classification model (long-COVID vs. healthy) was trained and tested with a demographic-matched sampled of Veterans and civilians. The goal here was to see if Veteran status affected features of a long-COVID diagnosis. Third, a model was built to look at cognitive features of long-COVID in an attempt to quantify brain fog. Brain fog was operationalized as a numerical variable by using the global score from the PROMIS Cognitive Complaints measure. Linear regression models were trained and tested with input features consisting of cognitive performance metrics (spatial reasoning, executive function, sustainted attention etc.) while controlling for long-COVID diagnosis status (binary).

## The results reveal that...

## Programming Language
* R: Data Exploration and Cleaning
* Python: Data Partition, Transformation Pipeline, Modeling, Model Evaluation
