# Day 4 — Batch Learning vs Online Learning

Today I learned two ways of training Machine Learning models:

- Batch Learning
- Online Learning

## 1. Batch Learning

In Batch Learning, the model is trained using a **large amount of data at once**.

The model is trained first and then deployed to production.

### Process

Data → Train Model → Test → Deploy → Production

### Example

Suppose we have 1 million images of dogs and cats.

We can train the model using the available dataset:

1 million images → Train → Test → Deploy

If new data arrives, we collect it and train/update the model again in another batch.

### Advantages

- Suitable for large datasets
- Training can be done periodically
- Simple to manage

### Disadvantage

The model does not learn immediately when new data arrives.

---

## 2. Online Learning

In Online Learning, the model learns **incrementally as new data arrives**.

Instead of waiting for a large dataset, the model updates continuously or in small batches.

### Process

New Data → Model Update → New Data → Model Update → ...

### Example

YouTube recommendations continuously receive new information about:

- Videos watched
- Likes
- Searches
- User interactions

The model can learn from new data incrementally and update its predictions.

### Advantages

- Useful for continuously changing data
- Can adapt quickly to new patterns
- Suitable for large or streaming datasets
- Does not always require retraining on the entire dataset

---

## Batch Learning vs Online Learning

| Batch Learning | Online Learning |
|---|---|
| Trains on a large batch of data | Learns incrementally |
| Training happens periodically | Learning can happen continuously |
| New data waits for the next training cycle | New data can update the model quickly |
| Good for stable datasets | Good for continuously changing data |

## Simple Example

### Batch Learning

```text
Monday → Collect data
       ↓
Train model
       ↓
Test model
       ↓
Deploy
