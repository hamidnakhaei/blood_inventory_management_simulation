# Blood Inventory Management Simulation
# Settings
- A blood bank is a facility which collects, tests, processes and stores blood and its components for future use.
- The primary responsibility of any blood bank is to plan blood collection and respond to the demand of blood and its components from patients.
- The main objectives of any blood bank are:
  1. To ensure that blood products are available in sufficient quantities for the patients who need blood transfusion.
  2. To ensure that the wastage of blood products is minimized.
- Blood contains mainly three different kinds of cells
  - red blood cells (RBCs)
  - white blood cells (WBCs)
  - platelets
  - plasma
-  human blood can be classified into several blood groups: \
![](https://github.com/hamidnakhaei/blood_inventory_management_simulation/blob/beb656acfd92d313d387a6cde8bab1ef4bf6b0a1/Fig/1.jpeg)
- Supply chain at the blood bank includes five major steps: collection, separation into components, testing and determination of blood type, storage, and issuing.
- Assumptions
  - The life of the RBCs is 36 days; and blood donation camps are currently held once every 4 days.
  - 70 per cent of the collected blood is separated into components at the blood bank.
  - Whole blood and red blood cells of the same blood type can be given interchangeably
  - On average, 39% of the population has O+ blood type.
  - We only have the April data for the demand for O+ blood type.
  - For the supply, we have data collected from 400 camps, held every 4 days.
  - The current level of shortage and wastage:
    - $X^t_i$: Number of items of age $i$ at the beginning of period $t$, $i$ can take values from 0 to $m-1$; with 0 denotes the freshest
    - $R$: Target level inventory for perishable item
    - $D^t$: Demand during the period $t$
    - $S^t$: Supply during the period $t$ \
![](https://github.com/hamidnakhaei/blood_inventory_management_simulation/blob/beb656acfd92d313d387a6cde8bab1ef4bf6b0a1/Fig/2.jpeg) \
![](https://github.com/hamidnakhaei/blood_inventory_management_simulation/blob/beb656acfd92d313d387a6cde8bab1ef4bf6b0a1/Fig/3.jpeg) \
![](https://github.com/hamidnakhaei/blood_inventory_management_simulation/blob/beb656acfd92d313d387a6cde8bab1ef4bf6b0a1/Fig/4.jpeg)
# Questions
  - What is the long-run level of shortage and wastage of O+ blood at the blood bank?
  - The blood bank management has two options. Using simulation, compare them:
    1. Increase blood collection through advertising and holding larger camps.
    2. Hold camps every 2 days.
  - How can the blood bank improve the shortage and wastage performance?
# Answer
![](https://github.com/hamidnakhaei/blood_inventory_management_simulation/blob/beb656acfd92d313d387a6cde8bab1ef4bf6b0a1/Fig/5.jpeg) \
![](https://github.com/hamidnakhaei/blood_inventory_management_simulation/blob/beb656acfd92d313d387a6cde8bab1ef4bf6b0a1/Fig/6.jpeg) \
Average, Percentage Average, and Total of Wastage and Shortage, holding every four days: \
![](https://github.com/hamidnakhaei/blood_inventory_management_simulation/blob/beb656acfd92d313d387a6cde8bab1ef4bf6b0a1/Fig/7.jpeg) \
Average, Percentage Average, and Total of Wastage and Shortage, holding every two days and target inventory = 110: \
![](https://github.com/hamidnakhaei/blood_inventory_management_simulation/blob/beb656acfd92d313d387a6cde8bab1ef4bf6b0a1/Fig/8.jpeg) \
Average, Percentage Average, and Total of Wastage and Shortage, holding every two days and target inventory = 110: \
![](https://github.com/hamidnakhaei/blood_inventory_management_simulation/blob/beb656acfd92d313d387a6cde8bab1ef4bf6b0a1/Fig/9.jpeg) \
Improvement Strategy: \
![](https://github.com/hamidnakhaei/blood_inventory_management_simulation/blob/beb656acfd92d313d387a6cde8bab1ef4bf6b0a1/Fig/10.jpeg) 
