# Smart India Hackathon Workshop
# Date: 11-11-2026
## Reference Number: 26003336
## Name: M Shifa

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution:

FarmBox is an innovative agricultural marketplace designed to connect farmers directly with consumers, retailers, restaurants and bulk buyers. It aims to eliminate unnecessary intermediaries and improve the agricultural supply chain.

Farmers can register on the platform, upload their available crops, specify quantities and set their selling prices. Consumers and bulk buyers can browse products, compare prices and place orders directly with farmers.

FarmBox also introduces smart agricultural vending kiosks where customers can conveniently purchase or collect fresh fruits and vegetables.

Main Features:

1.Direct farmer-to-consumer connections.

2.Farmer and buyer registration.

3.Online crop listing and ordering.

4.Transparent product pricing.

5.AI-based demand forecasting.

6.Smart delivery and route optimization.

7.Digital payments and order tracking.

8.Automated agricultural vending kiosks.

9.Stock and freshness monitoring.

FarmBox addresses the problem of multiple intermediaries by creating a direct connection between farmers and consumers.

Farmers can sell their agricultural products directly to buyers and receive a better share of the selling price. Consumers can purchase products at reasonable prices without paying unnecessary intermediary margins.

The logistics system helps reduce transportation expenses, while AI-based demand forecasting helps farmers understand market requirements and plan their supply.

The uniqueness of FarmBox is the integration of a digital agricultural marketplace with AI technology, smart logistics and physical vending kiosks.

Unlike ordinary online shopping applications, FarmBox focuses on improving the complete agricultural supply chai

## Technical Approach

Technologies to be Used:

1. Raspberry Pi / ESP32: Controls the FarmBox machine.

2. Touchscreen: Displays available products and prices.

3. QR Scanner: Supports QR-based payments.

4. Weight Sensor: Monitors product stock.

5. Temperature Sensor: Monitors storage conditions.

6. Servo Motor: Controls automatic product dispensing.

7. Python: Used for programming the machine.

8. Database: Stores product, stock, and sales details.

Methodology and Implementation:


             ┌───────────────┐
             │     START     │
             └───────┬───────┘
                     ↓
        ┌─────────────────────────┐
        │   Farmer Registration   │
        └───────────┬─────────────┘
                    ↓
        ┌─────────────────────────┐
        │  Collect Fresh Produce  │
        └───────────┬─────────────┘
                    ↓
        ┌─────────────────────────┐
        │  Load Products into     │
        │       FarmBox           │
        └───────────┬─────────────┘
                    ↓
        ┌─────────────────────────┐
        │ Display Products on     │
        │      Touchscreen        │
        └───────────┬─────────────┘
                    ↓
        ┌─────────────────────────┐
        │ Customer Selects        │
        │ Products                │
        └───────────┬─────────────┘
                    ↓
        ┌─────────────────────────┐
        │    Make Payment         │
        │      (UPI / QR)         │
        └───────────┬─────────────┘
                    ↓
        ┌─────────────────────────┐
        │ Automatic Product       │
        │       Dispensing        │
        └───────────┬─────────────┘
                    ↓
        ┌─────────────────────────┐
        │ Update Stock and        │
        │ Monitor Temperature     │
        └───────────┬─────────────┘
                    ↓
        ┌─────────────────────────┐
        │ AI Demand Prediction    │
        │ and Route Optimization  │
        └───────────┬─────────────┘
                    ↓
        ┌─────────────────────────┐
        │   Restock Products      │
        └───────────┬─────────────┘
                    ↓
             ┌───────────────┐
             │      END      │
             └───────────────┘


<img width="1402" height="1122" alt="image" src="https://github.com/user-attachments/assets/fa1bbec2-a79f-46a6-a1cc-c053132f590e" />



## Feasibility and Viability:

FarmBox can be developed using affordable components such as Raspberry Pi, ESP32, sensors, and a touchscreen. A small working prototype can be built to demonstrate automatic product dispensing and stock monitoring.

Challenges and Risks:

1.High initial setup cost.

2.Maintaining the freshness of fruits and vegetables.

3.Regular restocking and machine maintenance.

4.Technical issues with sensors and dispensing mechanisms.

Solutions:

1.Start with a small, low-cost prototype.

2.Use temperature sensors to monitor storage conditions.

3.Maintain regular cleaning and restocking.

4.Test the machine properly before implementation.

## Impact and Benefits:

FarmBox helps farmers sell their products directly to consumers while making fresh fruits and vegetables easily accessible to customers.

Benefits:

1.Economic Benefits: Improves farmers' earnings by reducing intermediaries and offers affordable prices to consumers.

2.Social Benefits: Supports local farmers and connects them directly with customers.

3.Environmental Benefits: Reduces unnecessary transportation and food wastage through better stock management.

4.Technology Benefits: Uses smart sensors, AI-based demand forecasting, and automated dispensing for efficient management.

5.FarmBox aims to create a fair, affordable, and sustainable agricultural supply system.

## Research and References:

1. e-NAM (National Agriculture Market): Information about connecting farmers with buyers, transparent pricing, and online payments.  
   https://www.enam.gov.in/

2. AGMARKNET: Provides agricultural commodity prices and market information.  
   https://agmarknet.gov.in/

3. Ministry of Food Processing Industries: Research on food storage, transportation, and post-harvest losses.  
   https://www.mofpi.gov.in/

4. National Horticulture Board: Information about cold storage and post-harvest management of fruits and vegetables.  
   https://nhb.gov.in/


