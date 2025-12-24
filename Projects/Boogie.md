# Boogie Apparel ERP

Internal Enterprise Resource Planning system for **Boogie Apparel**, a garment manufacturing company based in Indonesia. This system streamlines the end-to-end workflow from customer quotations to production delivery.

## Business Context

Boogie Apparel is a B2B garment manufacturer specializing in custom apparel production. The company handles:
- Custom garment orders from corporate clients
- Sample development and approval workflows
- Mass production with quality control
- Multi-stage delivery and payment tracking

### Key Business Processes

1. **Sales Pipeline**: Account Executives (AE) manage customer relationships, create quotations (SPH), and secure purchase orders
2. **Sample Development**: Sample dealing process with internal/external (mitra) production, customer approval cycles
3. **Mass Production**: Production planning, SKP (Surat Konfirmasi Produksi) management, timeline tracking
4. **Quality Control**: Multi-stage QC (Inline, Embellishment, Final) with photo documentation
5. **Delivery & Payment**: Shipping coordination, payment milestones (DP, pelunasan)

## Product Overview

### Core Modules

| Module | Description |
|--------|-------------|
| **Projects** | Central hub linking all operations - SPH, PO, samples, production, shipping |
| **Customers** | Customer master data with account management and PIC (Person in Charge) contacts |
| **SPH Management** | Internal quotations (from MD) and customer-facing quotations (revisable) |
| **PO Management** | Purchase order tracking with payment terms, DP, and completion status |
| **Sample Dealing** | Sample production workflow with SKP tracking and approval cards |
| **Production** | Mass production sessions with PPM dates, mitra assignments, and deadlines |
| **Quality Control** | Integrated QC phases with photo evidence and pass/revisi/hold status |
| **Analytics** | Sales performance dashboards, AE targets, and production metrics |