# Amazon Polly Lex Chat Project

Welcome to the Amazon Polly Lex Chat project that I made following an AWS workshop. I'll be walking you through what I did in order to deploy an Amazon Lex bot and demonstrate how to integrate Speech Synthesis Markup Language (SSML) with Amazon Polly to create lifelike speech. In this case, it will be a self-service bot for customers looking to order a pizza.

## Project Objectives

This project includes the following key objectives:

1. **Creating an Amazon Lex Bot:**
   - Learn how to create an Amazon Lex chatbot from scratch.

2. **Integrating with Amazon Connect:**
   - Seamlessly integrate a Lex bot with Amazon Connect for real customer interactions.

3. **Build a Structured Contact Flow:**
   - Learn how to build a structured conversation flow for guiding customers effectively.

4. **Enhance Text-to-Speech (TTS):**
   - Improve the chatbot's text-to-speech capabilities using SSML tags and Amazon Polly for natural, lifelike speech output.

## Project Overview

Here's an overview of the steps involved to create the project:

### Part 1 - Creating Your Amazon Lex Bot

1. **Log in to AWS Console:** Access the AWS Console using your Administrator-level AWS account.

2. **Navigate to Amazon Lex:**
   - Search for "Amazon Lex" in the AWS Console search bar.
   - Select "Amazon Lex - Build Voice and Text Chatbots."

3. **Create a New Lex Bot:**
   - Click on "Create bot."
   - Configure bot settings and add languages.

4. **Create a New Intent:**
   - Give the intent a unique name.
   - Define sample utterances.
   - Create and configure custom slot types, such as PizzaSize, PizzaCrust, and PizzaToppings.
   - Define fulfillment options.

5. **Build and Test Your Bot:**
   - Test the bot using the built-in testing interface to ensure it responds as expected.

6. **Publish Your Bot:**
   - Create a new version and an alias for deployment.

### Part 2 - Integrating with Amazon Connect

1. **Open Amazon Connect Console:**
   - Ensure that the region matches your Amazon Lex bot.

2. **Adding Lex Bot to Contact Flows:**
   - Select the Amazon Lex bot and alias to seamlessly integrate it into existing contact flows.

### Part 3 - Creating Contact Flow in Amazon Connect

1. **Open Amazon Connect Console:**
   - Log in to Amazon Connect.

2. **Creating a Contact Flow:**
   - Name it, e.g., "PizzaOrder_Flow."

3. **Designing the Contact Flow:**
   - Set voice, configure customer input, and set up slot attributes.
   - Add play prompts for responses.
   - Verify and publish the contact flow.

4. **Assigning the Contact Flow to a Phone Number:**
   - Choose a phone number and assign the "PizzaOrder_Flow" contact flow.

### Part 4 - Modifying SSML in Contact Flow

1. **Open Amazon Connect Console:**
   - Log in to Amazon Connect.

2. **Editing the Contact Flow:**
   - Modify the Play prompt block after Set contact attributes.
   - Use SSML to enhance the response.

3. **Publishing the Updated Contact Flow:**

This project demonstrates the creation and integration of an Amazon Lex bot with Amazon Connect, resulting in an efficient and interactive solution for customer interactions with natural text-to-speech capabilities.
