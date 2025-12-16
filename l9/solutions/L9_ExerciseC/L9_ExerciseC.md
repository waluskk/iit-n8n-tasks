## L9 Exercise C: Solution

**1. Workflow creation**

I created a new workflow in n8n and named it according to the required naming

![Workflow naming](step1.png)

**2. Webhook Setup**

I created a **Webhook node** to act as the trigger.

**Configuration:** It is set to listen for a call on the test webhook associated with my Codespace link

**3. Data processing**

Next, I created a **Code node**.

The node queries any JSON data (if received) and saves it to a notes.txt file.


 