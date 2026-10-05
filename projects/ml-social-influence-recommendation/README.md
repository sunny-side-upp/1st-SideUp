# ML-Based Social Influence Recommendation Model

## Overview
A machine learning project developed during my undergraduate work at Manipal University Jaipur to explore how social influence and user proximity can improve product recommendations in e-commerce.

## Problem
Traditional recommendation approaches can rely heavily on a user's own interaction history. This project explored whether relationships and behavioural proximity between users could provide additional signal for recommendation relevance.

## Approach
- Processed behavioural/user interaction data using Python.
- Modelled social influence and proximity between users.
- Evaluated multiple recommendation approaches.
- Benchmarked model outputs to compare recommendation accuracy.

## Product Perspective
The core product question was:

> Can signals from a user's social/behavioural network make recommendations more relevant than relying only on individual activity?

The project helped connect ML experimentation with a practical personalization use case.

## Current Status
This repository is being rebuilt as a portfolio-ready version of the original project. Source code, notebooks, evaluation results, architecture diagrams, and later improvements will be added incrementally.

## What I Would Do Differently Today
1. Define the recommendation objective and offline evaluation metric before model selection.
2. Establish a stronger baseline before introducing social-influence features.
3. Test cold-start behaviour explicitly.
4. Separate offline model quality from online product impact.
5. Design an A/B-test framework for measuring recommendation engagement and downstream conversion.

## Repository Structure
```text
ml-social-influence-recommendation/
├── README.md
├── notebooks/
├── src/
├── data/
│   └── README.md
├── results/
├── docs/
└── requirements.txt
```

## Attribution
Original academic project: Manipal University Jaipur.
