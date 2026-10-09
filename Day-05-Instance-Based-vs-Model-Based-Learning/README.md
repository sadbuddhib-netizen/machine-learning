# Day 5 — Instance-Based Learning vs Model-Based Learning

Today I learned two approaches to Machine Learning:

## 1. Instance-Based Learning

Instance-Based Learning stores training examples and compares new data with similar examples to make predictions.

**Example: K-Nearest Neighbors (KNN)**

Suppose we want to classify an animal as a cat or dog. KNN compares the new animal's data with nearby examples and predicts its class based on its nearest neighbors.

**Process:**

Training Examples → Find Similar Examples → Make Prediction

**Key Point:** Instance-Based Learning learns through similarity.

## 2. Model-Based Learning

Model-Based Learning learns patterns from training data and builds a model to make predictions on new data.

**Example: Linear Regression**

A model learns the relationship between hours studied and exam marks. It then uses this relationship to predict marks for a student who studies for a new number of hours.

**Process:**

Training Data → Learn Patterns → Build Model → Make Prediction

**Key Point:** Model-Based Learning uses a learned model to make predictions.

## Comparison

| Instance-Based Learning | Model-Based Learning |
|---|---|
| Stores training examples | Learns a general pattern |
| Compares new data with similar examples | Uses the trained model |
| Example: KNN | Example: Linear Regression |

## What I Learned

Instance-Based Learning makes predictions by comparing examples, while Model-Based Learning learns a general pattern from data and uses it to predict outcomes.
