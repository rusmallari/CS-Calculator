# CS-Calculator

## Overview
FICO Credit Score Calculator is a Python-based financial application designed to estimate a user's credit score using the main FICO metrics: payment history, credit utilization, length of credit history, and recent credit inquiries. Users input their financial information over the past 12 months to receive an estimated credit score and a detailed breakdown of how each factor contributes to their score.

The goal of this project is to provide a realistic, educational tool that demonstrates how credit scoring works and helps users understand the financial behaviors that influence their credit health.

---

## Features

### Credit Score Estimation
- Calculates an estimated FICO credit score (300–850) based on user inputs.
- Considers the major credit scoring factors:
  - Payment History (35%)
  - Credit Utilization (30%)
  - Length of Credit History (15%)
  - Recent Credit Inquiries (20%)
- Provides an easy-to-read rating: Excellent, Good, Fair, or Poor.

### User Input System
Users can input financial details including:
- Number of on-time payments (past 12 months)
- Total scheduled payments (past 12 months)
- Total credit limit
- Total credit used
- Length of credit history (years)
- Recent credit inquiries (past 12 months)

### Score Breakdown
- Displays the estimated credit score.
- Shows contribution of each factor to the overall score.
- Highlights areas that may need improvement.

---

## Application Flow
1. **Input Screen:** Users enter credit-related financial information for the past 12 months.  
2. **Score Calculation:** The system analyzes inputs and calculates an estimated FICO score.  
3. **Results Display:** The application presents the score along with a breakdown of contributing factors.  
4. **Improvement Tips:** Users receive guidance on improving their credit profile.  

---

## Technologies Used
- Python 3.x  
- Tkinter for GUI development  
