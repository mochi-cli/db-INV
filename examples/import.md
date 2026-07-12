---
mochi_example: inventory_records.v1
---

# Inventory Sample Records

This file shows the data shape for the inventory template tables.

## Suppliers

| id | supplier_id | supplier_name | supplier_contact | supplier_address |
|---|---:|---|---|---|
| supplier_001 | 1 | Northwind Wholesale | ops@northwind.example | 100 Harbor Road, Seattle |
| supplier_002 | 2 | Atlas Components | supply@atlas.example | 42 Market Street, San Francisco |

## Products

| id | product_id | product_name | unit_price | quantity_in_stock |
|---|---:|---|---:|---:|
| product_001 | 1 | Black Shirt | 18.50 | 120 |
| product_002 | 2 | Denim Jacket | 49.00 | 32 |

## Inventory

| id | inventory_id | product_id | quantity_available | last_stock_update |
|---|---:|---:|---:|---|
| inventory_001 | 1 | 1 | 120 | 2026-07-12T09:00:00 |
| inventory_002 | 2 | 2 | 32 | 2026-07-12T09:30:00 |

## Shipments

| id | shipment_id | product_id | supplier_id | quantity_shipped | shipment_date |
|---|---:|---:|---:|---:|---|
| shipment_001 | 1 | 1 | 1 | 80 | 2026-07-10 |
| shipment_002 | 2 | 2 | 2 | 20 | 2026-07-11 |

## Order_History

| id | order_id | product_id | order_date | order_quantity | total_cost | status |
|---|---:|---:|---|---:|---:|---|
| order_001 | 1 | 1 | 2026-07-12 | 12 | 222.00 | Pending |
| order_002 | 2 | 2 | 2026-07-12 | 3 | 147.00 | Delivered |
