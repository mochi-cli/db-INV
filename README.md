# Mochi Inventory Template

This repository defines the `inventory` MochiKit workspace template.

## Tables

- `Suppliers`
- `Products`
- `Inventory`
- `Shipments`
- `Order_History`

## Relationships

- Suppliers can have many shipments.
- Products have one inventory record.
- Products can have many shipments.
- Products can have many order history records.

## Use

```bash
mochikit init --template inventory
```

MochiKit reads this template through its template registry.
