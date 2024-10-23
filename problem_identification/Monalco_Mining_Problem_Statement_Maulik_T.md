# Monalco Mining Problem Statement \[Maulik Trivedi\]

## Problem Statement

How can Monalco Mining reduce its operational cost by 20% in 1 year by streamlining usage and maintenance of mining assets without compromising the assets or worker safety?

## Problem Context

Monalco Mining had ramped up its CAPEX expenditure when iron ores were priced at roughly $110 per ton to meet with the market demand. However, increased market supply has put a downward pressure on the price of iron ore which is roughly averaging around $55 per ton of iron ore. With Monalco Mining’s break even at $50 per ton of iron ore, they urgently need to reduce their operational cost to avoid any impact on business profitability.

## Success Criteria

Clear set of action items to test that will reduce the Operational cost of mining assets by 20% within 1 year.

## Scope for Solution Space

* Reduce Ore Crusher maintenance events.  
* Rationalize ore production rate with respect to the average ore price.
* Rationalize the usage of mining assets with respect to wear.  
* Repurpose/Liquidate excess assets.

## Constraint for Solution Space

* Ore crushers are required to go through one maintenance event after they process 50,000 tonnes of iron ore as per OEM recommendation.
* The company needs to maintain a base level of production rate to maintain profitability.

## Stakeholders

* Reliability Engineer: Chanel Adams  
* Asset Integrity Manager: Jonas Richards  
* Maintenance SMEs: Bruce Banner, Tara Starr  
* Principal Maintenance: Jane Steere  
* Change Manager: Fargo Williams
* Chief Financial Officier

## Key Data Sources

Primary datasources:
* Data Historian: This dataset includes various metrics related to the ore crushers: vibrations, temperature, humidity, and quantity of iron ore processed.
* Ellipse: This data source includes the information on previous work orders that were raised for the equipment maintenances before transition to SAP.
* SAP: This is the most up-to-date source of information on the equipment logs and work order requests that have been raised for the maintenance of the ore crushers and other equipments.

Secondary datasources:
* T3000 DCS: This component streams raw data on vibrations, temperature, and humidity of the ore crushers to Data Historian.
* Ore Crusher System: This includes a high-level process map of how the Ore Crusher System works for individual ore crusher models.