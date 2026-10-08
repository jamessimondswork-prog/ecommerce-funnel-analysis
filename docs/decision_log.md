# Decision log

Records major methodological decision, why they were made and their limitations.

---
## 1. [Decision title]
- **Date:** DD/MM/YYYY
- **Decision:**
- **Reason:**
- **Alternatives considered:**
- **Potential limitation:**

## 1. Dataset choice
- **Date:** 08/10/2026
- **Decision:** Use Google's GA4 obfuscated sample ecommerce dataset
  (Google Merchandise Store) in BigQuery.
- **Reason:** Real GA4 event-level data using the same schema found in
  professional analytics work, which links to my onsite marketing
  experience. Free to access via the BigQuery sandbox.
- **Alternatives considered:**
  - Olist Brazilian ecommerce dataset (Kaggle): rejected because it
    contains orders rather than browsing events, so the full funnel
    (view → add to cart → checkout → purchase) can't be built.
  - Universal Analytics sample dataset: rejected because GA4 has
    replaced Universal Analytics, so GA4 skills are more relevant.
- **Potential limitations:**
  - Data covers Nov 2020–Jan 2021, including Black Friday/Cyber Monday,
    Christmas and January sales, so conversion rates may not reflect
    typical periods.
  - Data is deliberately obfuscated by Google for privacy; some values
    are masked or placeholders, which may limit field-level accuracy.
  - Single retailer selling Google-branded merchandise, so findings may
    not generalise to other ecommerce businesses.
   
