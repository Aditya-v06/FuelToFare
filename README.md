# FuelToFare
An Interactive Power BI Dashboard Analyzing the Impact of Crude Oil and Jet Fuel Prices on Airline Ticket Fares (2019–2026)

## Objective
The global airline industry operates in one of the most fuel-intensive sectors of transportation. Jet fuel 
accounts for approximately 20–30% of an airline's total operating expenses, making it the single largest 
variable cost item. When crude oil prices rise or fall, airlines are directly impacted through their jet fuel 
procurement costs — and this impact ultimately reaches passengers in the form of ticket fare changes 
and fuel surcharges.

Between 2019 and 2026, the aviation industry experienced unprecedented volatility. The COVID-19 
pandemic caused jet fuel prices to crash by nearly 70% in March 2020, followed by a sharp recovery and 
geopolitical supply disruptions in 2022 that drove prices to multi-year highs. The Russia-Ukraine conflict 
disrupted global oil supply chains, OPEC production decisions further influenced crude prices, and 
potential Strait of Hormuz disruptions created risk premiums across energy markets. 

This project builds an interactive Power BI dashboard to analyse and visualise the relationship between 
petroleum commodity prices and airline ticket fares across five major airlines, five geographic regions, 
and four route classifications over a seven-year period.

## DAX Measures
1. Average Total Fare
Avg Total Fare = AVERAGE(airline_ticket_prices[total_fare_usd])
2. Average Fuel Surcharge
Avg Fuel Surcharge = AVERAGE(airline_ticket_prices[fuel_surcharge_usd])
3. Average Jet Fuel per Barrel
Avg Jet Fuel Bbl = AVERAGE(market_prices_table[jet_fuel_usd_barrel])
4. Average Brent Crude
Avg Brent Crude = AVERAGE(market_prices_table[brent_crude_usd])
5. Average Load Factor
Avg Load Factor = AVERAGE(airline_ticket_prices[load_factor_pct])
6. Average Fuel Cost
Avg Fuel Cost = AVERAGE(airline_ticket_prices[fuel_cost_pct_opex])

## Output
<img width="1191" height="665" alt="Screenshot 2026-05-25 183926" src="https://github.com/user-attachments/assets/96c60c3d-89d2-4c30-865a-453273bb3994" />
