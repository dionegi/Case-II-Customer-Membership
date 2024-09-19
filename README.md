# Customer Membership Program

## 1. Case Description

PacCommerce is a new e-commerce service that has tier membership feature:
- **Silver**
- **Gold**
- **Platinum**

Each tier membership has the benefit provided in this table: 

| **Membership** | **Discount** |                     **Another Benefit**                     |
|:--------------:|:------------:|:-----------------------------------------------------------:|
|    Platinum    |      15%     | Benefit Silver + Gold + Voucher Liburan + Cashback max. 30% |
|      Gold      |      10%     | Benefit Silver + Voucher Ojek Online                        |
|     Silver     |      8%      | Voucher Makanan                                             |

Each tier membership has also the requirements:

| **Membership** | **Monthly Expense (juta)** | **Monthly Income (juta)** |
|:--------------:|:--------------------------:|:-------------------------:|
|    Platinum    |              8             | 15                        |
|      Gold      |              6             | 10                        |
|     Silver     |              5             | 7                         |


## 2. Features Requirement

- Show benefit and price of each tier membership
- Show requirements for each tier membership
- Predict membership for user based on their monthly expense and monthly income
- Update user data after predicting membership
- Calculate final price and discount based on their membership

## 3. Data

The user data is dictionary type containing:
- Username
- Membership (Platinum, Gold, Silver)
