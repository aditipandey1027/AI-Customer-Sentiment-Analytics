# AI Customer Sentiment & Deflection Matrix
### Customer Experience Intelligence | Power BI | Power Query | DAX

> A customer experience analytics solution designed to examine digital friction, order completion, customer satisfaction, and support-ticket patterns through a consolidated business intelligence dashboard.

## Executive Overview

Customer experience issues can affect digital engagement, transaction completion, and support demand. However, these indicators are often difficult to interpret when customer-session, order, and support-ticket data are examined separately.

The **AI Customer Sentiment & Deflection Matrix** brings these analytical domains together in a Power BI reporting environment. It enables structured exploration of customer friction, order-completion patterns, customer satisfaction, sentiment categories, and support operations.

The project demonstrates how data preparation, analytical measures, and business-focused visualizations can convert fragmented data into a more accessible view of customer experience.

**Project classification:** Customer Experience Analytics · Business Intelligence · Descriptive Analytics

**Dataset:** Synthetic data · 10,000 rows in the final consolidated query

## Business Context

Digital product and customer support teams need to understand where customer friction occurs, which issues generate support demand, and how customer experience indicators vary across sessions.

This project establishes a consolidated analytical view to help investigate those questions.

### Business objectives

- Quantify sessions flagged for customer friction.
- Monitor order-completion performance.
- Compare order completion across customer-friction groups.
- Identify support-ticket categories with higher reported volumes.
- Examine customer satisfaction and sentiment distributions.
- Monitor ticket-resolution patterns.
- Present key customer experience indicators in a single reporting interface.

## Technical Architecture

| Component | Implementation |
|---|---|
| Data preparation | Microsoft Power Query |
| Data consolidation | Consolidated customer experience analysis query |
| Analytical calculations | DAX measures |
| Reporting and visualization | Microsoft Power BI |
| Dataset | Synthetic customer session, order, and support-ticket data |

### Data domains

**Customer interaction data**  
Session and clickstream information used to represent customer activity.

**Order and friction indicators**  
Order-completion fields and friction flags used to compare customer-session outcomes.

**Customer support data**  
Ticket identifiers, issue categories, customer satisfaction scores, sentiment categories, and resolution status.

The final consolidated query is named `AI_Customer_Experience_Final` and contains 10,000 rows.

## Data Preparation and Quality

The preparation workflow used Power Query to organize source data for reporting and analysis.

Key activities included:

- Cleaning and transforming source fields.
- Consolidating customer experience data into a final analysis query.
- Reviewing data types required for analytical calculations.
- Investigating missing issue-category values.
- Preserving records during data-quality checks.
- Retaining `UNKNOWN` as a valid category where applicable.
- Preparing fields for KPI calculations and dashboard visuals.

## KPI Framework

The dashboard presents six key performance indicators.

| KPI | Definition |
|---|---|
| Total Sessions | Count of distinct customer sessions |
| Customer Friction Rate | Percentage of distinct sessions flagged for friction |
| Order Completion Rate | Percentage of distinct sessions associated with completed orders |
| Total Support Tickets | Count of distinct, nonblank ticket identifiers |
| Average CSAT | Average numeric customer satisfaction score |
| Total Orders | Count of distinct sessions marked as completed |

These measures provide a high-level view of customer activity, friction, transaction completion, satisfaction, and support demand.

## Analytical Views

### Customer Satisfaction Distribution
Examines the distribution of customer satisfaction scores or categories to understand observed satisfaction patterns.

### Support Tickets by Issue Category
Compares ticket volumes by issue category to identify frequently reported support themes.

### Order Completion by Customer Friction
Compares completion patterns across friction groups to investigate potential relationships between friction and transaction outcomes.

### Customer Sentiment Breakdown
Displays the distribution of sentiment categories available in the dataset.

### Support Ticket Resolution Status
Summarizes ticket distribution across resolution statuses to provide visibility into support operations.

## Business Applications

The dashboard supports exploratory questions relevant to digital product, customer experience, and support operations teams:

- Which reported issue categories account for higher support-ticket volumes?
- What proportion of sessions is flagged for friction?
- How does order completion vary between friction groups?
- What patterns appear in customer satisfaction and sentiment?
- How are support tickets distributed by resolution status?

The results can help prioritize areas for further investigation. They should be interpreted as descriptive findings rather than proof of causation.

## Reporting Design

The dashboard uses a custom **Midnight AI** theme to maintain a consistent, professional reporting experience.

- Dark navy visual surfaces.
- Teal and steel-blue accents.
- Orange highlights for selected categories.
- Consistent KPI card formatting.
- High-contrast chart labels and titles.
- Structured visual hierarchy for business reporting.

## Scope and Analytical Limitations

This implementation focuses on data preparation, DAX-based KPI development, and Power BI visualization.

- The dataset is synthetic and does not contain real company customer records.
- The analysis describes observed patterns in the prepared data.
- Causal effects have not been established.
- Actual revenue loss or financial savings have not been validated.
- No machine-learning model, production AI classifier, or automated ticket-deflection system has been deployed.
- SQL is not part of the current implementation.

The project explores a customer experience analytics use case with potential future AI extensions; its title does not imply a completed production AI system.

## Future Development Roadmap

Potential extensions include:

1. SQL-based analysis of customer sessions and support operations.
2. Deeper customer-journey and friction analysis.
3. Revenue-at-risk calculations using validated financial assumptions.
4. Evaluation of machine-learning-based sentiment classification.
5. Assessment of potential support-ticket deflection opportunities.

These items represent future development opportunities, not completed capabilities.

## Repository Contents

- `AI_Customer_Sentiment_Deflection_Matrix.pbix` — Power BI report.
- `dashboard-preview.png` — Dashboard preview image.
- `README.md` — Project documentation.

## Skills Demonstrated

**Business Intelligence:** Power BI reporting, dashboard design, KPI development, DAX measures.

**Data Preparation:** Power Query, data cleaning, transformation, data consolidation, data-quality investigation.

**Analytics:** Customer Experience Analytics, Customer Satisfaction (CSAT), Digital Friction Analysis, Order Completion Analysis, Support Operations Analytics, Sentiment Distribution Analysis.

**Business Skills:** Business question formulation, exploratory analysis, metric interpretation, data visualization, analytical storytelling.

## Author

**Aditi Pandey**  
Aspiring Data Analyst | Business Intelligence | Power BI | Power Query | DAX

*Portfolio project demonstrating practical application of data preparation, analytical calculations, and business intelligence reporting.*

