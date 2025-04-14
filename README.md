# Human Cognitive Performance Analysis

This is a notebook to visualize the **Human Cognitive Performance** dataset.

## About Dataset
Human Cognitive Performance Analysis: Lifestyle & AI Predictions
This dataset provides a comprehensive analysis of human cognitive performance based on various lifestyle factors, including sleep duration, stress levels, diet type, screen time, exercise frequency, and caffeine intake. Additionally, it includes a cognitive score computed using a weighted formula and an AI-predicted score, making it suitable for machine learning and AI-based predictive modeling.

The dataset contains 80,000 samples with diverse demographic attributes, making it an excellent resource for data science, AI, and human behavior analysis.

The Cognitive Score is calculated using a formula that considers multiple factors:

- Faster reaction time ⬆️ increases the score
- Higher memory test scores ⬆️ increase the score
- More sleep ⬆️ improves cognition
- Higher stress levels ⬇️ decrease the score
- More screen time ⬇️ reduces cognitive ability
- Regular exercise ⬆️ improves cognitive performance
- Higher caffeine intake ⬇️ negatively affects cognition

## File Information

This dataset contains structured information related to human cognitive performance and various lifestyle factors. The data is stored in a tabular format with the following columns:

| Column Name         | Data Type   | Description                                           |
|---------------------|-------------|-------------------------------------------------------|
| User_ID             | Categorical | Unique identifier for users                          |
| Age                 | Numerical   | Age of the user                                      |
| Gender              | Categorical | Male/Female/Other                                    |
| Sleep_Duration      | Numerical   | Sleep hours per night                                |
| Stress_Level        | Numerical   | Scale from 1 to 10                                   |
| Diet_Type           | Categorical | Vegetarian, Non-Vegetarian, Vegan                    |
| Daily_Screen_Time   | Numerical   | Hours spent on screens daily                         |
| Exercise_Frequency  | Categorical | Low, Medium, High                                    |
| Caffeine_Intake     | Numerical   | mg per day                                           |
| Reaction_Time       | Numerical   | Time in milliseconds (ms)                            |
| Memory_Test_Score   | Numerical   | Score out of 100                                     |
| Cognitive_Score     | Numerical   | AI-generated overall cognitive performance score     |
| AI_Predicted_Score  | Numerical   | ML model’s prediction of cognitive performance       |


Dataset Details

The dataset includes 80,000 rows representing individuals with different cognitive characteristics.
Data is collected from surveys and cognitive assessments.
It is suitable for machine learning, data analysis, and AI-based research.