# Project 1: Azure AI Document Intelligence Integration

This project demonstrates how to set up and integrate Azure AI Document Intelligence with Azure Functions and a Next.js front-end application. The solution automates receipt analysis by extracting data quickly and accurately using advanced AI technology.

## Overview

Azure AI Document Intelligence enhances the efficiency of receipt analysis through AI-driven data extraction. This project walks through the steps to:

1. Set up Azure AI Document Intelligence.
2. Create and deploy an Azure Function using Visual Studio Code.
3. Integrate the Azure Function with a Next.js front-end.

## Prerequisites

- Azure Subscription
- Microsoft Account
- Visual Studio Code
- Azure CLI
- Postman (for API testing)

## Setup Guide

### 1. Azure AI Document Intelligence

1. **Navigate to the Azure Portal:**
   - Visit [portal.azure.com](https://portal.azure.com) and log in with your credentials.

2. **Search and Select Azure AI Document Intelligence:**
   - Use the search bar to find 'Azure AI Document Intelligence' and select it.

3. **Create a New Resource:**
   - Click on the 'Create' button to start the resource creation process.
   - Choose your subscription and select or create a resource group.
   - Enter a unique name for your resource and select a preferred region.
   - Choose the pricing tier, preferably "Free F0" or "Standard S0" if free tier is unavailable.

### 2. Creating and Deploying Azure Function

1. **Setup Visual Studio Code:**
   - Ensure Visual Studio Code is installed and configured with Azure Function extensions.

2. **Deploy Azure Function:**
   - Create a new Azure Function project in Visual Studio Code.
   - Deploy the function to your Azure subscription.

3. **Test the Azure Function:**
   - Use Postman to send a sample receipt to the deployed function.
   - Check if the receipt data is correctly processed and results are displayed as expected.

### 3. Integrating with Next.js Front-End

1. **Set Up Next.js:**
   - Initialize a Next.js project with TypeScript:
     ```bash
     npx create-next-app@latest <name_of_your_project>
     ```
   - Start the development server:
     ```bash
     npm run dev
     ```

2. **Create a Page to Fetch the API:**
   - Ensure both the Azure Function and the Next.js front-end are running concurrently.
   - Implement API calls to the Azure Function from the Next.js application.

3. **Testing:**
   - Verify the integration by analyzing receipt data directly from your Next.js web interface using image URLs.

## Conclusion

Congratulations! You have successfully set up and integrated Azure AI Document Intelligence with an Azure Function and a Next.js application. This project allows you to analyze receipts using AI and streamline your data extraction process.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgements

- Azure AI Document Intelligence
- Visual Studio Code
- Next.js

---

Feel free to adjust the content according to your project's specifics or additional details that may be necessary. Let me know if you need further customization!
