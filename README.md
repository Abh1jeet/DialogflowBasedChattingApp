# How to Provide Replies  Dialogflow And Webhook

## what is dialogflow

Dialogflow is a  human–computer interaction technology based on natural language conversations. It is best known for creating the Assistant  that performs tasks and answers users' question in a natural language.


## what is webhook

Webhooks are "user-defined HTTP callbacks" They are usually triggered by some event ,,,,
When that event occurs, the source site makes an HTTP request to the URL configured for the webhook

### (query) user -> dialogflow -> webhook
### (output)user <- dialoglow  <- webhook




## working 

So basically user asks a query and using geocity our program extracts name of country from that sentence
That country is passed to webhook which fetches name of capital of that country 
Then webhook gives response to dialogflow which shows output to user
