# Problem Description

A reporting query on an e-commerce database was taking approximately 10–12 seconds to execute.

## Database Context
- Orders table: ~1 million rows
- Customers table: ~100k rows

## Issues Observed
- Full table scan on Orders
- Missing indexes
- Inefficient JOIN conditions

## Impact
- Slow dashboard loading
- Poor user experience