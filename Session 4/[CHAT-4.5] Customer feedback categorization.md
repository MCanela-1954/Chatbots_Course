# [CHAT-4.5] Customer feedback categorization

---

## Input

Analyze this customer feedback and categorize the issues. Use these categories: UI/UX, Performance, Feature Request, Integration, Pricing, and Other. Also rate the sentiment (Positive/Neutral/Negative) and priority (High/Medium/Low).

Here is the feedback: The new dashboard is a mess! It takes forever to load, and I can't find the export button. Fix this ASAP! 

## Output (Gemini 2.0)

Certainly, let's analyze the customer feedback:

**1. Categorization:**

* **UI/UX:** 
    * "The new dashboard is a mess!" (Poor design, difficult to navigate) 
* **Performance:**
    * "It takes forever to load" (Slow loading times)
* **Feature Request:**
    * "I can't find the export button" (Missing export functionality)

**2. Sentiment:**

* **Negative:** The feedback expresses strong dissatisfaction with the new dashboard.

**3. Priority:**

* **High:** The customer demands immediate action ("Fix this ASAP!"). The performance issue and missing export functionality likely impact user productivity and satisfaction significantly.

**Summary:**

This customer feedback highlights serious issues with the new dashboard, including poor usability, slow loading times, and the absence of a crucial export feature. The customer is highly dissatisfied and demands urgent resolution. 

I hope this analysis is helpful! Let me know if you have any other feedback to analyze.

---

## Input

Our CS team is overwhelmed with unstructured feedback. Your task is to analyze feedback and categorize issues for our product and engineering teams. Use these categories: UI/UX, Performance, Feature Request, Integration, Pricing, and Other. Also rate the sentiment (Positive/Neutral/Negative) and priority (High/Medium/Low). Use JSON format in your response, as in the following example:

```
<example>
Feedback: The new dashboard is a mess! It takes forever to load, and I cant find the export button. Fix this ASAP!
{
    "feedback": "The new dashboard is a mess! It takes forever to load, and I cant find the export button. Fix this ASAP!",
    "category": "UI/UX",
    "sentiment": "Negative",
    "priority": "High"
}
</example>
```

Feedback: Your pricing is ridiculous! $99/mo for basic features? I'm switching to a competitor.

## Output (Gemini 2.0)

```
json
{
    "feedback": "Your pricing is ridiculous! $99/mo for basic features? I'm switching to a competitor.",
    "category": "Pricing",
    "sentiment": "Negative",
    "priority": "High"
}
```

