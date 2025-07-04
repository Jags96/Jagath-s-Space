---
title: "What does it do: the Apartment Recommender"
date: 2024-11-28
tags: ["Recommendation System", "Ranking System", "Creative Idea", "Python"]
author: ["Jagath Kumar Reddy K"]
description: "Creative and custom rank scoring ideas for apartment recommender systems."
summary: "Creative and custom rank scoring ideas for apartment recommender systems."
cover:
  image: "cropped.gif"  
  alt: "Animated image of apartment recommendation concept"
  relative: true
editPost:
    URL: "https://github.com/Jags96/Score-Apartment-Recommender"
    Text: "Github"
showToc: false
disableAnchoredHeadings: false
---



---

**Apartment Recommender**
---

### **Summary**

> “Apartments Recommendation System based on user preferences with flexible search filters; Custom Flexibility Options; Feature Similarity recommendation”

**Project Link:** [Group Project](https://datasciencegroup1.streamlit.app/score_based_top_apartments)

**Dataset Link** [Dataset](https://archive.ics.uci.edu/dataset/555/apartment+for+rent+classified)



**Code Link** [GitHub](https://github.com/Jags96/Score-Apartment-Recommender)

---

### **Major Features**

1. Flexible Search Filters for Bathroom and Bedroom Count; custom flexibility design.
2. Keyword Search Filter.
3. Higher Dimensional Feature Similarity Recommendations using SVD.

---

### **Intention / Motivations**

* Example scenario: A user wants a 3-bed, 3-bath apartment in Texas, but might accept 2 bathrooms.
* Existing systems require manually selecting all possible combinations, which is tedious.
* The proposed system allows users to specify a **level of flexibility**, simplifying the selection process.
* A **score-based filtering system** ranks apartments similarly to search engine rankings.

---

### **Custom Score-Based Filtering**

**Idea / Logic:**

* **Score out of 10** is given for room count preferences.
* **Score = 10** → No flexibility (strict filter).
  **Score = 1** → Maximum flexibility.
* Chosen room counts receive full score; nearby counts share redistributed points.
* Filtering is based on location (state and city).
* Each apartment receives a **total score** = sum of its feature scores.
* Apartments are displayed based on this total score.

---

### **Redistribution of Flexibility Score**

* Score redistribution logic adjusts values for non-exact matches (e.g., nearby room counts).

---

### **Checkout the Flexible Search Filter**

[Group Project](https://datasciencegroup1.streamlit.app/score_based_top_apartments)

---

### References

- Apartment for Rent Classified [Dataset]. (2019). UCI Machine Learning Repository. https://doi.org/10.24432/C5X623.