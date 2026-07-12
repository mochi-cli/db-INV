# Mochi Inventory Template

This repository defines the `inventory` MochiKit workspace template.

## Collections

- `items`: SKU, item name, category, quantity, cost, location, and status
- `stock_movements`: stock in, out, and adjustment events
- `suppliers`: supplier contact information and notes

## Use

```bash
mochikit init --template inventory
```

MochiKit reads this template through its template registry.
