The similar products carousel helps customers discover products similar to the current product and improve conversion. 

The objective of this assignment is to use the product attribute information available in the dataset and find similar products given a sample product.

Input: Product-id from the data set. This is the product for which similar products have to be identified from the data set.

Output: List of top 10 products that are similar to the current product.


Fields in dataset
Product      ID Unique identifier of the product
Title        Title of the product (compact description of the product)
Image URL    Image of the product
Division     First level classification of the product
Category     Second level classification of the product
Sub Category Third level classification of the product
Article Type Fourth level classification of the product
Offer price  Manufacturer listed price (MRP)
Sale price   Price after deals/discounts
ColorPrimary color of the product
Gender

Library:

pandas
seaborn
matplotlib
scipy.sparse
sklearn.neighbors
nltk
wordcloud  
