# Fraud Detection Pipeline using PySpark


# Problem statement
Financial places like banks have a tough time spotting fake transactions right away. 
There is just so much data coming in all the time and their systems cannot keep up fast enough. 

# Solution
For this project I built something using PySpark to handle fraud detection. 
It works by figuring out a risk score that changes based on different things like how much money is involved or where the transaction happens. 
It feels like a good way to make decisions on the fly.

# Technologies Used
I used Python for the coding part and PySpark to deal with the big data stuff. 
Everything ran in Google Colab since it is easy to set up there without needing a fancy computer.

## Pipeline Workflow
1. Load transaction data
2. Calculate transaction count per user
3. Apply risk scoring:
   - High transaction amount
   - High-risk location
   - Frequent transactions
   - Rapid transactions
4. Compute final fraud classification

## Fraud Detection Logic
- Amount-based risk
- Location-based risk
- Behavioral analysis (txn_count)
- Transaction velocity (rapid_txn)

# Steps to run the prg
1. Open the notebook in Google Colab
2. Install PySpark
3. Run all cells step-by-step

# Output
- Risk score for each transaction
- Final fraud classification

From doing this I got a better sense of how PySpark DataFrames work and building out these data pipelines.
Also putting together logic that looks at more than one factor for something like fraud detection. It is not perfect but it covers the basics.

This could work well for a workshop aimed at beginners. Maybe to show data engineering starting points or the fundamentals of PySpark. And how real systems catch fraud in practice. 
