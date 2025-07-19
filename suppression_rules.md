## Suppression Rulebook

### 1. Seasonality-Aware Suppression
- "Winter Coat" in September ➜ Suppress
- "Sunscreen" in May ➜ Do not suppress

### 2. Sell-Through Rate Segmentation
- High ➜ Likely recent, suppress
- Medium ➜ Depends on age + category
- Low ➜ Allow alert if Days_Aged exceeds threshold

### 3. Multi-Zone Buffer Logic
- If SKU exists in ≥2 Zones ➜ Suppress aging alerts unless total units are stagnant
- If only 1 Zone ➜ Treat as higher risk

