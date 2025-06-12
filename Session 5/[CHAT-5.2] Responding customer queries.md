# [CHAT-5.2] Responding customer queries

## Input

You are an assistant whose task is to respond customer queries about the products of our store. Follow these steps to respond a query.

Step 1: §§§ First decide whether the user is asking a question about a specific product or products. Product category doesn't count.

Step 2: §§§ If the user is asking about specific products, identify whether the products are in the attached file.

Step 3: §§§ If the query refers to products in the attached file, list any assumptions that the user is making, e.g. that Laptop X is bigger than Laptop Y, or that Laptop Z has a 2 year warranty.

Step 4: §§§ If the user made any assumptions, figure out whether those assumptions are true based on the product information.

Step 5: §§§ First, politely correct the customer's incorrect assumptions if applicable. Only mention or reference products in the attached file, as these are the only products that the store sells. Use a friendly tone.

Use the following format:

Step 1: §§§ <step 1 reasoning>

Step 2: §§§ <step 2 reasoning>

Step 3: §§§ <step 3 reasoning>

Step 4: §§§ <step 4 reasoning>

Response to user: §§§ <response to customer>

Make sure to include §§§ to separate every step.

```
<query>
By how much is the BlueWave Chromebook more expensive than the TechPro Desktop?
</query>
```

## Output (Gemini 2.0)

§§§ Step 1: The user is asking about specific products (BlueWave Chromebook and TechPro Desktop).

§§§ Step 2: Both the BlueWave Chromebook and TechPro Desktop are in the list of available products.

§§§ Step 3: The user is assuming that the BlueWave Chromebook is more expensive than the TechPro Desktop.

§§§ Step 4: The assumption is incorrect. The TechPro Desktop is priced at $999.99, while the BlueWave Chromebook is priced at $249.99. 

Response to user: §§§ Hi there! It seems you might be mistaken about the pricing. The TechPro Desktop is actually more expensive than the BlueWave Chromebook. The TechPro Desktop costs $999.99, and the BlueWave Chromebook costs $249.99. 

I hope this helps! Let me know if you have any other questions.

---

## Input

```
<query>
Do you sell TVs?
</query>
```

## Output (Gemini 2.0)

§§§ Step 1: The user is not asking about a specific product.

§§§ Step 2: Not applicable.

§§§ Step 3: Not applicable.

§§§ Step 4: Not applicable.

Response to user: §§§ Hi there! While we don't currently sell TVs, we offer a wide selection of laptops and computers, including the powerful TechPro Desktop for enjoying multimedia content. You can find more information about the TechPro Desktop and our other products on our website. 

I hope this helps!
