# Exchange Contract Interface (Draft)

## Function: buyXCB()
- @param amount: USDT amount to spend
- Calculates XCB = amount / 1.0
- Mints and sends XCB to user
- Updates Reserve Pool record

## Function: sellXCB()
- @param amount: XCB to sell
- Calculates USDT = amount * 0.9
- Sends USDT to user from Reserve Pool
- Burns XCB

## Function: adjustFee()
- Based on buyback volume, adjust fee from 0.01% up to 5%
