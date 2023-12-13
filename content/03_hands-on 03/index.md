## Hands-on 3 (Lawrence Barratt)
### 1) Creating Your Business Flow
1. Navigate to Apps
1. Find and click on Business Flow
1. Click '+ Business Flow'
1. Select 'Configuration' and give the Business Flow an identifiable name
1. Click on Step 1, and rename the step to 'Deposit'
1. Drop down Events, select ‘com.easytrade.deposit.start
### 2) Adding Subsequent Steps
1. Under the first step, click '+ Add Step'
1. Rename this step to 'Buy'
1. Drop down Events, select ‘com.easytrade.buy.start'
1. Under the second step, click '+ Add Step'
1. Rename this step to 'Sell'
1. Drop down Events, select 'com.easytrade.sell.start'
### 3) Adding Configuration and KPIs
1. At the top, click 'Settings'
1. Change Select event to 'com.easytrade.buy.start'
1. Change select KPI to 'price'
1. Change correrlation ID to 'accountId'
### 4) View the Business Flow in the instructor's environment
