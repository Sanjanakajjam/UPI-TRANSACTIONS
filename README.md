# UPI-TRANSACTIONS
1. Project Title / Headline

📊 Digital Payments Insights: UPI Transaction Analytics Dashboard
An interactive and dynamic Power BI dashboard designed to explore UPI transaction patterns across banks, cities, device types, and payment modes for the year 2024—focusing on monthly trends, transaction purposes, and user behavior in India’s digital payments ecosystem.

2. Short Description / Purpose

The UPI Transactions Dashboard provides a detailed, visual analysis of digital payment activity across multiple categories like banks, devices, and cities. It helps uncover transaction trends, balance variations, and payment behavior over time.
This project aims to support financial analysts, digital payment strategists, and business intelligence professionals in understanding the evolution of UPI usage and performance patterns.

3. Tech Stack

The dashboard was built using the following tools and technologies:<br>
• 🧮 Power BI Desktop – Primary platform for interactive data visualization and report creation.<br>
• 🔄 Power Query Editor – Used for data transformation, cleaning, and structuring before modeling.<br>
• 🧠 DAX (Data Analysis Expressions) – For calculated measures such as total balance, monthly averages, and percentage change.<br>
• 🗂 Data Modeling – Established relationships among categorical fields like BankName, City, TransactionType, and Month to allow dynamic cross-filtering.<br>
• 📁 File Format – .pbix for dashboard development and .xlsx for raw data source.<br>
• 🖼 Visualization Export – .png used for dashboard preview and documentation.

4. Data Source

Source: Custom dataset (UPI Transactions.xlsx) created for educational and analytical use.

Description:
The dataset contains UPI transaction data across banks and cities for the year 2024. It includes details about the sender and receiver banks, transaction purposes, payment methods, and demographic insights such as gender and age group.

Column Name	Description
BankNameSent	Bank initiating the transaction
BankNameReceived	Receiving bank name
City	City where transaction occurred
DeviceType	Device used (Mobile/Desktop)
Gender	User gender
AgeGroup	User age category
MerchantName	Merchant involved in transaction
PaymentMethod	UPI/QR/Wallet
Purpose	Transaction purpose (Shopping, Bill Payment, etc.)
TransactionType	Credit or Debit
Month	Month of transaction
Balance	Transaction balance or total amount per month
5. Features / Highlights
• Business Problem

With India’s UPI transactions exceeding billions monthly, banks and analysts need a way to visualize transaction flows and identify growth opportunities.
However, transaction data across multiple attributes (banks, devices, gender, and purpose) can be complex to analyze manually.

Key Questions Answered:

How do UPI transaction balances vary monthly throughout 2024?

Which months recorded peak digital transaction activity?

Which banks and payment methods contribute most to the total transaction value?

What device types are most used for UPI transactions?

• Goal of the Dashboard

To provide an interactive visual tool that:

Displays UPI transaction patterns by month, device, and bank.

Enables users to identify high-volume transaction months and trends.

Supports decision-making for digital finance analysts and marketing teams.

Helps monitor transaction growth across cities and user demographics.

• Walkthrough of Key Visuals

📈 Line Chart – “Balance by Month [Year 2024]”
Displays monthly UPI balance trends using a smooth pink-filled line chart.

January: 8.232K

Peak in June: 8.536K

Steady rise again in December: 8.429K

🎚 Interactive Filters (Slicers)
Allow users to refine insights based on:

BankNameSent

BankNameReceived

City

DeviceType

Gender

AgeGroup

MerchantName

PaymentMethod

Purpose

TransactionType

📊 Chart Toggle Buttons

LineChart Amounts

Column Chart Amounts

Column Chart Balance
These buttons dynamically switch between visuals to compare transaction trends in different formats.

📅 Monthly Balance Visualization
Highlights trends across 12 months—showing seasonal highs and lows.

• Business Impact & Insights

Strategic Insights:

Peak transaction activity in June, suggesting seasonal or festival-linked spikes.

Lowest transaction values in May, followed by recovery in subsequent months.

Consistent transaction growth from October to December, aligning with festive shopping periods.

Usage patterns indicate mobile devices dominate UPI transactions.

Business Applications:

Banks can monitor transaction inflows and identify high-performing periods.

Fintech Analysts can study adoption rates of UPI and digital wallets.

Marketing Teams can plan promotional campaigns around peak transaction months.

Policy Makers can assess digital payment penetration across demographics.

6. Screenshots / Demos
Dashboard Preview
<img width="1913" height="972" alt="Screenshot 2025-11-09 095350" src="https://github.com/user-attachments/assets/f8f56214-10c7-4792-b98e-fd512c422544" />
<img width="1907" height="971" alt="Screenshot 2025-11-09 095553" src="https://github.com/user-attachments/assets/3f3d04c1-4e3e-46b4-a395-51685c063c70" />



