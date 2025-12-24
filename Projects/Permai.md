# Permai ERP

Internal ERP system for **Permai**, a wholesale distribution company that supplies baby and children's products to retail outlets across Indonesia.

---

## Business Context

### What is Permai?

Permai operates as a wholesale distributor, purchasing products from suppliers and selling them to retail outlets (toko/cabang). The business involves:

- **Suppliers** → Permai (CV) → **Retail Outlets** (Cabang/Toko)
- Multi-tier pricing based on customer grades (B1, B2, B3, B4 - "Bintang" tiers)
- Integration with external accounting systems (Jurnal) and POS systems (MokaPOS)

### Core Business Processes

| Process | Description |
|---------|-------------|
| **Sales Orders** | Outlets place orders → Warehouse confirms quantities → Invoices synced to Jurnal |
| **Return Requests** | Outlets request returns/exchanges → Verified by staff → Synced to Jurnal/MokaPOS |
| **Pricing Management** | Products have tiered prices based on customer grades (B1-B4) |
| **Stock Alerts** | Monitor low stock levels across products |
| **Outlet Management** | Track outlet information, debt balances, and daily revenue |

### Key Entities

- **Outlets/Customers**: Retail stores that purchase from Permai
- **Products**: Baby/children's products with SKUs, pricing, and inventory
- **Sales Orders**: Orders from outlets with line items, quantities, and pricing
- **Return Requests**: Product returns or exchanges from outlets
- **Grades**: Customer tiers (B1-B4) that determine pricing
- **Data Sources**: External systems (Jurnal CV, Jurnal Bizpark, MokaPOS)

### External Integrations

| System | Purpose |
|--------|---------|
| **Jurnal (CV)** | Accounting system for CV entity - purchase/sales invoices |
| **Jurnal (Bizpark)** | Accounting system for Bizpark entity - sales invoices |
| **MokaPOS** | Point-of-sale system for outlet transactions |