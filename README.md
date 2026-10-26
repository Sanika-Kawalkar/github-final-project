# Simple Interest Calculator

A simple, lightweight application/script to calculate simple interest based on principal amount, annual interest rate, and time period in years.

## 📌 Formula

$$\text{Simple Interest (SI)} = \frac{P \times R \times T}{100}$$

Where:
- **P** = Principal amount (initial investment or loan)
- **R** = Annual interest rate (in percentage)
- **T** = Time period (in years)

---

## 🚀 Features

- Calculates total interest earned or payable.
- Computes the final total balance ($\text{Total} = P + \text{SI}$).
- Easy to run and integrate.

---

## 🛠️ Getting Started

### Prerequisites

Ensure you have Python (or your language of choice) installed:
- Python 3.x

### Usage Example (Python)

```python
def calculate_simple_interest(principal, rate, time):
    interest = (principal * rate * time) / 100
    total = principal + interest
    return interest, total

# Example:
p = 1000  # Principal
r = 5     # 5% interest rate
t = 2     # 2 years

si, amount = calculate_simple_interest(p, r, t)
print(f"Simple Interest: ${si}")
print(f"Total Amount: ${amount}")
