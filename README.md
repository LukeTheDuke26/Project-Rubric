# Project-Rubric
Stack Overflow Survey Insights


# Data Science Project: Comprehensive Analysis of Stack Overflow 2017 Developer Survey

This project presents a detailed analysis of the StackOverflow's 2017 Developer Survey data, aiming to delve into various aspects of developers' life, preferences, and their engagement with the StackOverflow community.

---

## Motivation

My journey towards becoming a Data Scientist drove me to take on this project. Currently enrolled in the Data Scientist track at Udacity, I am grateful to be supported by my company throughout this endeavor. I am fascinated by data science, an incredibly compelling field that I believe will significantly shape the future of work and our lives. Thrilled to have embarked on this journey, I eagerly anticipate the challenges and opportunities for learning it will bring. This project stands as a testament to my passion and the first of many milestones in my data science journey.

---

## Project Structure

The project consists of two main parts:

1. **Project Rubric: Analysis of the Stack Overflow 2017 Developer Survey**
    - Jupyter Notebook: `Project Rubric - Part 1.ipynb`

2. **Enhancing the Model: Diving Deeper into the Developers' Realm**
    - Jupyter Notebook: `Project Rubric - Part 2.ipynb`

---

## Data 

The dataset used in this project is the Stack Overflow Developer Survey data from 2017. 
- Dataset file: `survey_results_public.csv`

---

## Installation & Usage

Before running the notebook, ensure that you have the following packages installed:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these packages using pip:

```
pip install numpy pandas matplotlib seaborn scikit-learn
```

To run the notebook, use the following command in your terminal:

```
jupyter lab
```

Then, navigate to the project directory and open the desired notebook:
- For part 1, open `Project Rubric - Part 1.ipynb`.
- For part 2, open `Project Rubric - Part 2.ipynb`.

---

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---


Major Findings:

1.	In terms of education, most developers have a significant level of formal education, with a tilt towards computer-centric degrees. However, self-study and non-traditional learning methods also play a crucial role in skill acquisition.

2.	A large portion of developers program as a hobby or contribute to open-source projects, demonstrating the vibrant and resourceful nature of the developer community.

3.	SQL, JavaScript, Python, and C# emerged as the most popular programming languages among developers, while AngularJS, Node.js, and .NET Core are the preferred frameworks. In terms of platforms, Windows and Android lead the pack, with an emerging interest in Amazon Web Services.

4.	Developers largely work in private limited companies and publicly-traded corporations, with varying company sizes. Work start times are typically around 9 AM, and overall, there's a positive trend in job satisfaction. Remote work is prevalent, with a substantial number of developers working from home at least a few days each month.

5.	Factors such as Career Satisfaction, HoursPerWeek, and Salary significantly contribute to Job Satisfaction, but there is a significant proportion of the variation attributable to other factors not included in the model.

6.	A comprehensive linear regression model was developed to study job satisfaction, using predictors such as 'CompanySize', 'HoursPerWeek', 'HomeRemote', 'JobSecurity', 'Salary', 'CareerSatisfaction', and 'Gender'. The model, with an R-squared of around 0.40, could explain approximately 40% of the variation in job satisfaction. Despite its promising performance, the model leaves room for potential improvements, serving as a platform for further exploration in the field of job satisfaction research.

The insights gained from this study help us better understand the developer community, the paths to skill acquisition, and the preferred work environments and tools. We hope that these findings will provide valuable insights to individuals considering a career in development, educators designing curriculum, and organizations looking to attract and retain developer talent.



Acknowledgements
I would like to express my deep gratitude towards the following:

Stack Overflow, for providing the data from the 2017 Developer Survey that formed the basis of this project.
Udacity, for their excellent Data Scientist program that has guided my journey into data science.
My supportive company, which has greatly facilitated my studies by providing resources and time.
Any individuals, whose guidance and support has been invaluable.
And finally, my appreciation extends to all the developers of the Python libraries used in this project, including pandas, numpy, matplotlib, seaborn, and scikit-learn.
