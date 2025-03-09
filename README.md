# 📌 **Markov Chains in Real Life: Starbucks Order Simulation**
# 🔹 **Introduction**
This project explores Markov chains by simulating the coffee ordering process at Starbucks. A Markov chain models transitions between different states based on probabilities, with the key assumption that the next state depends only on the current state.

# ❓ Research Question
How long does it typically take to get a coffee at Starbucks? We define three states:

O: Ordering the coffee
M: Coffee is being made (waiting)
L: Leaving with the coffee
🔬 Implementation
One Customer, One Drink

A single customer orders one drink with a normally distributed preparation time.
We simulate waiting times and visualize the distribution.
One Customer, Multiple Drinks

A customer randomly selects a drink from a dataset.
Each drink has a different average preparation time with varying uncertainty.
Multiple Customers, Many Drinks

Multiple customers are served by multiple baristas.
The model keeps track of available baristas and assigns orders dynamically.
# 🛠️ **Tech Stack**
- Python
- NumPy, SciPy, Pandas
- Matplotlib, Seaborn
# 🚀 **Running the Simulation**
- python
- Copy
- Edit 
# 📊 **Results**
- Waiting times follow a probability distribution.
- More complex drinks take longer to prepare.
- Multiple baristas reduce waiting times.
# 📂 **Data Source**
We use the Starbucks Menu Drinks Dataset for realistic drink options and preparation times.
