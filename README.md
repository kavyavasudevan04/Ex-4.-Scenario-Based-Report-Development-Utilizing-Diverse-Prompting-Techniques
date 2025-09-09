# Ex-4.-Scenario-Based-Report-Development-Utilizing-Diverse-Prompting-Techniques
Objective: The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Create prompts using various AI prompting techniques to guide your experiment, data collection, analysis, and report creation.
## Aim:
The aim of this experiment is to design and develop an AI-powered chatbot that can effectively manage customer inquiries in a retail environment.
## Algorithm:
#### 1 Problem Definition:
Identify common retail customer queries (e.g., product availability, order status, return policies).

#### 2 Prompt Design:

Create test prompts for Zero-Shot, Few-Shot, Chain-of-Thought, Role Prompting, and Retrieval-Augmented Prompting.

Ensure prompts cover multiple scenarios: FAQs, order issues, and product recommendations.

#### 3 Model Selection:
Use diverse LLM platforms (ChatGPT, Claude, Bard, Cohere, Meta) for evaluation.

#### 4 Execution:

Input prompts into each AI model.

Collect outputs for each prompting technique.

#### 5 Analysis:

Evaluate responses on accuracy, fluency, relevance, and personalization.

Compare user satisfaction across prompting techniques.

#### 6 Result Compilation:
Document findings in a structured report with examples, comparisons, and recommendations.
## Prompt:
#### Zero-Shot Prompt:
What is the return policy for clothing items in this retail store?

#### Few-Shot Prompt:
Example 1: Q: What is the delivery time for electronics? A: Delivery takes 3–5 working days.
Example 2: Q: What is the warranty on shoes? A: Shoes come with a 6-month warranty.
Now answer: What is the return policy for clothing items?

#### Chain-of-Thought Prompt:
A customer asks about returning clothing items. First, identify the return policy timeframe, then check exceptions, and finally explain how the return process works. Provide a structured answer.

#### Role Prompting:
You are a helpful customer support chatbot for a retail store. A customer wants to return a clothing item. Explain the process politely and clearly.

#### Retrieval-Augmented Prompting (RAG):
Based on the following knowledge base, summarize the return policy for clothing items in simple words.
## Output:
#### Zero-Shot: 
Clothing items can be returned within 30 days of purchase with a receipt.

#### Few-Shot: 
Clothing items can be returned within 30 days of purchase. They must be unworn and in original condition. Refunds are processed within 5 days.

#### Chain-of-Thought: 
Step 1: Return policy timeframe is 30 days. 
Step 2: Exceptions include final-sale items. 
Step 3: Returns can be made in-store or online. Final Answer: Customers can return clothing items within 30 days, except sale items, either in-store or by mail.

#### Role Prompting: 
I understand you’d like to return a clothing item. You can do so within 30 days of purchase, provided the item is unused and in its original condition. Please bring the receipt, and our staff will be happy to assist you.

#### RAG: 
According to the store’s official return policy, clothing items can be returned within 30 days with proof of purchase. Items must be in original condition. Refunds are issued to the original payment method.
## Result:
The experiment showed that prompting technique greatly impacts chatbot response quality.
