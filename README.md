**Demand Forecasting and Inventory Optimization with SARIMAX Model**

The code processes historical demand and inventory data, employs time series analysis techniques to forecast future demand, calculates optimal order quantities, reorder points, safety stock, and evaluates total costs. The goal is to facilitate informed decision-making in inventory management and cost optimization.

1. **Code:** The Python script `demand_inventory_analysis.py` is the core component of this project. It includes data preprocessing, visualization, SARIMAX modeling, demand forecasting, and cost calculations. The code leverages the `pandas`, `matplotlib`, `seaborn`, and `statsmodels` libraries for analysis and visualization.

2. **Sample Data:** The dataset used for analysis is provided in the `demand_inventory.csv` file. 

1. **Set Up Environment:**
   - Make sure you have Python installed on your system.
   - Install required libraries using `pip install pandas numpy matplotlib seaborn statsmodels`.

2. **Run the Code:**
   - Open a terminal or command prompt.
   - Navigate to the directory containing `demand_inventory_analysis.py`.
   - Run the script using `python demand_inventory_analysis.py`.

3. **Interpreting the Results:**
   - The code provides actionable insights into optimal order quantities, reorder points, safety stock, and total costs.
   - Results and analysis are printed in the console.

   - Optimal Order Quantity: The optimal order quantity pertains to the volume of a product to be requested from suppliers as the inventory level reaches a specific threshold. In this instance, a calculated ideal order quantity stands at 138 units.

   - Reorder Point: The reorder point represents the inventory level at which a fresh order must be initiated to restock inventory prior to depletion. In this scenario, a calculated reorder point stands at  137.95 units. This indicates that when inventory reaches or dips below this threshold, it is advisable to place an order for restocking.

   - Safety Stock: Safety stock constitutes the additional inventory retained as a precaution against uncertainties in demand and supply. It serves as a buffer against unforeseen fluctuations in demand or lead time. In this context, a calculated safety stock amounts to 44.57 units. This ensures that a sufficient inventory cushion is in place to accommodate potential variations in demand or lead time.

   - Total Cost: The total cost embodies the cumulative expenses linked to inventory management. In this case, the total cost has been ascertained at approximately 556.9 units, considering the order quantity, reorder point, safety stock, and related costs.

   - Through an examination of these values, one can make informed decisions regarding the extent of inventory to be procured and the timing of orders, thereby ensuring a seamless supply chain and customer satisfaction, while concurrently minimizing expenses.

    This is how you can conduct Demand Forecasting and Inventory Optimization using Python. Demand Forecasting entails predicting the volume and pattern of customer orders, a critical process for businesses to effectively allocate resources, manage inventory, and plan production. Inventory Optimization seeks to strike a balance between maintaining sufficient stock to meet demand without carrying excess inventory that ties up capital and storage space.

4. **Summary:**
    Effective demand forecasting and inventory optimization are vital for businesses to allocate resources efficiently, manage inventory, and plan production. This project demonstrates how the SARIMAX model can be employed to analyze historical data and make informed decisions regarding inventory management.

