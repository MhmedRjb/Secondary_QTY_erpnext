# Quantity Tracking System for Inventory Management
This system addresses the need to track quantities of items, especially in industries where products like cheese lose weight over time. The primary purpose is to maintain accurate inventory records and prevent discrepancies or potential theft.

### Problem Statement
- **Weight Fluctuations:** Certain items, such as cheese, may lose weight gradually, leading to discrepancies between actual weight and recorded weight in inventory.
- **Risk of Mismanagement or Theft:** Relying solely on recorded weight can create opportunities for mismanagement or theft, as it might not accurately reflect the actual quantity of items in stock.

### Mismanagement Scenario 
In a warehouse, we have 100 wheels of Romy cheese. These typically experience weight loss ranging from 4% to 10% due to various factors like raw material quality, weather, and storage conditions.

Let's calculate:
100 Cheese Wheels * 13.5 kg (average weight) = 1350 kg.
Assuming a loss of 4% to 10% (54 kg - 135 kg), the difference amounts to 81 kg, which equals approximately 4 to 5 cheese wheels. This represents the potential loss during the production phase.
The variability in weight loss, ranging from 4% to 10%, could create confusion. For instance, the person in charge of inventory might inadvertently claim a 10% loss when, in reality, the actual loss is only 4%. This discrepancy could result in inaccuracies in the recorded inventory.

During the sales process, there's typically an insignificant loss, approximately around 0.05%, which is considered acceptable. so no worry in sales pahse

## Solution Overview
- Separate Quantity Tracking: Implementing a secondary method to track the quantity of items apart from their weight ensures more accurate inventory management.

## for developer who face the same issue 
- this project will be not bad as a fast soultion but it is need a lot of work 
  - there is cusotme fields in all fields effect in stock ledger
  - there is tow reports one for all transection and other for balance only
  - in my way i will make it more Integrated  



## License
This project is licensed under the MIT License.


