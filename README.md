# Adversarial Attacks on Tabular Data Classifiers

Guaranteeing the security of Machine Learning (ML) classifiers is a crucial priority of all institutions
employing automatic decision-making systems, to protect their businesses against cyberattacks and
fraudulent attempts. Adversarial attacks are novel techniques that, other being proven to be effective
to fool image classification models, can also be applied to tabular data. Adversarial attacks aim
at producing adversarial examples, in other words, slightly modified inputs that induce the Artificial
Intelligence (AI) system to return incorrect outputs that are advantageous for the attacker. To illustrate
the threat of adversarial attacks in a tabular context, we consider the scenario where a bank customer
applies for a loan. A machine learning model is used to make a decision regarding the acceptance of
the application based on customer provided information (incomes, age, etc.). The model advises the
bank to reject the application of our customer. However, he is determined to get the loan by filling
false information to mislead the model. The key for this attack to succeed is its imperceptibility: the
application should remain credible and relevant, in coherence with the model’s prediction. An adversarial attack must create adversarial samples x_adv that are sufficiently close to the
real data x, i.e., |x − x_adv |2 < ϵ, where ϵ is that maximum distance to which an attack is considered
credible.


**This Project entails the exploration of the impact of adversarial attacks on tabular data
classifiers, and the study of the possible countermeasures against such attacks, specifically within the context of loan risk prediction using the German Credit Risk dataset.**


The Doc directory contains an extensinve and in-depth report of the whole Project.
The Source directory contains the Project Jupyter Notebook.
The Dataset directory contains the German Credit Risk dataset.
Additionally, the virual environment with all required dependencies is inserted.

## PART 1: Data Exploration and Preprocessing

- Dataset PreProcessing, Exploratory Data Analysis.

## PART 2: Unsupervised Exploration and Clustering

- Dimensionality Reduction for Data Visualization: PCA and t-SNE.

- Unsupervised Data Analysis: K-Means and GMM Clustering algorithms. Purity study.

## PART 3: Supervised Data Analysis

- Classifier Selection, Cross Validation and Classifier Evaluation.

## PART 4: Adversarial Attacks and Defenses Exploration

- Naive Attack: Random Noise applied on whole dataset.

- Naive Attack v2: Random Feature Specific Noise. Noise only applied to selected features.

- Adversarial Attacks: FGSM, PGD (inf norm, square norm, targeted PGD), HopSkipJump, DeepFool.

- Countermeasure Exploration: Nested Adversarial Training, Gradient Obfuscation, Data Sanitization.


