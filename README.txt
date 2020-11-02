Discount Strategy Analysis on Saks.com and Off5th.com


Research Question:
How do the sale products priced on both wesite? 
Are both sites selling the same products? If not, what is the different and why?

Data Sets
Data set were scraped from saks.com sale section and off5th.com on 10/27/20 and 10/29/20. 
It included products of women's dresses, Men's dress shirts and Men's causual shirts from both sites.
Saks.com data has 4003 rows, after removing 11 rows that failed to extract the original price data, 3989 rows were used in the analysis.
Off5th.com data has 5111 rows, all were included in the analysis.

Data Columns
8 columns were scraped from the websites. 

'website': where the data is from. Values include: 'Saks', 'Off5th'
'brand_name': the brand name of the product
'product_name': the name of the product
'category': the category of the product, values include: 'dresses', 'casual-button-down-shirts', 'dress-shirts'
'department': the department of the product, values include: 'men', 'women', 'women-apparel'
'original_price': product original price, float
'discount_price': product after discount price, float
'discount_amount': marked percentage off (not available on saks.com), float

8 columns were added during the anlysis.

'private_label': whether the brand is privately owned by Saks groups
'brand_positioning': the price point and position of brand, values include: 'Trendy', 'Contemporary', 'Luxury'
'percent_off' = (1-'discount_price'/'original_price')*100, float
'order' = the order of the product on the webpage


Conclusion:

1.Overall, Off5th has a lower average selling price and a higher discount rate than Saks.com sale section
2.The majority of brands on the two sites are the same but each has a proportion of exclusive brands, catering to a different customer group. *Strategically, Saks trying to keep different type of customers on separate sites.
3.Discount is offered at a few preset levels on Saks.com, while on Off5th.com the discount is on a continuous spectrum. 
4.Discount rate of the brands carried by both sites is significantly higher than the exclusive brands on Off5th.com. 

