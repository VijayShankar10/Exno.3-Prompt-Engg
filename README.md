# Exno.3 - Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE: 03.09.25                                                                           
### REGISTER NUMBER : 212222040178

### Aim:  
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, structured prompts.

---

### Algorithm and Prompting Techniques for AI Chatbot Development  

## 1. Straightforward Prompts  
**Objective:** Provide direct, simple responses to customer questions without additional context or complexity.  

**Prompt Pattern:**  
Prompt: *"When a customer asks 'Where is my order?', respond with: 'Your order is currently being processed and will be delivered by [date].'"*  

**Explanation:**  
This method ensures quick and clear responses to common queries. For example, when a customer inquires about order status, the chatbot instantly replies with a consistent message.  

---

## 2. Tabular Format Prompting  
**Objective:** Organize information in a structured table format for better readability.  

**Prompt Pattern:**  
Prompt: *"Provide troubleshooting steps for common device issues in a table format with columns: Issue | Possible Cause | Suggested Solution."*  

**Example Output:**  

| Issue                  | Possible Cause        | Suggested Solution                                   |
| ---------------------- | --------------------- | --------------------------------------------------- |
| Phone not charging     | Damaged cable/adapter | Try a different charger or USB cable.               |
| Screen flickering      | Software glitch       | Restart the device or update display drivers.       |
| App keeps crashing     | Outdated version      | Update or reinstall the app.                        |  

**Explanation:**  
This technique helps present solutions in an easy-to-read format, useful when multiple options need to be compared quickly.  

---

## 3. Missing Word Prompting  
**Objective:** Let the chatbot fill in missing details or complete partially given information.  

**Prompt Pattern:**  
Prompt: *"The customer asks: 'My order is ____.' → Chatbot should complete: 'Your order is being processed and expected to arrive by [date].'"*  

**Explanation:**  
Here, the model infers missing information to provide a complete response. This ensures the chatbot gives meaningful answers even when user input is incomplete or vague.  

---

## 4. Preceding Question Prompting  
**Objective:** Encourage the chatbot to ask clarifying questions before providing an answer.  

**Prompt Pattern:**  
Prompt: *"When a customer asks 'Why hasn’t my package arrived?', respond first with a clarifying question like: 'Could you share your order ID so I can check the status for you?' Then provide the solution."*  

**Explanation:**  
This method ensures the chatbot collects essential details before answering, making responses more accurate and personalized.  

---

### Table Result  

| **Prompting Technique**      | **Objective**                                                      | **Prompt Pattern Example**                                                                                                          | **Key Benefit**                                      |
| ----------------------------- | ------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| **Straightforward Prompting** | Provide direct, simple responses to routine questions.             | *"When a customer asks 'Where is my order?', respond: 'Your order is being processed and will be delivered by [date].'"*            | Quick and consistent answers.                        |
| **Tabular Format Prompting**  | Present information in structured, table-based format.             | *"List troubleshooting steps in a table: Issue | Cause | Solution."*                                                               | Improves readability and clarity.                    |
| **Missing Word Prompting**    | Fill in missing details to complete user’s input.                  | *"'My order is ____.' → 'Your order is being processed and expected to arrive by [date].'"*                                         | Handles incomplete or vague queries effectively.     |
| **Preceding Question Prompting** | Ask clarifying questions before giving the final answer.           | *"'Why hasn’t my package arrived?' → 'Can you share your order ID so I can check?' Then provide solution."*                         | Increases accuracy and personalization of responses. |

---

### Result:  
Thus the Prompts were executed successfully.
