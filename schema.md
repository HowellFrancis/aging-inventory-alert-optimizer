## Dataset Schema

| Column            | Description                                          |
|-------------------|------------------------------------------------------|
| SKU               | Unique product identifier                            |
| Zone              | Fulfillment center or geographic region              |
| Category          | Product category (e.g., Winter Coats, Electronics)   |
| Season            | Current season context (Winter, Spring, etc.)        |
| Days_Aged         | Inventory aging in days                              |
| Units             | Units currently held in the FC                       |
| Sell_Through_Rate | Velocity class (e.g., High, Medium, Low)             |
| Alert_Triggered   | 1 if an aging alert was issued                       |
| Suppress_Flag     | 1 if the alert should be suppressed                  |

