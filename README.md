# Sharpmonie_Fintech_Dataset_2023

This Python project, hosted on GitHub, focuses on the OLTP (Online Transaction Processing) activities of SharpMonie, a fintech platform. Users can seamlessly conduct various financial transactions through the SharpMonie app and associated services. The project includes functionalities such as mobile recharge, bill payments, funds transfer, peer-to-peer transactions, and more.

## Project Repository
[Python-WhatsApp GitHub Repository](https://github.com/joshua-dada-mayowa/Sharpmonie_Fintech_Dataset_2023)

## Documentation

### 1. Overview
SharpMonie's OLTP activities form the core of its operational model, providing users with a wide range of financial services and interactions.

### 2. OLTP Activities
Here is an overview of SharpMonie's OLTP activities:
- Mobile Recharge and Data Purchase
- Bill Payments
- Funds Transfer
- Peer-to-Peer Transactions
- Betting Account Funding
- Withdrawal
- Agent Banking Services
  - Independent Agents
  - Super Agents
- Promo and Discounts
- Transaction Processing
- POS Operations
- Record Keeping

### 3. Data Dictionary

#### 3.1 Table: cards
- `CardID` (INT): Unique identifier for each card.
- `Types` (VARCHAR(50)): Denotes the type of the card (debit or credit).
- `Networks` (VARCHAR(50)): Specifies the network associated with the card.
- `Methods` (VARCHAR(50)): Indicates the methods supported by the card.

#### 3.2 Table: lgas
- `LGAID` (INT): Unique identifier for each Local Government Area (LGA).
- `LGA` (VARCHAR(50)): Name of the Local Government Area.
- `StateID` (INT): Foreign key linking to the states table.

#### 3.3 Table: states
- `StateID` (INT): Unique identifier for each state.
- `States` (VARCHAR(50)): Name of the state.

... (similar documentation for other tables)

### 4. Project Files
- **Documentation.pdf**: Detailed documentation for the project.
- **Sample_Data (2).ipynb**: Jupyter notebook with sample data.
- **SharpMonie.ipynb**: Jupyter notebook for the SharpMonie project.
- **dataset.ipynb**: Jupyter notebook for dataset operations.
- **merge.ipynb**: Jupyter notebook for merging operations.
- **sharpmonieOLTP.rar**: Archive file, potentially containing additional resources.

### 5. Version History
- **First Commit**: Initial project setup (2 months ago).

## Getting Started
To explore the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/joshua-dada-mayowa/Sharpmonie_Fintech_Dataset_2023.git
   ```

2. Open the Jupyter notebooks using your preferred environment.

3. Refer to the `Documentation.pdf` for in-depth details about the project, including the data dictionary and usage instructions.

Feel free to explore, contribute, or use the project for your own purposes!
