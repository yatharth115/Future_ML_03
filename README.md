# 🏏 One8 Customer Support Chatbot (Dialogflow + Telegram)

A virtual assistant developed for the One8 by Virat Kohli sporting brand to handle common customer support inquiries (Order Tracking, Returns, FAQs).

**Deployment Platform:** Telegram
**NLP Engine:** Google Dialogflow ES

## 🌟 Key Features

* **Custom Intent Design:** Created specific intents for core support topics:
    *'One8_Order_Id_Status'
    *'One8_Order_Status_Check'
    *'One8_Product_Details'
    *'One8_Store_Locations'
    *'One8_Welcome_Greeting'
* **Custom Entities:** Defined structured data types to capture key information:
    *'@ One8_Order_Issue' (e.g., track, shipment, cancel, order) 
    *'@ One8_Product_Category' (e.g., sneakers, t-shirts, shoes)
    *'@ Order_Identifier' (e.g., O18-XXXX)
* **Intelligent Fallback:** Uses the `One8_Fallback_Misunderstanding` intent for seamless conversational recovery.
* **24/7 Deployment:** Instantly available on Telegram via Dialogflow's native integration.

## 🚀 How to Import and Test the Agent

1.  **Download:** Download the contents of the `/One8_Support_Bot` folder.
2.  **Create Agent:** In the Dialogflow ES console, create a new agent (e.g., "One8-Test").
3.  **Import:** Go to **Settings⚙️ > Export and Import > Restore from ZIP** and upload the ZIP file created from the `/One8_Support_Bot` folder.
4.  **Test:** Use the **Try it now** console on the right to test phrases like:
    * `Where is my order O18-4567?`
    * `I want to return a jacket.`
    * `I need a human agent.`

**Live Demo Link:** *https://t.me/One8_Support_bot*

