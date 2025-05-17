# Trading Platform - API Test Plan

## Tools:
- Java + RestAssured
- JUnit/TestNG
- Maven
- Eclipse
- Git + GitHub

## Features to Test:

### 1. Login
- POST /users
- Validate username/password

### 2. Buy/Sell Order
- POST /orders
- Validate order type, symbol, quantity, price

### 3. Portfolio Fetch
- GET /portfolio
- Returns holdings per user

### 4. Price Lookup
- GET /query?function=GLOBAL_QUOTE&symbol=IBM

### 5. Order History
- GET /history
- Returns past order data

## Test Scenarios:
- Positive & Negative Logins
- Order with invalid data
- Portfolio with no orders
- Lookup invalid symbols
- History filtering by user/date
