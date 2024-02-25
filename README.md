# Doordash FAQ Bot

This repository documents the development of a Custom Question Answering bot trained on the frequently asked questions (FAQs) provided by delivery partners on the Doordash website. The bot is created using Azure Cognitive Service Language Studio and integrated with Microsoft Teams for real-time communication.

## Project Overview

The project focuses on building a conversational bot capable of addressing common inquiries regarding Doordash services, leveraging the FAQs available on the [Doordash website](https://dasher.doordash.com/en-au/faq). By harnessing Azure Cognitive Service Language Studio, the bot can understand user queries and provide accurate responses based on the information gathered from the Doordash FAQs.

## Dependencies

- Azure Cognitive Service Language Studio
- Microsoft Teams (for integration)
- Node.js SDK (for bot development)

## Technology Stack

- **Azure Cognitive Service Language Studio:** Employed for natural language understanding and processing.
- **Microsoft Teams:** Integrated for seamless communication with users.
- **Node.js SDK:** Utilized for bot development, offering a framework for query handling and response generation.

## Methodology

1. **Resource Creation:** Establishing a language resource in Azure Cognitive Service to support project development.
2. **Project Initialization:** Creating a new project in Language Studio, specifying language preferences and project details.
3. **Data Acquisition:** Adding the Doordash FAQ source URL to gather information for the bot's knowledge base.
4. **Knowledge Base Enhancement:** Editing the knowledge base by incorporating alternative questions to improve the bot's understanding.
5. **Testing:** Assessing the accuracy of the bot's knowledge base through sample query testing.
6. **Deployment:** Deploying the project and creating a bot instance for practical usage.
7. **Integration:** Connecting the bot to the Microsoft Teams channel for direct interaction with users.
8. **Usage:** Interacting with the bot via Microsoft Teams to inquire about Doordash-related topics and evaluating its responses.

## Conclusion

This project showcases the development and deployment process of a custom question-answering bot specifically designed for addressing Doordash FAQs. By adhering to the outlined methodology and leveraging the specified technology stack, developers can create similar conversational bots tailored for various domains and applications.
