# Monthly budget summary

This example lists the open accounts of a YNAB plan with their balances, summarises the income, budgeted and activity amounts of a month, and flags categories that are overspent in that month.

## Prerequisites

- Ballerina Swan Lake 2201.x or later
- Push the connector to the local repository:
  ```bash
  cd ballerina
  bal pack && bal push --repository=local
  ```
- Create a `Config.toml` in this directory:
  ```toml
  accessToken = "<your-personal-access-token>"
  planId = "last-used"
  month = "current"
  ```

## Run the example

```bash
bal run
```
