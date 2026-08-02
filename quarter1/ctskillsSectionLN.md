# Annex A
# Computational Thinking Exercise: Smart School Canteen Queue

**Section:** 9-Calcium  
**Score:** ____________  
**C# / Name:** Flory Blaire N. Credo  
**Date:** 07-31-2026

## Scenario

The PSHS school canteen is small and often gets crowded during lunch break. Students line up to buy food, but the process is slow because:

- Some students take too long to decide what to order.
- The cashier has to manually calculate totals and give change.
- There is no system to track which food items are running out.

Your group's task is to decompose this problem into smaller, manageable parts that could be solved with computational thinking (CT) skills.

## Step 1: Identify the Big Problem

**Main Problem:**

The school canteen is slow during lunch because there are long lines, slow ordering, manual payment, and no way to track food supplies.

## Step 2: Identify Three to Four Sub-Problems

1. Students take too long to decide what food to order.
2. The cashier manually calculates the total amount and change, which takes time and may lead to mistakes.
3. The canteen staff do not have a system to monitor food inventory, so some food items run out without notice.
4. Students have no organized queue management system, causing confusion and delays.

## Step 3: Define Computational Thinking Approaches

| Sub-Problem | CT Skill | Example Solution |
|-------------|----------|------------------|
| Students take too long to decide on orders. | Decomposition | Display the menu before the line so students decide early. |
| Cashier manually computes totals and change. | Algorithm Design | Create a system that automatically calculates the total cost and change after entering the selected food items and payment amount. |
| No inventory tracking. | Pattern Recognition | Monitor which food items sell quickly every day and automatically notify staff when stock is low. |
| Queue is disorganized. | Abstraction | Focus only on the order in which students arrive and assign queue numbers to keep the line organized. |

## Step 4: Pseudocode

```text
START

Input selected food items
Set Total = 0

For each selected item
    Add item price to Total
End For

Display Total

Input AmountPaid

IF AmountPaid >= Total THEN
    Change = AmountPaid - Total
    Display "Payment Successful"
    Display "Change: ", Change
ELSE
    Display "Insufficient Payment"
END IF

STOP
```

## Reflection

Breaking the main problem into smaller sub-problems made it easier to identify specific solutions for each issue instead of trying to solve everything at once. Computational thinking skills such as decomposition, algorithm design, pattern recognition, and abstraction helped organize the problem and develop practical solutions that could improve the efficiency of the school canteen.
