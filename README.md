Introduction


Companies increasingly require new ways to communicate with their customers, facilitate interaction with them, and improve their sales channels. For this practice, we put ourselves in the situation of being freelance consultants and were hired by a company to develop a small bot for managing queries and orders.

The company sky2travel (fictitious company) hired us to create a transactional bot. They had asked us to conduct an initial project demo to assess the feasibility of the requirements. Sky2travel was a company focused on flight and travel searches. Its large customer base was between 18 and 40 years old and made intensive use of mobile phones, resulting in 70% of sales originating from these devices.

The company had identified a need among their customers to search for and purchase flights through their mobile phones in a faster and more convenient manner. As a result, they aimed to integrate their bot with platforms like WhatsApp, Telegram, web chat, Facebook Messenger, and others.

The goal was to enable customers to make requests with simple text messages such as "Flights from Madrid to London in August for 3 days" or "Affordable tickets to Berlin with Lufthansa." The application would then process the customer's requests and send them relevant information, along with a direct payment link, to their mobile phones.

For the demo, we were tasked with creating a script capable of generating requests in JSON format to be sent to the Amadeus booking software. Creating a notebook in ipynb format was sufficient for demonstrating the functionality.


What were the main objectives in this project?

1. Convert user-entered phrases into JSON format.
2. Generate a table or JSON containing information for each message.
3. Prompt users for missing information if encountered during request processing.
4. Train a custom tagger within the travel context by generating a custom corpus comprising at least 20 sentences or requests similar to the examples provided. Train the tagger and manually correct any erroneous tags.
5. Create a virtual assistant. Upon executing the "asistent()" function, users would hear the message "Hello, welcome to sky2travel. How can I assist you?" Users would then indicate their needs, such as "Ticket from Berlin to Madrid with Iberia." Subsequently, launch the bot developed in the basic section and return a voice message saying "Perfect. I'm initiating the search for your trip from X to Y for the specified DATE with AEROLINEA."
