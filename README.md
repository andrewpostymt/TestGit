# E-Commerce Platform Monorepo

Example monorepo demonstrating a production-scale e-commerce platform with **38 microservices**.

## Services

| Service | Description | Endpoints |
|---------|-------------|-----------|
| order-service | Full order lifecycle management | 255 |
| product-service | Product catalogue and variants | ~25 |
| user-service | User accounts and authentication | ~21 |
| payment-service | Payment processing and refunds | ~20 |
| inventory-service | Stock tracking and warehousing | ~20 |
| subscription-service | Recurring billing and plans | ~20 |
| billing-service | Invoicing and tax management | ~17 |
| analytics-service | Reporting and dashboards | ~20 |
| admin-service | Platform administration | ~25 |
| workflow-service | Business process automation | ~23 |
| … and 28 more | | |

## Structure

```
services/
├── order-service/        # 255 endpoints across 15 resource groups
├── product-service/
├── user-service/
└── … 35 more services
```

## Getting Started

```bash
npm install
npm run build
```
