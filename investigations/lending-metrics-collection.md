## This document represents metrics collected from sourced interviews

| metric | Description | Source
| ----------- | ----------- | --------- | 
| 1_week_loan_client| This metric represents a total count of all celsians who have taken a loan within 1 week of opening an account on celsius | Ashley O'Brien, Marketing |  
|total|shows total market capitalization of the top-125 cryptocurrencies.|Ronald Loh, VIP Lending|
|total2|shows total market capitalization of the top-125 cryptocurrencies, excluding bitcoin|Ronald Loh, VIP Lending|
|total3|shows total market capitalization of the top-125 cryptocurrencies, excluding bitcoin, and others|Ronald Loh, VIP Lending|
|loan_count_activated_by_date| count of loans activated by day | Greg Swanson, BA, Lending| 
|loan_count_liquidated_by_date| count of loans ended by day via liquidation | Greg Swanson, BA, Lending| 
|loan_count_closed_by_date| count of loans ended by day not via liquidation | Greg Swanson, BA, Lending| 
|loan_count_ended_by_date| total count of loans ended by day | Greg Swanson, BA, Lending| 
|asset_price_asset*| current_price of asset* offered by celsius| Greg Swanson, BA, Lending| 
|historic_asset_price_asset*| historic_price of asset* offered by celsius| Greg Swanson, BA, Lending| 
|returning_user|previous loan customer opens new loan by date| Tomer Weiss, Retail Lending PM|
|inbound_wires| total wires inbound by date| Greg Swanson, BA, Lending| 
|outbound_wires| total wires outbound by date| Greg Swanson, BA, Lending| 
|-------------------------------|
## lost_collateral
| metric | Description | Source
| ----------- | ----------- | --------- | 
|lost_collateral|loss of US dollar value from contract collateral due to market downturn|George Rajah, Sys Infra Ass.|. 
adds all client balances(custody,yield,withhold), subtracts locked collateral(could be 1 or 3), turn that into absolute value.   
loan: 547
look `for available_collateral_balance`

|||
