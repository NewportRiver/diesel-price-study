# U.S. Economic-Logistics Petroleum Shock Model

## Mathematical Thresholds for Freight Stress, Supply Shortage, Household Affordability, and Systemic Economic Instability, 2026–2030

**Research status:** Deep Research synthesis completed September 19, 2026.

## Executive findings

The central hypothesis is **partly supported**, but the evidence does not support a single national “collapse price” for diesel.

A sustained diesel price of **$12–$14 per gallon would be an extreme trucking-cost shock under 2026 conditions**, yet price by itself does not produce a mathematically defensible national logistics-collapse threshold.

The more defensible critical variable is:

\[
Risk=f(P_d,S,t,C,I,A,R)
\]

where:

- \(P_d\) = diesel price
- \(S\) = physical petroleum-product shortage
- \(t\) = duration
- \(C\) = freight capacity
- \(I\) = inventory availability
- \(A\) = household affordability
- \(R\) = adaptation and cost/rate pass-through

The primary conclusion is:

> **There probably is not a single diesel-price cliff. There is a petroleum-logistics phase boundary.**

The location of that boundary moves substantially with fuel availability, duration, carrier liquidity, inventory cover, household resilience, demand elasticity, and policy/market adaptation.

### Core result

The original **$12–$14/gal** intuition is plausible as part of the phase surface, but not as a standalone threshold.

The central model places the $12–$14 region near systemic-instability conditions when combined with either:

- roughly a **20% effective petroleum-product shortfall lasting 2–3 months**, or
- roughly a **10% shortfall persisting for much of a year**.

With reliable physical fuel availability, $12–$14 diesel produces severe cost and affordability stress, but the research does **not** support labeling it a national logistics-collapse threshold.

## Current empirical anchors

On September 14, 2026, EIA reported a national on-highway diesel average of **$6.285/gal**, up **$2.546/gal from one year earlier**. The West Coast averaged $7.250 and California $8.039. EIA described the national figure as the highest nominal value in its weekly series dating to 1994 and the highest inflation-adjusted level since 2022.

EIA also reported January–August 2026 U.S. distillate production near **5.1 million barrels/day**, the highest since 2019, with refinery utilization near **97%** in the week ending September 11. The simultaneous presence of high domestic refinery activity and tight global distillate conditions demonstrates why price, inventories, refinery utilization, imports, regional distribution, and international refining capacity must be modeled together.

ATRI’s 2026 operational-cost study reported an industry-average truck operating cost of **$2.336/mile in 2025**, of which approximately **$1.854/mile was nonfuel cost**. ATRI also reported extremely thin truckload and refrigerated margins, negative flatbed margins, elevated deadhead, and a significant divergence between smaller fleets cutting equipment spending and fleets above 1,000 trucks increasing procurement.

These facts strengthen the financial-stress portion of the hypothesis while arguing against treating one fuel price as a physical-collapse switch.

## Freight baseline and operating-cost model

Federal Interstate truck rules generally constrain gross combination vehicle weight to **80,000 lb**, subject to axle and bridge-formula limits. Cargo must share that gross limit with tractor, trailer, fuel, driver, and equipment, and many shipments cube out before they weigh out.

There is no single economically meaningful national truck payload. The Census/BTS Commodity Flow Survey separates shipments by mode, distance, shipment weight, geography, and commodity, so a production model should eventually use payload distributions rather than one fixed number.

For scenario analysis, this study uses a representative central payload of **35,000 lb**, with sensitivity cases around 20,000, 30,000, 40,000, and 45,000 lb. A central fuel economy of **7.0 mpg** and a **15% loaded-mile uplift for deadhead/repositioning** are modeling assumptions, not asserted national averages.

For loaded distance \(D\), deadhead factor \(H\), truck efficiency \(\eta\), diesel price \(P_d\), and payload \(W\):

\[
FC=\frac{D(1+H)}{\eta}P_d
\]

\[
C_{lb}=\frac{FC}{W}
\]

\[
C_{lb-mi}=\frac{P_d(1+H)}{\eta W}
\]

Let \(B\) be nonfuel operating cost per all-mile:

\[
C_{truck}=B+\frac{P_d}{\eta}
\]

and productive loaded-mile operating cost:

\[
C_{loaded}=(1+H)\left(B+\frac{P_d}{\eta}\right)
\]

Using ATRI’s observed 2025 nonfuel cost \(B=\$1.854/mile\), 7 mpg, and 15% repositioning:

| Diesel | Fuel $/all-mile | Total $/all-mile | Total $/loaded-mile | Change vs. $6.285 baseline | Fuel cost, 1,000 loaded mi | Fuel cost/lb @ 35,000 lb |
|---:|---:|---:|---:|---:|---:|---:|
| $6.285 | $0.898 | $2.752 | $3.165 | baseline | $1,033 | 2.95¢ |
| $8 | $1.143 | $2.997 | $3.446 | +8.9% | $1,314 | 3.76¢ |
| $10 | $1.429 | $3.283 | $3.775 | +19.3% | $1,643 | 4.69¢ |
| **$12** | **$1.714** | **$3.568** | **$4.104** | **+29.7%** | **$1,971** | **5.63¢** |
| **$14** | **$2.000** | **$3.854** | **$4.432** | **+40.1%** | **$2,300** | **6.57¢** |
| $16 | $2.286 | $4.140 | $4.761 | +50.4% | $2,629 | 7.51¢ |
| $20 | $2.857 | $4.711 | $5.418 | +71.2% | $3,286 | 9.39¢ |

Moving from the September 2026 national average to $14 adds approximately:

\[
\frac{14-6.285}{7}\approx \$1.10
\]

per truck-mile in fuel alone before secondary inflation in tires, maintenance, wages, financing, and equipment.

At $14 diesel over 1,000 loaded miles in the central assumptions, fuel alone costs about **11.5¢/lb** on a 20,000-lb payload but about **5.1¢/lb** at 45,000 lb.

For a 35,000-lb payload, 7 mpg, and 15% repositioning:

| Loaded distance | Fuel $/lb at $12 | Fuel $/lb at $14 |
|---:|---:|---:|
| 250 mi | 1.41¢ | 1.64¢ |
| 500 mi | 2.82¢ | 3.29¢ |
| 750 mi | 4.22¢ | 4.93¢ |
| 1,000 mi | 5.63¢ | 6.57¢ |
| 1,500 mi | 8.45¢ | 9.86¢ |
| 2,000 mi | 11.27¢ | 13.14¢ |
| 2,500 mi | 14.08¢ | 16.43¢ |

## Feedback architecture

The proposed reinforcing loop is economically coherent:

\[
Petroleum\ Shock
\rightarrow Freight\ Cost\uparrow
\rightarrow Delivered\ Cost\uparrow
\rightarrow Household\ Affordability\downarrow
\]

\[
\rightarrow Demand\downarrow
\rightarrow Revenue\downarrow
\rightarrow Firm/Carrier\ Exit\uparrow
\rightarrow Capacity\downarrow
\rightarrow Unit\ Cost\uparrow
\rightarrow Price\uparrow
\]

A second reinforcing pathway works through inventory:

\[
Fuel\ Shortage
\rightarrow Truck\ Availability\downarrow
\rightarrow Replenishment\downarrow
\rightarrow Inventory\downarrow
\]

\[
\rightarrow Scarcity\ Premium\uparrow
\rightarrow Precautionary\ Orders\uparrow
\rightarrow Inventory\downarrow\ further
\]

But the system also contains damping loops:

\[
Price\uparrow
\rightarrow Demand\downarrow
\rightarrow Fuel\ Demand\downarrow
\rightarrow Price\ Pressure\downarrow
\]

and:

\[
Price\uparrow
\rightarrow Freight\ Rate\uparrow
\rightarrow Carrier\ Margin\ Restored
\]

plus substitution, conservation, inventory drawdown, imports, route changes, and supply response.

A compact dynamic price equation is:

\[
\pi_{t+1}
=
\rho\pi_t
+\alpha E_t
+\beta S_t
+\gamma K_t
-\delta Q_t
-\mu A_t
\]

where \(E_t\) is energy-cost shock, \(S_t\) is scarcity, \(K_t\) is capacity destruction, \(Q_t\) is demand destruction, and \(A_t\) is adaptation.

The statement “higher prices create higher prices” becomes self-reinforcing only when the net positive feedback exceeds these stabilizing mechanisms.

## Logistics-Economic Feedback Coefficient

A stronger mathematical form than a simple stress ratio is:

\[
x_{t+1}=F(x_t,z_t)
\]

with transition Jacobian:

\[
J_t=\frac{\partial F}{\partial x}
\]

and:

\[
R_L=\rho(J_t)
\]

where \(\rho(J_t)\) is the spectral radius of the local transition matrix.

Interpretation:

- \(R_L<1\): disturbances tend to decay
- \(R_L\approx1\): disturbances persist
- \(R_L>1\): disturbances can amplify

A $14 diesel price can still exist in a damping regime when fuel is available, rate pass-through is fast, and adaptation is strong. A lower diesel price combined with major shortage, depleted inventories, and weak carrier balance sheets can enter an amplifying regime.

## Carrier capacity, liquidity, and inventory

Carrier capacity can be represented as:

\[
C_{t+1}=C_t-E_t+N_t+R_t
\]

where exits depend on margin, liquidity, utilization, debt, shortage, and duration.

Immediate fuel exposure is:

\[
\Delta c_f=\frac{P_t-P_0}{MPG}
\]

If \(\phi_t\) is the share passed through to customers:

\[
Loss_t\approx Miles_t\Delta c_f(1-\phi_t)
\]

A simple liquidity runway is:

\[
T_{cash}=\frac{Cash\ Buffer}{Daily\ Unrecovered\ Cost}
\]

Public data do not provide a sufficiently standardized national estimate of current cash reserves by owner-operator, sub-10-truck fleet, midsized carrier, and national fleet. Accordingly, the Monte Carlo model uses a broad **15–120 day liquidity-tolerance range** rather than assigning a false national average.

For inventory, if a sector begins with \(K\) days of normal consumption in stock and experiences an effective unreplaced shortfall \(S\):

\[
T_{depletion}\approx\frac{K}{S}
\]

A 14-day inventory buffer with a persistent 20% replenishment shortfall therefore has a mechanical full-depletion horizon near 70 days if demand does not adjust.

## Logistics-Economic Stress Index

For scenario comparison, the study defines:

\[
LESI_t=
0.15F_t+
0.20S_t+
0.20C_t+
0.20I_t+
0.15H_t+
0.10D_t
\]

where:

- \(F\) = fuel-cost stress
- \(S\) = physical-supply stress
- \(C\) = carrier/liquidity stress
- \(I\) = inventory stress
- \(H\) = household-affordability stress
- \(D\) = demand/production stress

These weights are **modeling assumptions**, not empirically estimated structural coefficients.

Decision bands used in this study:

| LESI | Model interpretation |
|---:|---|
| <15 | Manageable / normal-range adaptation |
| 15–30 | Stress |
| 30–50 | Severe stress |
| 50–70 | Systemic-instability risk |
| 70+ | Critical-distribution-failure risk |

These are research bands, not historical legal or governmental definitions.

## Historical calibration

### 1973–1974 Arab oil embargo

The embargo combined export restrictions with production cuts. State Department historical material records oil prices first doubling and then roughly quadrupling, alongside nationwide shortages and the importance of stockpiles as a short-term buffer.

This episode supports three components of the model: physical supply matters, inventories buy time, and price escalation can exceed the first-order transport-cost increase.

### 1978–1980 Iranian Revolution / second oil shock

This Carter-era episode is especially important.

Contemporary U.S. planning documents treated the Iranian shortfall as initially manageable through inventory drawdowns but warned that prolonged curtailed production could interfere with rebuilding stocks for later seasonal peaks.

The same material warned that relatively modest product shortages and rising spot prices could induce households and businesses to hoard, creating a much more serious psychologically amplified shortage.

This supports:

\[
S_{eff}=S_{physical}+S_{behavioral}+S_{distribution}
\]

rather than treating the published national supply deficit as identical to the shortage experienced by end users.

### 2005 Gulf Coast refinery disruptions

GAO documented an extraordinary spike in lost Gulf Coast refinery capacity during the 2005 hurricane disruptions. Unaffected refiners sometimes deferred maintenance to keep supplying the market, illustrating both nonlinear disruption and adaptive response.

### 2021 Colonial Pipeline disruption

The pipeline shutdown demonstrated why geography and distribution must remain separate from total national petroleum supply. Southeastern markets depended on local terminal inventories and alternate transport routes even though petroleum existed elsewhere in the country.

### 2008 freight/petroleum shock

The 2007–2009 period is useful mainly as a falsification warning. Petroleum-price, credit, industrial, demand, housing, and financial shocks overlapped so strongly that the episode should not be treated as a clean petroleum-only estimate of a national tipping coefficient.

## 90-day price-shortage stress surface

Central model LESI at 90 days:

| Diesel | No shortage | 5% | 10% | 20% | 30% |
|---:|---:|---:|---:|---:|---:|
| $8 | 4.0 | 14.3 | 24.0 | 42.2 | 58.0 |
| $10 | 8.7 | 18.9 | 28.6 | 46.7 | 62.5 |
| **$12** | **13.4** | **23.6** | **33.2** | **51.3** | **67.0** |
| **$14** | **18.0** | **28.1** | **37.8** | **55.8** | **71.4** |
| $16 | 22.6 | 32.7 | 42.3 | 60.3 | 74.3 |
| $20 | 31.7 | 41.7 | 51.3 | 68.5 | 79.3 |

This is the key interaction result. A $12 diesel price with normal physical supply is fundamentally different from $12 plus a 20% effective product shortfall.

## Monte Carlo threshold surface

Twenty thousand parameter draws varied truck efficiency, nonfuel cost, inventory cover, pass-through speed, liquidity, behavioral amplification, and adaptation.

For the model’s **systemic-instability threshold \(LESI\ge50\)**:

| Effective shortfall | Duration | Median diesel threshold | Approx. 10th–90th percentile |
|---:|---:|---:|---:|
| 0% | 90 d | generally not reached by $24 | — |
| 5% | 180 d | about $20.50* | about $18–$22.75* |
| 5% | 365 d | about $17.75 | about $15.50–$20.75 |
| 10% | 90 d | about $20.00 | about $17.50–$22.50 |
| 10% | 180 d | about $16.25 | about $14–$19 |
| **10%** | **365 d** | **about $13.00** | **about $11–$15.50** |
| **20%** | **90 d** | **about $12.00** | **about $9.25–$15** |
| 20% | 180 d | about $8.25 | about $4–$11 |
| **30%** | **30 d** | **about $14.50** | **about $11.25–$17.75** |

\*Conditional on runs that crossed the threshold by $24/gal.

Thus the original $12–$14 hypothesis emerges naturally under at least two very different conditions:

\[
\$12\text{–}\$14+\sim20\%\ shortage+\sim90\ days
\]

or:

\[
\$12\text{–}\$14+\sim10\%\ shortage+\sim1\ year
\]

## Time to modeled stress bands

Central parameterization:

| Scenario | Systemic-risk band | Critical-distribution-risk band |
|---|---:|---:|
| $12, normal supply | not reached within 365 d | not reached |
| $14, normal supply | not reached within 365 d | not reached |
| $14 + 10% shortfall | ~244 d | not reached within 365 d |
| **$12 + 20% shortfall** | **~83 d** | ~359 d |
| **$14 + 20% shortfall** | **~63 d** | ~233 d |
| **$12 + 30% shortfall** | **~37 d** | ~106 d |
| **$14 + 30% shortfall** | **~30 d** | ~84 d |
| $16 + 20% shortfall | ~49 d | ~168 d |

These are **model transition estimates**, not predictions that stores empty on a specific day.

The curvature behaves more like:

\[
Risk=aP_d+bS+ct+d(P_dS)+e(St)+f(P_dSt)+...
\]

than a one-dimensional relation such as \(Risk=aP_d\).

## Adaptation sensitivity

For $14 diesel plus a 20% shortfall lasting 90 days:

- central parameterization: **LESI ≈ 55.8**
- strong adaptation: **LESI ≈ 40.4**
- weak adaptation: **LESI ≈ 75.7**

This range demonstrates why one collapse price would be misleading.

## Household affordability

Census reported **2025 real median household income of $87,460** and median **post-tax household income of $76,060**.

A petroleum-stress affordability model should use BLS Consumer Expenditure data by income quintile/decile rather than only the national median.

For income group \(q\):

\[
HAI_q=\frac{Y^{disp}_q}{E^{essential}_q}
\]

After an essential-basket price increase \(\pi_e\):

\[
HAI'_q=\frac{Y^{disp}_q}{E^{essential}_q(1+\pi_e)}
\]

and:

\[
\frac{HAI'_q}{HAI_q}=\frac{1}{1+\pi_e}
\]

A 10% increase in essential costs mechanically reduces this ratio about 9.1%; a 20% increase reduces it about 16.7%, before wages or transfers adjust.

## Multi-stage freight amplification

Petroleum cost may enter a finished good many times:

\[
Raw\ Material
\rightarrow Processor
\rightarrow Manufacturer
\rightarrow Distribution\ Center
\rightarrow Retailer
\rightarrow Consumer
\]

For \(n\) freight stages:

\[
\Delta C_{transport}
=
\sum_{j=1}^{n}
\frac{D_j(1+H_j)}
{\eta_j W_j}
\Delta P_d
\]

This is more realistic than assuming one store-delivery fuel charge represents all petroleum exposure embedded in a finished good.

## Commodity sensitivity

Define:

\[
FS_i=\frac{Transportation\ Cost_i}{Delivered\ Value_i}
\]

A 3.62¢/lb incremental fuel burden may be trivial for pharmaceuticals but significant for low-value heavy goods such as some bulk agricultural, beverage, mineral, construction, and feedstock commodities.

The first-order vulnerability is therefore greatest among **low-value, heavy, long-distance products with poor load utilization and weak modal substitution**.

## Physical shortage versus price

A very high diesel price can, in principle, clear through economic rationing: lower-value activity drops out and fuel flows toward users willing to pay.

A gallon that **does not exist at the required location** cannot be purchased at any price.

Therefore:

\[
Economic\ Rationing \neq Physical\ Rationing
\]

At $14 with full availability, the dominant mechanism is higher freight rates, demand destruction, substitution, and margin reallocation.

At $14 plus a 20% effective shortage, some of the system experiences physical rationing and missed replenishment even where a shipper is willing to pay.

This is why shortage changes the model’s curvature much more than another dollar or two of diesel once prices are already high.

## Threshold matrix

| Diesel | Effective shortage | Duration | Central model condition | Interpretation |
|---:|---:|---:|---|---|
| $12 | 0% | 90 d | LESI 13.4 | Manageable at system level; severe carrier cost shock remains |
| $14 | 0% | 180 d | 21.0 | Stress |
| $20 | 0% | 365 d | 40.7 | Severe stress, not physical-collapse band |
| $12 | 10% | 90 d | 33.2 | Severe |
| $14 | 10% | 180 d | 46.2 | Severe / near systemic boundary |
| $14 | 10% | 365 d | 55.4 | Systemic-instability risk |
| **$12** | **20%** | **90 d** | **51.3** | **Systemic-instability risk** |
| **$14** | **20%** | **90 d** | **55.8** | **Systemic-instability risk** |
| **$14** | **20%** | **180 d** | **66.4** | **High systemic risk** |
| $12 | 30% | 90 d | 67.0 | High systemic / near critical |
| **$14** | **30%** | **90 d** | **71.4** | **Critical-distribution-failure risk band** |
| **$14** | **30%** | **180 d** | **79.5** | **Critical risk** |

A striking implication is that **$20 diesel with normal supply can remain below the modeled systemic boundary while much lower prices with sustained 20–30% shortages can cross it**.

That is the clearest quantitative rejection of a single-price-collapse hypothesis.

## Limitations

No historical dataset identified in this research demonstrates an empirically estimated national bifurcation at exactly $12, $14, or any other retail diesel price.

The LESI bands and weights are research constructs. Monte Carlo intervals are parameter-uncertainty ranges around the model, not statistical confidence intervals estimated from repeated historical U.S. collapse events.

Several variables remain poorly standardized at national scale:

- carrier cash reserves by fleet size
- fuel-surcharge recovery lags by contract type
- commodity-specific inventory cover
- panic-buying elasticity
- commodity-specific freight pass-through
- complete current Class 8 payload distributions
- policy response timing and magnitude

The current model also treats policy response parametrically rather than predicting future emergency actions.

## Final conclusion

The original theory is best reformulated as:

> A petroleum-driven U.S. logistics-instability regime can emerge when the combined gain from fuel cost, physical shortage, inventory depletion, carrier financial losses, and affordability-driven capacity destruction exceeds the damping gain from rate pass-through, demand destruction, substitution, inventory buffers, and supply adaptation.

In local dynamic form:

\[
R_L=\rho(J)>1
\]

is the conceptual tipping criterion.

The research therefore supports placing **$12–$14 diesel on the phase diagram, but not drawing it as a vertical collapse line**.

A stronger statement is:

> **Around $12–$14 diesel, a persistent ~20% effective product shortage can move the modeled system from severe stress toward systemic instability on roughly a two-to-three-month timescale.**

Conversely:

> **$12–$14 diesel with reliable physical supply is economically severe, but the research does not support calling it a national logistics-collapse threshold.**

## Primary source record

- U.S. Energy Information Administration — weekly retail gasoline/diesel prices and September 2026 distillate analysis  
  https://www.eia.gov/petroleum/gasdiesel/  
  https://www.eia.gov/todayinenergy/detail.php?id=68164
- American Transportation Research Institute — 2026 Analysis of the Operational Costs of Trucking  
  https://truckingresearch.org/2026/07/new-atri-report-details-accelerating-costs-and-low-profitability-despite-cuts/
- Census/BTS — 2022 Commodity Flow Survey final tables  
  https://www.census.gov/data/tables/2022/econ/cfs/aff-2022.html
- FHWA — federal truck size and weight framework  
  https://ops.fhwa.dot.gov/
- U.S. Census Bureau — 2025 income, poverty, and health-insurance release  
  https://www.census.gov/newsroom/press-releases/2026/income-poverty-health-insurance-coverage.html
- Bureau of Labor Statistics — Consumer Expenditure Survey tables  
  https://www.bls.gov/cex/tables.htm
- U.S. Department of State — 1973–1974 oil embargo historical record  
  https://history.state.gov/milestones/1969-1976/oil-embargo
- U.S. Department of State — Iranian oil shortfall / historical documents  
  https://history.state.gov/historicaldocuments/frus1969-76v37/d181
- U.S. Department of State — 1977–1980 historical record  
  https://history.state.gov/historicaldocuments/frus1977-80v03/d222
- EIA — Colonial Pipeline disruption analysis  
  https://www.eia.gov/todayinenergy/detail.php?id=47917
- GAO — refinery outage analysis  
  https://www.gao.gov/assets/a282579.html
- Federal Reserve / Federal Reserve History — energy pass-through and Great Inflation historical context  
  https://www.federalreserve.gov/  
  https://www.federalreservehistory.org/
