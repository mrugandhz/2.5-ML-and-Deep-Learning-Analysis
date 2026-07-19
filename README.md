# AIML

# Machine Learning vs. Deep Learning — Comparative Case Analysis

## Introduction
A written analysis comparing when to use traditional machine learning versus deep learning, grounded in two real-world applications.

## Objective
To demonstrate the ability to reason about tool selection in AI/ML — not just implement a model, but justify why it's the right one for a given problem.

## Example 1: Machine Learning — House Price Prediction
**Algorithm:** Linear Regression
**Real-World Application:** Zillow's "Zestimate" tool, which estimates home values using structured features such as square footage, location, and comparable recent sales.

**Why Machine Learning Is Suitable:** House price prediction relies on a manageable set of well-understood, structured features — number of bedrooms, square footage, location, and neighborhood quality — that have a fairly direct and interpretable relationship to price. Linear regression can model these relationships efficiently without requiring massive datasets or heavy computational resources. Its outputs are also interpretable: a buyer, seller, or lender can see which specific features drove a given price estimate.

**Why Deep Learning Is Not Suitable Here:** Deep learning models require large volumes of data and significant compute to justify their added complexity, and they sacrifice interpretability — a neural network's price prediction is a "black box." Since the relationships in this data are relatively simple and well-structured, deep learning's additional complexity would not meaningfully improve accuracy; it would mainly add cost and reduced transparency.

## Example 2: Deep Learning — Autonomous Driving
**Algorithm:** Convolutional Neural Networks (CNNs) and Deep Reinforcement Learning
**Real-World Application:** Tesla's Autopilot and Waymo's self-driving systems, which process camera and LIDAR input to detect pedestrians, vehicles, traffic lights, and road signs in real time.

**Why Deep Learning Is Suitable:** Autonomous driving involves raw, unstructured sensor data — images and video — where the important "features" (the shape of a pedestrian, the edges of a stop sign) cannot be manually defined in advance. These must be learned automatically from millions of examples across countless conditions. CNNs excel at this kind of automatic feature extraction, and the complexity of real-time driving decisions requires the nonlinear pattern recognition only deep networks provide at this scale.

**Why Traditional Machine Learning Is Not Suitable Here:** A traditional ML model would require engineers to manually define features like "the edge of a stop sign," which is effectively impossible given the near-infinite variability of real-world driving conditions. Without automatic feature learning, a traditional model would be too brittle and unsafe for a task where the stakes are measured in human safety.

## Conclusion
Machine learning is well-suited to structured, interpretable problems with well-understood features and moderate data requirements, while deep learning is necessary for unstructured, high-complexity problems where features can't be hand-engineered and the stakes justify the added computational cost. Choosing the right approach is about matching the tool to the structure of the problem — not defaulting to whichever method sounds more advanced.

## Tools & Technologies
Research and analytical writing (no coding tools used for this artifact).

## Value Proposition
Demonstrates conceptual fluency that complements my hands-on AI chatbot project — showing I can both build AI tools and reason critically about which technical approach fits a given business problem.

## References
Course lesson materials — Types of Machine Learning; Machine Learning vs. Deep Learning lesson, AIML-500, Indiana Wesleyan University.
