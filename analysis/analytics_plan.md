# ReviewLens — Data & Analytics Plan

## Objective

Analyse customer review data to identify recurring product-level
experiences and convert unstructured feedback into actionable insights.

---

## Data Used

ReviewLens will use customer review data containing:

- Review ID
- Product / Order ID
- Review rating
- Review text
- Review date

Where available, product-level information can be joined with review
data to analyse patterns across products and categories.

---

## Review Analysis Pipeline

Customer Reviews
        ↓
Data Cleaning
        ↓
Review Filtering
        ↓
Theme / Aspect Classification
        ↓
Positive & Negative Signal Detection
        ↓
Frequency Analysis
        ↓
Product-Level Insights
        ↓
ReviewLens Reality Snapshot

---

## Core Review Categories

Reviews will initially be classified into product-experience themes:

1. Fit / Size
2. Fabric / Quality
3. Colour / Appearance
4. Product-photo Match
5. Comfort
6. Durability
7. Delivery / Fulfilment
8. Wrong Product / Variant
9. Return / Refund Experience
10. Other

---

## Analytics Questions

The analysis will answer:

### Q1. What are customers talking about most?

Measure the frequency of each review theme.

### Q2. What are the most common negative experiences?

Identify recurring negative themes within low-rated or negative reviews.

### Q3. Which product categories have stronger pain signals?

Compare review themes across product categories.

### Q4. Are some issues recurring across products?

Identify themes that appear repeatedly across multiple products.

### Q5. Does recency change the signal?

Compare recent feedback with older reviews to identify whether a
problem appears persistent or declining.

---

## Key Metrics

### Review-level metrics

- Total reviews analysed
- Reviews containing text
- Positive vs negative reviews
- Theme frequency
- Theme sentiment

### Product-level metrics

- Average rating
- Number of reviews
- Most common positive theme
- Most common negative theme
- Negative-theme frequency
- Recent vs historical theme frequency

---

## GenAI / NLP Layer

ReviewLens can use GenAI/NLP to transform unstructured customer reviews
into structured product insights.

Potential applications include:

- Review theme classification
- Identification of recurring customer concerns
- Grouping similar customer experiences
- Summarising recurring patterns
- Generating concise Product Reality Snapshots

For this case study, GenAI/NLP is treated as a proposed product
capability rather than a production-ready AI system.

Any AI-generated insight would require validation before being surfaced
to customers.

---

## Important Validation Principle

AI-generated insights should not automatically be treated as ground
truth.

Before launching at scale, the outputs should be validated against
manually reviewed customer feedback.

Validation should monitor:

- Classification accuracy
- False or misleading summaries
- Unsupported claims
- Customer trust

---

## Product Output

The final analytical output will feed into the ReviewLens
Product Reality Snapshot.

Example:

Theme                  Signal
--------------------------------
Fabric / Quality       High
Fit / Size             Medium
Colour / Appearance    Low
Photo Match            Positive

This converts raw review text into a structured product insight.
