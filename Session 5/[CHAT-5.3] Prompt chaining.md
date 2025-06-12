# [CHAT-23] Prompt chaining

## Input 1

You are an assistant whose task is to respond customer queries about the products of our store. The available products are listed in the attached file. Refer to that list as the "our product catalog".

Decide whether the user is asking a question about a specific product or products. Product category doesn't count.

```
<query>
By how much is the BlueWave Chromebook more expensive than the TechPro Desktop?
</query>
```

## Output 1 (Gemini 2.0)

The user is asking a question about two specific products, the BlueWave Chromebook and the TechPro Desktop.

## Input 2

If the user is asking about specific products, identify whether the products are in our catalog.

## Output 2 (Gemini 2.0)

Yes, both the BlueWave Chromebook and the TechPro Desktop are in our catalog.

## Input 3

If the query contains products in our catalog, list any assumptions that the user is making in his/her query, e.g. that Laptop X is bigger than Laptop Y, or that Laptop Z has a 2 year warranty.

## Output 3 (Gemini 2.0)

The user is assuming that both products have a price, so it's possible to compare them.

## Input 4

If the user made any assumptions, figure out whether the assumption is true based on your product information.

## Output 4 (Gemini 2.0)


The assumption is true. The prices for both products are listed in the product catalog:

- BlueWave Chromebook: $249.99

- TechPro Desktop: $999.99

## Input 5

Remember that the specific query was:

```
<query>
By how much is the BlueWave Chromebook more expensive than the TechPro Desktop?
</query>
```

First, politely correct the customer's incorrect assumptions if applicable. Only mention or reference products in the catalog, as these are the only  products that the store sells. Answer the customer in a friendly tone.

## Output 5 (Gemini 2.0)

Hi there! Actually, it's the other way around. The BlueWave Chromebook is less expensive than the TechPro Desktop. The TechPro Desktop is $750 more expensive than the BlueWave Chromebook.