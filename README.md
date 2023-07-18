# Project 1 Revisited

 
## Linear Regression


![download](https://github.com/Luz-Dobbins/week17-Project-1-Revisited/assets/123646377/50535278-44c2-4c8d-a402-21943c5c65b8)



### The coefficients show that the sale of items is dependent on the store type with supermarkets having positive coefficients and grocery store type having a negative effect on sales. The outlet size is the third feature of sales amounts.


## Decision Tree


![download](https://github.com/Luz-Dobbins/week17-Project-1-Revisited/assets/123646377/a3aa34ae-5aa6-4b31-8c7c-4a5ec42f8684)



### The decision tree has a major importance of Item_MRP which after being informed of what it means, I do agree that individuals will look at a price and decide on purchasing or not. Grocery store types are also an important feature with Item_visibility, supermarket types, and item weight following right behind.

# Global Explanation

## Shap Bar Plot


![download](https://github.com/Luz-Dobbins/week17-Project-1-Revisited/assets/123646377/3afdf4cd-0199-44b5-803f-a563fa9b5ea1)


### Both grafts show the same important features which makes sense.
- The Price of an item is important when we buy something, be it food or home goods. I like to stay within budget and am always looking for a great deal.
- Grocery Stores have always made more money than just clothing outlets. That is why Walmart opened Super Walmarts They have more people buying clothes and electronics now that they are in the same building as grocery stores. We are one shop-and-go people.
- Item visibility is highly important especially when individuals are in a hurry and buy the first thing they. The sweet spot for item placement is at eye level and that is also why the pricier items are there.



## Shay Dot Plot

![download](https://github.com/Luz-Dobbins/week17-Project-1-Revisited/assets/123646377/f9283477-6eb0-4d55-b99f-2a412cd2fc29)


### The most important features are Item_MRP, Grocery/ Supermarket type stores, Item_Visibility, and Item_Weight.
- Pricing on items can cause the product not to sell as well and we would need to have sales just to get the quantity on hand down.
- Grocery will always be needed and putting it all together in supermarkets is a great way to get items sold, that would usually stay on the shift for longer. It improves profit and supermarkets are the new wave of the future.
- The visibility of an item has a lot to do with the probability of it selling. This affects all revenue and profit of a business. We always place higher-priced items at eye level and shoppers usually go for them as soon as they hit the aisle.
- The Item weight carries an even more difficult problem because you need to develop a way of placement when products need to be on a pallet or in a tall aisle. These are great items to put into the end of an aisle and if space permits to place in front of the store. I would take notice as I enter the store and purchase it on my way out. Making something that weights more sell is a great way of increasing profit and you don't have to carry a lot in stock because of storage.

# Local Explanation

## Lime

### Max Item_visibility

![image](https://github.com/Luz-Dobbins/week17-Project-1-Revisited/assets/123646377/08c3284d-9db8-4240-8ab2-57c25ef02476)


### Min Item_Visibility

![image](https://github.com/Luz-Dobbins/week17-Project-1-Revisited/assets/123646377/53afb151-59bc-4817-b8c9-bea7a30d9c2a)


### The Lime Explainer has the Item_MRP as the biggest impact of all the other features, with a .64% factor of impact on the sales of the stores. I think the company to look to out source more budget-friendly options. You can see with more visibility a product sells better with less visibility the item has more negatives going on in the Lime Explorer

## Force Plot

### Lineart Regression Force Plot

![image](https://github.com/Luz-Dobbins/week17-Project-1-Revisited/assets/123646377/9a79e849-21db-4df6-8de7-e1238defbc86)


### Decision Tree Regression Force Plot

![image](https://github.com/Luz-Dobbins/week17-Project-1-Revisited/assets/123646377/2e820b20-a01a-47aa-b891-3f6382ff5a4e)


### I used item_visibility for the force plots on both the decision tree regression and the linear regression to see the effects it presents for sales per store. I like the decision tree plot and think doing it on a random forest would give a better comparison for this part of the assignment. 



