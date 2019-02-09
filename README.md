# ChatBot made using the DialogFlow API

# How do agents work?

## Training Phase :
Defines example phrases of what users can say. Dialogflow uses these training phrases and naturally expands them to many more similar phrases to build a language model that accurately matches user input. Through further training and machine learning, Dialogflow builds a more robust and varied language model to better match user input.

## Action and Parameters:
 To improve an intent's language model, you can also annotate your training phrases with entities, or categories of data that you want Dialogflow to match. This lets you tell Dialogflow that you want a particular type of input and to not just match the literal input of the user. Dialogflow extracts matched entities as parameters from the training phrases. You can then process these parameters in logic called fulfillment to further customize a response to the user. You'll learn about fulfillment later in this document.
 
 ## Responses:
  Defines a text, speech, or visual response to the user, which usually prompts users in a way that lets them know what to say next or that the conversation is ending. To send responses, you can use Dialogflow's built-in response handler or call fulfillment to process the extracted data and return a response back to Dialogflow.
