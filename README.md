## Depress-Anxiety-Stress-Prediction

Mental illness is a health problem that could have an influence on emotions, reasoning, and social interactions of a person. Examples of it include depression, anxiety disorders, and stress. In particular, as with anyone who finds themselves in an unexpected situation, they may experience the feelings of grief and loss, be overwhelmed and fearful of the future.

The impact of living with mental illness may be different for everyone. Some may find it as a barrier to education and employment; for others, it may notably affect their work.

We utilized the Depression Anxiety Stress Scales (DASS-42) survey dataset to predict users' mental health conditions with high accuracy. The DASS-42 is a 42-item self-report scale designed to measure the emotional states of depression, anxiety, and stress. The survey, available at (OpenPsychometrics.org), was open to individuals motivated to receive personalized results regarding their mental health. Questions, answers, and metadata is collected from 39775 participants.

The dataset was preprocessed and divided into separate datasets for each condition—depression, anxiety, and stress.

We employed several machine learning algorithms, including Random Forest, Decision Tree, Gaussian Naive Bayes, K Nearest Neighbors, and Support Vector Machine (SVM).

After training and evaluating these models, the SVM model emerged as the most accurate.
