# AI-Hallucination-Risk-Dashboard
## Overview

As AI tools become embedded in business decision-making, a critical risk emerges: AI hallucinations — confident but incorrect or incomplete insights influencing high-impact decisions.

This project approaches the problem from an AI governance and business analytics perspective, answering:

When does AI become dangerous for business decisions?

Instead of evaluating AI models technically, the analysis quantifies business risk, revenue exposure, and governance gaps caused by AI usage.

## AI Governance

AI Governance ensures AI is used responsibly, safely, and within defined business boundaries.

From a business lens, it addresses:

Which decisions should AI influence?

Where is human review mandatory?

How much revenue is exposed to AI errors?

This project demonstrates how data analysts can support AI governance without building AI models.

## Objective

To measure and visualize:

AI hallucination risk

Overconfidence in AI outputs

Business and revenue exposure

Impact of governance policies on AI risk

## Dataset

Synthetic enterprise data (50K records)

Simulates AI usage across Finance, Sales, HR, and Operations

Includes decision impact values, AI confidence scores, and decision types

Synthetic data enables realistic risk simulations not available in public datasets.

## Hallucination Definition 

An AI response is considered a hallucination when:

The AI is highly confident and

The response is factually incorrect or

Key business assumptions are missing

This allows risk even when outputs are partially correct.

## Methodology

SQL: Built a canonical view (v_ai_hallucination) to define business-level hallucination logic

Risk Metrics: Hallucination Rate, Overconfidence Index, Assumption Gap Score

AI Risk Score: Weighted composite metric (0–100)

Segmentation: Risk by department, decision type, impact bucket, and time

Policy Simulation: Human review for strategic decisions above ₹10L

## Dashboard Highlights

Overall AI Hallucination Rate

AI Risk Score

Revenue at Risk (₹)

High-risk departments and decisions

Before vs After policy simulation

Designed for executive-level decision-making, not just reporting.

## Key Insights

~35% of AI-influenced decisions showed hallucination risk

Strategic, high-impact decisions carried the highest exposure

Finance and Sales contributed most to revenue at risk

A ₹10L human-review policy reduced hallucination exposure by ~80–90%

Significant reduction in simulated revenue risk

## Tools & Skills

SQL (SQL Server) – Views, CASE logic, risk aggregation

Python – Risk modeling, scenario simulation

Power BI – DAX measures, policy simulations, dashboards

Business Analytics – Metric design, AI governance thinking

## Why This Project Stands Out

Focuses on AI governance and risk, not model accuracy

Quantifies business impact, not just analytics outputs

Demonstrates decision-intelligence and policy thinking

Highly relevant to modern data and analytics roles

## Author

Nikita Albela
MBA (HR & Business Analytics)
Aspiring Data Analyst focused on business-first analytics, risk modeling, and AI governance.
