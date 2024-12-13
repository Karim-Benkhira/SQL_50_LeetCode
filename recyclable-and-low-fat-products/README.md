# Table: Products

## Problem Statement

Write a SQL query to find the IDs of products that are both:
- **Low fat** (`low_fats = 'Y'`)
- **Recyclable** (`recyclable = 'Y'`)

### Requirements:
- Return the result in any order.
- The output should include only the `product_id` of the matching products.

---

## Example

### Input:
`Products` table:
| product_id | low_fats | recyclable |
|------------|----------|------------|
| 0          | Y        | N          |
| 1          | Y        | Y          |
| 2          | N        | Y          |
| 3          | Y        | Y          |
| 4          | N        | N          |

### Output:
| product_id |
|------------|
| 1          |
| 3          |

### Explanation:
- Products with IDs `1` and `3` satisfy both conditions:
  - They are low fat (`low_fats = 'Y'`).
  - They are recyclable (`recyclable = 'Y'`).

---
