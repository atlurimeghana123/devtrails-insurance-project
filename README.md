# Income Protection Platform for Delivery Workers  

## The Problem
  Delivery workers depend on daily earnings. But when situations like heavy rain, pollution, or traffic disruptions happen, their income suddenly drops.
  A worker earning ₹800–₹1000 per day might earn only ₹300 on bad days.
  There is **no simple system today that protects their income during such situations**.  
  Existing insurance is slow, complicated, and not designed for daily earners.

## Why This Matters  
  - Gig workers rely on **daily income to survive**  
  - Disruptions are **common and unpredictable**  
  - Income loss happens instantly  
  - Current solutions are **not practical for gig workers**  
 We need something **fast, simple, and reliable**.

## Who This Helps  
  This solution is designed for delivery partners working on platforms like:
- Zomato  
- Swiggy  
These workers face income uncertainty every day.

## Our Idea  
 We are building a system that protects delivery workers from **income loss caused by disruptions**.
 Instead of complicated claims, our system:
- Understands what a worker *should have earned*  
- Compares it with what they *actually earned*  
- Automatically provides compensation  
This makes the system **fast, fair, and simple**.

## How It Works

 Worker signs up
       ->
 Chooses a weekly plan
       ->
 System monitors disruptions
       ->
 Expected income is calculated
      ->
 Actual income drops
      ->
 System calculates loss
      ->
 Claim is triggered automatically
      ->
 Payout is given
 
## Weekly Plan Model 
 | Plan | Weekly Cost | Coverage |
 |------|------------|---------|
 | Basic | ₹20 | ₹500 |
 | Standard | ₹30 | ₹800 |
 | Pro | ₹40 | ₹1200 |

Workers can choose a plan based on their needs.

## Premium Calculation Logic 
   Weekly Premium = Base × (1 + Zone Risk + User Risk + Seasonal Risk)
  
  Where:
  - Zone Risk → how risky the delivery area is  
  - User Risk → based on past claim behavior  
  - Seasonal Risk → higher during monsoon/pollution periods

## Income Loss Calculation  
  - Expected income → predicted using past data  
  - Actual income → real earnings  
  - Loss = Expected − Actual  
  - Payout = based on plan coverage

##  What Makes This Different
  - Uses multiple signals, not just weather  
  - Combines real data and simulated data  
  - Focuses on actual income loss  
  - Fully automated process  
  - Designed specifically for gig workers

##  AI Integration
  AI is used to:
  - Estimate expected income  
  - Understand risk levels  
  - Detect suspicious activity

## Fraud Detection  
  To prevent misuse:
  - Validate worker location  
  - Verify disruption events  
  - Detect duplicate claims  
  - Analyze behavior patterns

## Anti-Fraud & GPS Spoofing Strategy    
  - Check movement consistency  
  - Verify real activity before disruption  
  - Compare behavior across users  
  - Detect suspicious clusters  
This helps identify fake claims without affecting genuine workers.

## Tech Stack  
  Frontend → React  
  Backend → Node.js  
  Database → MySQL  
  AI → Python

##  Development Plan
   Phase 1 → Idea and design  
   Phase 2 → Core system development  
   Phase 3 → AI, fraud detection, dashboard  

##  Final Thought
  This project aims to build a **simple, fair, and reliable income protection system** for delivery workers.
  A system that supports the people who keep cities running.

## Team
   **CompileCrew**


