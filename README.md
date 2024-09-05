# Food_delivery_and_profitability_project
The Food Delivery project is about examining the orders made to a restaurant and determining the profitability of the orders with respect to expenses. I extracted the data cleaned and analyzed it using descriptive statistical methods and causal inference. 
Some of the results include:
* A percentage discount of 10% and 5% provided a higher profit than 15%. Furthermore, higher costs are exhibited in higher percentage discounts
* All payment methods experience refunds, therefore, refunds are not attributed to specific payment methods
* The delivery fee and the payment processing fee are relatively constant across all payment methods
* There is a higher commission of payment by digital wallet which leads to lower profit than the other two payment methods. On average, payments by credit card offer better profit margins followed by Cash on delivery. Furthermore, Digite wallet has a higher commission fee among the two payment methods
* The delivery time by Credit card is the highest among the payment methods yet the company gets the highest average profit from this payment method than the rest.
* Higher discounts are offered for payment by cash and Credit card than Digital Wallets. This move appears to be bearing fruits on the profit
* From the Causal inferences, I found that increasing the treatment *perc_discount* by one unit decreases the average profit by 8.29 and an increase in commission_fee by one unit does not have a causal effect on the profit.

The recommendations include:
* The company should consider offering a discount of 10% and 5% only and abandon 15% discount offer
* The company needs to come up with policies that focus on Credit card payment and Cash on Delivery rather than Digital wallet
* The company needs to revise the delivery time on payments by credit card to tap more profit
* The company should continue offering discounts to cash on delivery and Credit Cards and reduce the same on digital Wallets 
