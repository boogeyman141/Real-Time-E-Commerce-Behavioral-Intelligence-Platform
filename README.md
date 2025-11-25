# Real-Time E-Commerce Behavioral Intelligence Platform (RealTime RidePulse style)

## Project scope
Option A+ datasets:
- NYC Taxi trip records (batch)
- NOAA weather (batch)
- GitHub Archive (nested JSON stream)
- Synthetic Kafka nested JSON streams (custom producers)

## Structure
See /docs/architecture.png

## Quickstart
1. Follow Day1-3 scripts in weekly-plan.md
2. Start local Docker (Kafka + Zookeeper + Airflow)
3. Run producers to stream nested JSON to Kafka
