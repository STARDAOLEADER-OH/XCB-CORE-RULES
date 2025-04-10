# XCB Token Core Mechanism

## Issuance
- XCB is issued at 1:1 to USDT, initial supply 100 million.
- Decimal precision: 4 places, rounded on settlement.
- All received fiat is placed into the XCB Credit Reserve Pool.

## Exchange & Circulation
- XCB only circulates within the platform.
- Cannot be withdrawn outside the system.
- Used as primary settlement currency in all internal transactions.

## Buyback Mechanism
- Unlimited buyback at 0.9 USDT.
- Unlimited issuance at 1.0 USDT.
- All buyback funds come from the Credit Reserve Pool.
- Smart contracts auto-adjust fee rate based on buyback pressure.

## Fee Structure
- Base: 0.1% per side (buyer/seller)
- Auction: Buyer 2.5%, Seller 1.5%
- Digital goods: 1%
- All fees 100% on-chain, fully auditable
