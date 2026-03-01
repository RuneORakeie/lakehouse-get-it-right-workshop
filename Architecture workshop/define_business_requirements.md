World Wide Importers (WWI) Use Case

World Wide Importers (WWI) is a mid-sized importer and wholesaler that buys products from global suppliers and sells to business customers (retailers and corporate accounts).

WWI operates a central HQ with finance and sales, plus one or more distribution warehouses that pick/pack/ship orders.

WWI competes on availability, fast delivery, and competitive pricing, but margins are under pressure due to fluctuating supplier costs and freight variability.
Current Challenges

WWI's systems produce a lot of operational data (orders, invoices, deliveries, stock movements, purchasing, customers, suppliers), but leaders don't trust the numbers because:

    Reporting is slow
    Definitions differ by department
    Operational teams can't see issues early enough to act

Strategic Objective

Build a best-practice lakehouse that becomes the "single place" for reliable operational + financial analytics, powering Power BI and enabling future ML/forecasting and near-real-time exception handling.
Personas & Requirements
1. Mia – CEO / Managing Director

Goals:

    Grow revenue without sacrificing margin
    Improve customer experience (availability + on-time delivery)
    Make decisions faster with fewer "data debates"

Challenges:

    Conflicting KPIs across functions (Sales vs Finance vs Operations)
    Weekly/monthly reporting lag; can't see trend breaks early

Needs from the lakehouse:

    Executive scorecard with consistent KPI definitions
    Drill-through from company KPIs → region/customer/product → root causes
    Trust: lineage + data quality signals

2. Noah – CFO / Finance Controller

Goals:

    Close faster; reduce manual reconciliations
    Understand margin erosion (cost changes, discounts, returns, freight)
    Improve cash flow forecasting

Challenges:

    Multiple versions of "revenue" and "cost"
    Late postings and incomplete master data create mismatches

Needs:

    Curated "gold" finance-ready tables (invoices, payments, cost components)
    Auditability: where each number comes from (lineage)
    Governed access to sensitive fields (customer details, pricing)

3. Sara – Head of Sales

Goals:

    Hit targets; improve win rate and retention
    Identify customers at risk (late deliveries, stock-outs, price sensitivity)

Challenges:

    Sales team can't see stock availability and delivery performance reliably
    Forecasting is gut-feel; limited insight into seasonality and customer behavior

Needs:

    Customer 360: orders + delivery performance + returns + profitability
    Self-serve segmentation with guardrails (certified datasets)
    Near-real-time alerts: "key customer order delayed" / "item at risk of stock-out"

4. Omar – Warehouse & Logistics Manager

Goals:

    Improve OTIF (On-Time, In-Full)
    Reduce picking/packing bottlenecks
    Optimize inventory (avoid stock-outs AND excess stock)

Challenges:

    Reactive firefighting; data arrives too late
    No single view of demand vs on-hand vs inbound purchase orders

Needs:

    Operational dashboards: backlog, pick rates, exceptions, delivery delays
    Inventory health metrics: days of cover, slow movers, shrinkage signals
    Reliable master data for products/locations

5. Priya – Procurement Manager

Goals:

    Reduce supplier lead time variability and cost
    Improve fill rates and negotiate better terms

Challenges:

    Supplier performance tracked manually
    Hard to quantify impact of late/incomplete shipments on revenue and service levels

Needs:

    Supplier scorecards (lead time, fill rate, cost variance)
    Demand signals and reorder recommendations (future-ready)
    Data products combining purchasing + inventory + sales

6. Elena – Customer Service Lead

Goals:

    Reduce "where is my order?" calls
    Provide consistent answers; improve satisfaction

Challenges:

    Must query multiple systems; answers differ depending on who you ask
    No standardized "order status" across channels

Needs:

    Unified order lifecycle view (order → pick → ship → invoice)
    Exception queue powered by data (late, partial, wrong address, etc.)
