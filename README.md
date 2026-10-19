# Green-Foundry-Transition-Model
A python-based simulation and Monte-Carlo risk assessment evaluating the financial and environmental viability of industrial decarbonization pathways for a fictional mid-sized German metal parts manufacturer

**The Problem:** How can a manufacturer reduce Scope 1 and 2 emissions by 40% by 2035 without compromising financial stability?

**Methodology:**

- Baseline carbon accounting using public German emission factors.

- Scenario modelling (Cautious Observer/BAU, Efficiency Seeker/Low-Cost, Green Foundry/Capital Investment).

- 500-iteration Monte Carlo simulation to test for uncertainty in energy prices, grid decarbonization, and solar yield.

- Total Cost of Ownership (TCO) and CAPEX/OPEX financial modeling.

**Key Findings:**

- Doing nothing increases emissions by 2%.

- The "Green Foundry" investment strategy has an 81.2% probability of hitting the 40% reduction target.

- The project demonstrates that industrial decarbonisation is not only technically feasible but also financially viable when approached with a carefully designed combination of renewable generation, electrification, and operational efficiency. The Green Foundry Transition Model provides a template for other mid-sized manufacturers who seek to reduce their carbon footprint while improving their financial performance.

Tools Used: Python (NumPy, Pandas, SciPy, Matplotlib).

**Data Sources & Benchmarks**

To ensure the simulation is grounded in reality, all baseline inputs are sourced from public, verifiable databases:

- Grid Emission Factor (2025): 0.344 kg CO₂/kWh. Source: German Environment Agency (UBA)

- Natural Gas Emission Factor: 0.201 kg CO₂/kWh. Source: UK Government (DEFRA) 2025 Conversion Factors.

- Industrial Electricity Price (2025): €0.183/kWh. Source: Statista - German Industrial Energy Prices The average 2024 industrial price for small/medium enterprises in Germany, from the German Association of Energy and Water Industries (BDEW). Source: IWR (2024).
Sources: Gas pricing sourced from the VEA via energate messenger. Electricity pricing sourced from the German Federal Network Agency market data archive via the SMARD Industrial Electricity Report. https://www.smard.de/page/en/topic-article/5892/216044/industrial-electricity-price-trends


- Industrial Gas Price (2025): €0.082/kWh. Source: GlobalPetrolPrices, energate messenger (2024) Average for mid-sized industrial accounts, excluding VAT/Gas Tax.


- Solar PV Yield: 900 kWh/kWp. Source: Fraunhofer ISE benchmark. EWI, University of Cologne (2026).
