# Automated Cleaning Service Quote & Customer Management Tool

This project is an intelligent, automated system designed to provide instant cleaning service quotes based on house type and square footage, combined with a dynamic knowledge base for answering user questions. It integrates several modern tools to deliver a seamless user experience for both customers and cleaning service providers.

## Live Demo

Try the live cleaning service quote assistant here(Last step might give error as the webhook used for getting user details and adding in spreadsheet is not up continously):  
[Click here to get your instant cleaning service quote](https://creator.voiceflow.com/prototype/6894de44a13cb3809210240a)

## Features

- **Instant Quote Generation:**  
  Users input their house type and square footage, and the system generates instant, accurate cleaning service quotes tailored to their needs.

- **Knowledge Base Integration:**  
  If a user's question is informational rather than quote-related, the system fetches answers from a curated cleaning service knowledge base to provide relevant, helpful responses.

- **Voiceflow Conversational Flow:**  
  The entire user interaction is managed via a smooth, conversational flow built in Voiceflow, ensuring an engaging experience.

- **Automated Customer Data Management:**  
  After generating a quote, the user's details are automatically added to a customer database (Google Sheets) using **Make.com** (formerly Integromat), simplifying data collection and follow-up.

- **Powered by Relevance AI:**  
  The quote generation and knowledge retrieval leverage Relevance AI’s semantic search and contextual understanding capabilities.

## Technologies Used

- **Relevance AI:** For building and querying the knowledge base and generating quotes.  
- **Voiceflow:** For designing and managing the conversational user interface.  
- **Make.com:** For automation workflows, such as adding customer data to a spreadsheet.  
- **Google Sheets:** As the customer database to store leads and interaction history.

## How It Works

1. User interacts with the Voiceflow cleaning service assistant.  
2. User provides house type and square footage to request a cleaning service quote.  
3. The system uses Relevance AI to generate a precise quote based on user inputs.  
4. If the user asks a general question about cleaning services, answers are fetched from the knowledge base instead.  
5. Once the quote is delivered, user details are automatically logged into a Google Sheets database via Make.com automation.  
6. The user can then receive follow-ups or further assistance based on stored data.


## Setup & Deployment

- The Voiceflow project manages the conversational flow and API calls to Relevance AI.  
- The Relevance AI studio contains the cleaning service knowledge base and quote generation logic.  
- Make.com automates data syncing from Voiceflow responses to Google Sheets.

*Note: API keys and credentials for Relevance AI and Make.com need to be configured securely.*

## Future Enhancements

- Add multi-language support for a broader customer base.  
- Integrate SMS/email notifications for instant customer follow-up.  
- Expand the knowledge base with more detailed cleaning service FAQs and pricing info.  
- Add analytics dashboard to track quote requests and customer engagement.
