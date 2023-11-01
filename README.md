
# Market Basket Insights

## Table of Contents
1.Introduction
2.Problem Statement
3.Design Thinking Process
4.Phases Of Development
5.Submission


## Introduction
This project aims to analyze customer purchase behavior using market basket analysis to help a retail business make data-driven decisions. It includes identifying associations between products purchased by customers, optimizing product placements, cross-selling, and creating effective marketing strategies.

## Problem Statement
The retail business seeks to understand the relationships between products purchased by customers and identify associations or patterns to improve sales, customer satisfaction, and marketing strategies.

## Design Thinking Process
Our approach is customer-centric, focusing on understanding customer preferences and behaviors. We followed these steps in the design thinking process:

- Empathize: Gathered customer transaction and preference data.
- Define: Defined project objectives.
- Ideate: Brainstormed potential associations and patterns.
- Prototype: Implemented association analysis techniques.
- Test & Iterate: Evaluated and refined the discovered association rules.

## Phases of Development
### 1. Data Collection
- Data Source: [Kaggle dataset](https://www.kaggle.com/datasets/aslanahmedov/market-basket-analysis)
- Data Description: Contains transaction records of a retail store, including customer IDs, product IDs, and purchase timestamps.

### 2. Data Preprocessing
- Handling Missing Values: Checked for and handled missing values, if any, in the dataset.
- Data Encoding: Encoded categorical variables like product IDs.
- Data Transformation: Converted transaction data into a suitable format for association analysis.

### 3. Association Analysis Techniques
- Used the Apriori algorithm for discovering association rules.
- Set minimum support and confidence levels for rule generation.

### 4. Discovered Association Rules
- Identified significant association rules, e.g., "If customers buy product A, they are likely to buy product B."
- Examples of discovered rules: (A -> B with confidence X% and support Y%)

### 5. Business Implications
- Improved Product Placement: Insights from the association rules can optimize product placements.
- Cross-selling: Rules can promote complementary products or offer discounts.
- Targeted Marketing: The rules can guide marketing campaigns for specific customer segments.

## How to Run the Code
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run the code by executing code file name.ipynb using Jupyter NoteBook.
   ```
 To Run Our Coding File in Microsoft Visual Studio Code
   ```
   
## Dependencies
- List any libraries or dependencies required to run the code, e.g., Python, NumPy, Pandas, etc.

## Dataset Source and Description
- Dataset Source: [Kaggle dataset](https://www.kaggle.com/datasets/aslanahmedov/market-basket-analysis)
- Description: This dataset contains transaction records of a retail store, including customer IDs, product IDs, and purchase timestamps. It is used for market basket analysis to discover customer purchase patterns.

## Submission
You can access and review this project on GitHub: [Link to GitHub Repository](https://github.com/prasanna-devi-1269/AI-PHASE1Project110521104031.git)

---
