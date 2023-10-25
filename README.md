# Amazon Polly Lex Chat

Welcome to the Amazon Polly Lex Chat project that I made following an AWS workshop. I'll be walking you through the process of deploying an Amazon Lex bot and demonstrate how to integrate Speech Synthesis Markup Language (SSML) with Amazon Polly to create lifelike speech.

## Goals

By the end of this tutorial, you will achieve the following objectives:

1. **Create Your Amazon Lex Bot:**
   - Learn how to create your Amazon Lex chatbot from scratch.

2. **Integrate with Amazon Connect:**
   - Seamlessly integrate your Lex bot with Amazon Connect for real customer interactions.

3. **Build a Structured Contact Flow:**
   - Master the art of building a structured conversation flow for guiding customers effectively.

4. **Enhance Text-to-Speech (TTS):**
   - Improve your chatbot's text-to-speech capabilities using SSML tags and Amazon Polly for natural, lifelike speech output.

## Let's Get Started!

### Part 1 - Create Your Amazon Lex Bot

1. **Log in to AWS Console:** Use your Administrator-level AWS account.

2. **Navigate to Amazon Lex:**
   - Type "Amazon Lex" in the search bar.
   - Select "Amazon Lex - Build Voice and Text Chatbots."

3. **Create a New Lex Bot:**
   - Choose "Create bot."
   - Configure bot settings and add languages.

4. **Create a New Intent:**
   - Give the intent a unique name.
   - Define sample utterances.
   - Create and configure custom slot types for PizzaSize, PizzaCrust, and PizzaToppings.
   - Define fulfillment options.

5. **Build and Test Your Bot:**
   - Test your bot using the built-in testing interface.

6. **Publish Your Bot:**
   - Create a new version and alias for deployment.

### Part 2 - Integrate with Amazon Connect

1. **Open Amazon Connect Console:**
   - Ensure the region matches your Amazon Lex bot.

2. **Add Lex Bot to Contact Flows:**
   - Select the Amazon Lex bot and alias to integrate it into existing contact flows.

### Part 3 - Create Contact Flow in Amazon Connect

1. **Open Amazon Connect Console:** Log in to Amazon Connect.

2. **Create a Contact Flow:**
   - Name it, e.g., "PizzaOrder_Flow."

3. **Design the Contact Flow:**
   - Set voice, get customer input, and configure slot attributes.
   - Add play prompts for responses.
   - Verify and publish the contact flow.

4. **Assign the Contact Flow to a Phone Number:**
   - Choose the phone number and assign the "PizzaOrder_Flow" contact flow.

### Part 4 - Modify SSML in Contact Flow

1. **Open Amazon Connect Console:** Log in to Amazon Connect.

2. **Edit Contact Flow:**
   - Modify the Play prompt block after Set contact attributes.
   - Use SSML to enhance the response.

3. **Publish the Updated Contact Flow:**
