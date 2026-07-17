# Perplexity AI: Marketing, Analytics & Campaign Architecture

This repository contains the comprehensive strategic documentation for Perplexity AI's digital marketing ecosystem. It covers the end-to-end architecture from campaign structure and ad creative management to conversion tracking and performance optimization.

---

## 📑 Documentation Index

### 1. Conversion Tracking & Analytics Architecture
*   **Purpose**: Establish a data-driven framework for measuring performance and feeding machine-learning bidding algorithms.
*   **Key Components**:
    *   **Value Mapping**: Assigns monetary values to user actions (Pro Sub: $20, Education: $10, Free Sign-up: $1, App Download: $2.50).
    *   **GA4 Event Framework**: Standardized event tracking for `page_view`, `sign_up`, `begin_checkout`, `purchase`, and `app_download`.
    *   **Funnel Analysis**: A detailed conversion funnel drop-off matrix identifying friction points (Bounce Rate, Sign-up friction, Monetization gaps).

### 2. Ad Creatives & Analytics Architecture
*   **Purpose**: Define the creative strategy and messaging for Google Ads.
*   **Key Components**:
    *   **RSA Copywriting Matrix**: Segmented strategies for Brand, Generic, and Competitor Conquest campaigns.
    *   **Creative Focus**: Differentiates between benefit-focused, trust-based, and feature-led messaging.
    *   **Extensions & Assets**: Standardized Sitelink and Callout configurations for high-intent search paths.

### 3. Google Ads Campaign Structure Architecture
*   **Purpose**: Meticulous hierarchy to maximize Quality Score and minimize CPA.
*   **Key Components**:
    *   **Campaign/Ad Group Mapping**: Segregated by intent (Brand Defensive, High-intent Product Search, Commercial Pricing, Competitor Conquest).
    *   **Keyword Strategy**: Strict match-type assignment (Exact for high-intent, Phrase for discovery) to prevent bidding wars.

### 4. Campaign Integrity & Negative Keyword Strategy
*   **Purpose**: Operational integrity and waste mitigation.
*   **Key Components**:
    *   **Negative Keyword Lists**: Proactive filtering of non-commercial traffic, including job seekers, employment-related searches, and "cracked/torrented" software users.
    *   **Integrity Checklist**: Standardized landing page alignment, proactive Search Terms Report (STR) reviews, and match-type overlap prevention.

---

## 📊 Data Architecture & Implementation Logic

The core of this marketing engine is managed via the **`Marketing_Performance_Logic.xlsx`** file. While the strategy documents above define the "what," this spreadsheet serves as the "how," providing the functional data layer for the entire system:

*   **Conversion Value Modeling**: Contains the mathematical formulas used to assign monetary weight to user actions (Pro Sub, Education, Sign-up), allowing for precise ROI calculations.
*   **Campaign Hierarchy Matrix**: Maps specific ad groups to targeted keyword sets, ensuring 1:1 relevance between search intent and landing page content to maximize Quality Score.
*   **Waste Mitigation Database**: Maintains the master list of negative keywords, proactively filtering out non-commercial traffic and ensuring budget efficiency.
*   **Funnel Drop-off Analysis**: Provides the raw data and projections for the conversion funnel, identifying exactly where users drop off and how to optimize those specific stages.

*This file acts as the operational interface for the Perplexity AI ad account, bridging the gap between technical tracking (GA4) and business growth strategy.*

---

## Strategic Summary

The architecture is built for **scale** and **efficiency**. By segregating intent (Campaign structure), ensuring technical precision (GA4 framework), and aggressively filtering low-value traffic (Negative keywords), Perplexity AI ensures high-intent traffic reaches the most relevant landing pages, thereby optimizing for long-term ROI.
