# Week-3-Assignment
Python programming

#Source code:
‎#Product code / Set price of product
‎if product_code == "A":
‎	price = 60
‎elif product_code == "B":
‎	price = 70
‎elif product_code == "C":
‎	price = 90
‎
‎#Set discounts
‎if 1 <= number_unit < 10:
‎    discount = 0
‎elif 100 <= number_unit < 40:
‎    discount = 0.1
‎elif number_unit > 100:
‎    discount = 0.25
‎else:
‎    discount = 0.2
‎
‎#create function
‎def total_price(cost, disc, num):
‎	disc_price = cost - (cost*disc)
‎	final_price = disc_price * num
‎	return final_price
‎	
‎#Call the function
‎print(total_price(price, discount, number_unit))
‎
‎
