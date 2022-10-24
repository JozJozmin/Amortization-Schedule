# Amortization-Schedule
Creating amortization schedule for both fixed and adjustable rate mortgage(ARM)
## Scenario ##
You have 3 different mortgages:
1. A 30-year fixed rate at 4%. The loan will amortize over 30 years.<br>
   The 30-year mortgage should have 361 rows: first row is time = 0, then 1 row per month until month 360 = 30 years. The unpaid principal balance, or UPB, column should    be $1,000,000 million at the beginning, and 0 at the end. Be sure to add the total interest paid.<br>

2. A 20-year fixed rate at 2.5%. The loan will amortize over 20 years.<br>
   The 20-year mortgage should have the same columns, but only 20*12 + 1 = 241 rows.<br>

3. A 7-1 Adjustable Rate Mortgage (ARM) that varies according to rates. The loan will amortize over 20 years.<br>
   The 7-1 ARM should have 361 rows (same as 30-year mortgage), but the interest rate will (potentially) change every 6 months.<br>

a). Build an amortization schedule in Google Sheets, showing the month number, fixed payment amount, principal paydown, interest applied, and new principal balance.<br>
b). Create a Jupyter notebook that shows the mortgage problem solved in Python 

