# Oms-SpringKotlin

Description:
Create an Order Management Service. The service will do following
Read and Update Order data from Idoc
Save Order details
Check inventory for Orders
Create Transport service to fetch transport data
Update status of the delivery

Data Structure:
PRODUCT	 
  	ID
 	NAME
 	DESC
 	CATEGORY
 	VALID FROM
 	VALID TO
 	QTY
PRODUCT_PRICE	 
 	ID
 	PRODUCT_ID
 	AMOUNT
 	CURRENCY
 	VALID FROM
 	VALID TO
ORDER_DETAILS	 
 	ORDER_ID
 	PRODUCT_ID
 	TOTAL PRICE
TRANSPORT	 
 	ID
 	ORDER_ID
 	STAGE_ID
 	STATUS
 	START TIME
 	END_TIME


End Points to Build

1>	Check Product available for specified quantity and valid as of today 
2>	Calculate total price for a product with specified quantity and valid as of today
3>	Get Order by ID
4>	Get transport status by order id
5>	Save Order Data from Order XML
6>	Save Product data from Product Json
