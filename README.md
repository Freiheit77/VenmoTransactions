# VenmoTransactions

## Background
Venmo is a peer-to-peer (P2P) mobile payment app owned by PayPal. The Venmo app allows its users to exchange money with just a click of a button. In the fourth quarter of 2019, Venmo’s net payment volume amounted to 29 billion U.S. dollars, representing a 56 percent year-on-year growth, and its user-base had more than 40 million active accounts . What made Venmo so popular in the US is its social flavor; users are required to accompany their transactions with a message describing what the transaction was about. This social twist has allowed Venmo to transform financial transactions into sharing experiences.

## Objective
    1. Evaluate user connection density and user sharing experience on Venmo
    2. Predict payment trends and user activeness 

## Data Description
1. The dataset contains over 7 million transaction records. 
2. Features: 
    - user1: payer
    - user2: receiver
    - transaction_type
    - datetime
    - description
    - is_business
    - story_id

## Analytics
1. Text analytics on "description" feature
2. Social network analytics 
3. Build static and dynamic user profile with lifetime from 0 to 12
4. RF predictive framework (transaction recency and frequency)

## Findings
    1. The "Food", "Activity", and "People" are the top 3 emoji categories with the most relevant transaction records.
    2. There are 3018657 unique social network node and 5534634 edges. 
    3. After lifetime 10, the means for all categories' spendings tend to be stable and close to zero. 
