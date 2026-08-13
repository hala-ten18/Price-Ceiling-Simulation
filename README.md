💰 Price Ceiling Market Simulation

An interactive economic simulation demonstrating how government-imposed price ceilings affect supply, demand, market equilibrium, consumer surplus, producer surplus, shortages, deadweight loss, and black-market activity.

📊 Project Overview

This project was created as an interactive demonstration of the economic effects of price controls.

Users can adjust the price ceiling using an interactive slider and immediately see how the market responds. The simulation updates the supply-and-demand graph, economic metrics, step-by-step calculations, and explanatory text in real time.

A black market option is also available to demonstrate how scarcity created by a binding price ceiling can lead to transactions above the legal price.

🎯 Objectives

The simulation aims to demonstrate:

* Supply and demand relationships
* Market equilibrium
* Binding vs. non-binding price ceilings
* Quantity demanded and quantity supplied
* Shortages caused by price controls
* Consumer surplus
* Producer surplus
* Deadweight loss
* Potential black-market effects
* Economic outcomes for consumers and producers

⚙️ Economic Model

The simulation uses the following linear demand and supply functions.

Demand

Qd = 100 - 10P

Supply

Qs = 10P

The resulting market equilibrium is:

* Equilibrium Price (P₀): $5
* Equilibrium Quantity (Q₀): 50

Price Ceiling

When the price ceiling is above or equal to the equilibrium price, it is non-binding and the market continues to operate at equilibrium.

When the price ceiling is below the equilibrium price, it becomes binding:

Quantity Demanded > Quantity Supplied

This creates a shortage.

Shortage

Shortage = Qd - Qs

Consumer Surplus

For a binding price ceiling, the simulation calculates consumer surplus using:

CS = 1/2 × Qs × (Pmax - Pceiling)

Producer Surplus

PS = 1/2 × Qs × Pceiling

Deadweight Loss

DWL = 1/2 × (Q₀ - Qs) × (P_D(Qs) - Pceiling)

Black-Market Price

When a shortage exists, the simulation estimates the implied black-market price by evaluating the demand curve at the quantity supplied:

P_BM = P_D(Qs)

🖥️ Features

Interactive Price Ceiling

A slider allows the user to change the price ceiling from $0 to $10.

The simulation updates automatically whenever the price changes.

Supply & Demand Graph

The graph displays:

* Demand curve
* Supply curve
* Market equilibrium
* Price ceiling
* Consumer surplus
* Producer surplus
* Deadweight loss
* Shortage area
* Quantity supplied
* Quantity demanded

Economic Impact Metrics

The simulation displays:

* Consumer Surplus
* Producer Surplus
* Deadweight Loss
* Shortage

Step-by-Step Calculations

The simulation provides the formulas and numerical calculations behind the displayed economic metrics, allowing users to see how each result is derived.

Black Market Simulation

Users can enable a black-market scenario to see:

* Estimated black-market price
* Visual representation of black-market activity
* Explanation of how scarcity can create incentives for transactions above the legal price

Educational Visuals

Emojis are used as an additional visual explanation of the effects of the price ceiling:

* 😃 Consumers benefiting from a lower legal price
* 😞 Producers losing revenue
* 😤 Consumers unable to purchase the product
* 💰 Black-market money
* 🤝 Black-market transactions

🛠️ Technologies Used

* HTML5 — page structure
* CSS3 — layout, styling, responsive design, and UI components
* JavaScript — economic calculations, simulation logic, event handling, and dynamic updates
* HTML Canvas API — interactive supply-and-demand graph and economic visualization

🔄 How It Works

User changes price ceiling
          ↓
JavaScript reads new price
          ↓
Quantity demanded & supplied are calculated
          ↓
Shortage is determined
          ↓
Economic metrics are calculated
          ↓
Graph is redrawn
          ↓
Explanations & calculations are updated

▶️ How to Run

No external libraries or installation are required.

Option 1 — Open Locally

1. Clone the repository:

git clone https://github.com/hala-ten18/Price-Ceiling-Simulation.git

2. Open the project folder.
3. Open index.html in a web browser.

Option 2 — GitHub Pages

The project can also be hosted using GitHub Pages, allowing the simulation to be accessed directly through a browser.

📁 Project Structure

Price-Ceiling-Simulation/
│
└── index.html

The project is currently contained in a single HTML file, which includes the HTML structure, CSS styling, and JavaScript simulation logic.

💡 Example

Suppose the price ceiling is set to $3.

The model calculates:

Quantity Demanded

Qd = 100 - 10(3)

Qd = 70

Quantity Supplied

Qs = 10(3)

Qs = 30

Shortage

Shortage = 70 - 30

Shortage = 40 units

The simulation then updates the graph and economic metrics to reflect the resulting shortage.

🎓 Academic Context

This project was developed as an interactive demonstration of concepts from economics, particularly the effects of government price controls on market outcomes.

It combines economic theory with interactive web development to make abstract supply-and-demand concepts easier to visualize and explore.

📌 Skills Demonstrated

* Economic modeling
* Supply and demand analysis
* Quantitative calculations
* Interactive data visualization
* JavaScript programming
* HTML5 Canvas
* Responsive web design
* User interface development
* Translating economic theory into an interactive simulation
* Data-driven visual storytelling

⚠️ Disclaimer

This simulation uses simplified linear supply and demand functions for educational purposes. Real-world markets involve additional factors and may not behave according to these simplified assumptions.
