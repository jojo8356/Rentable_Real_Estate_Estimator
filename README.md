# Rentable_Real_Estate_Estimator

1. The user is prompted to enter the following information:

  - The purchase price of the property (purchase_price).
  - The monthly rent that the user can receive (monthly_rent).
  - The expected rental duration in months (rental_duration).
  - Monthly additional costs, such as taxes and insurance (additional costs).
  - The profit is calculated by subtracting the monthly additional costs from the monthly rent (profit = monthly_rent -              additional_costs).

2. Profitability is calculated by multiplying the annual profit by 12 to obtain the annual profit (profit * 12), then dividing this annual profit by the purchase price of the good (purchase_price). The result is then multiplied by 100 to obtain a percentage (profitability = round(profit * 12 / purchase_price * 100)).

3. A condition is used to determine whether the asset is profitable. The good is considered profitable if the profit is greater than zero and if the profitability is greater than 5%. In this case, a message is displayed indicating the expected profit and profitability. Otherwise, a message indicating the expected loss and profitability is displayed.
