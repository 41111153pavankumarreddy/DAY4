create tuples
mens_heights = ("5.2","6.4","4.5","6.0","5.0",)
print(mens_heights)
type(mens_heights)
('5.2', '6.4', '4.5', '6.0', '5.0')
tuple
sorting the tuple()
stock_prices = (66,55,15,22,85,25.0,66.9)
sorted(stock_prices)
[15, 22, 25.0, 55, 66, 66.9, 85]
stock_prices = (66,55,15,22,85,25.0,66.9)
sorted(stock_prices, reverse = True)
​[85, 66.9, 66, 55, 25.0, 22, 15]
repeating the tuple elements
orders_received = ("biryani","coke","water")
n = 3
repeated_tuple = orders_received * n
print(repeated_tuple)
('biryani', 'coke', 'water', 'biryani', 'coke', 'water', 'biryani', 'coke', 'water')
dictionary
books = {"Into to Machine Learning":40,
        "Big Data - Hadoop":45,
         "Spark - The Definitive Guide":67,
         "Data Science using Python":55}
print(books)
{'Into to Machine Learning': 40, 'Big Data - Hadoop': 45, 'Spark - The Definitive Guide': 67, 'Data Science using Python': 55}
removing an element
books = {"Into to Machine Learning":40,
        "Big Data - Hadoop":45,
         "Spark - The Definitive Guide":67,
         "Learn Java":67,
         "Data Science using Python":55}
del books["Learn Java"]
print(books)
{'Into to Machine Learning': 40, 'Big Data - Hadoop': 45, 'Spark - The Definitive Guide': 67, 'Data Science using Python': 55}
items_purchased = {'Sanitizer':4,'Hangers set':7, 'Glass':5}
len(items_purchased)
3
str(items_purchased)
"{'Sanitizer': 4, 'Hangers set': 7, 'Glass': 5}"
type(items_purchased)
dict
items_purchased = {'Sanitizer': 4, 'Hangers set': 7, 'Glass': 5}
items_purchased.keys()                   
dict_keys(['Sanitizer', 'Hangers set', 'Glass'])
items_purchased.values()
dict_values([4, 7, 5])
items_purchased.items()
dict_items([('Sanitizer', 4), ('Hangers set', 7), ('Glass', 5)])
items_purchased
items_purchased = {'Sanitizer':4,'Hangers set':7, 'Glass':5}
items_purchased.clear()
items_purchased
{}
items_purchased = {'Sanitizer':4,'Hangers set':7, 'Glass':5}
purchase_price = items_purchased.copy()
purchase_price
​
{'Sanitizer': 4, 'Hangers set': 7, 'Glass': 5}
items_purchased = {'Sanitizer': 4, 'Hangers set': 7, 'Glass': 5}
print("Amount to be paid:",items_purchased.get("Sanitizer"))
Amount to be paid: 4
items_purchased = {'Sanitizer': 4, 'Hangers set': 7, 'Glass': 5}
print("Amount to be paid:",items_purchased.get("Powder"))
Amount to be paid: None_purchased
items_purchased = {'Sanitizer': 4, 'Hangers set': 7, 'Glass': 5}
items_purchased.setdefault("Powder",5.2)
items_purchased
{'Sanitizer': 4, 'Hangers set': 7, 'Glass': 5, 'Powder': 5.2}
tuple = ('cumbum','prakasam','andhra pradesh')
dict1 = dict.fromkeys(tuple)
print("dictionary :", dict1)
dict2 = dict.fromkeys(tuple,5)
print ('updated dictionary :', dict2)
dictionary : {'cumbum': None, 'prakasam': None, 'andhra pradesh': None}
updated dictionary : {'cumbum': 5, 'prakasam': 5, 'andhra pradesh': 5}
items_purchased = {'Sanitizer': 4, 'Hangers set': 7, 'Glass': 5, 'Powder': 5.2}
items_purchased = {'Sanitizer': 4, 'Hangers set': 7, 'Glass': 5, 'Powder': 5.2}
items_purchased["Hangers set"] = 5
print("items_purchased:",items_purchased)
items_purchased: {'Sanitizer': 4, 'Hangers set': 5, 'Glass': 5, 'Powder': 5.2}
items_purchased = {'Sanitizer': 4, 'Hangers set': 7, 'Glass': 5, 'Powder': 5.2}
del items_purchased["Hangers set"]
print("items_purchased:",items_purchased)
items_purchased: {'Sanitizer': 4, 'Glass': 5, 'Powder': 5.2}
​
