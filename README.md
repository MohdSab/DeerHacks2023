# Flatter.tech 
Generates a tailor made compliment based on the features of the user. 

Front-end is done through HTML, JS, and CSS to handle the client connection and communicate with the server. The webpage has a dynamic window showing a video feed, when prompter it takes a screenshot and sends it via HTTP protocol to the Back-end server.

Back-end server accepts a HTTP connection that can recieve a picture from client, then send API calls to REPLICATE/BLIP AI to descern unique features of the person in the picture. Then generate a prompt that is sent to OPENAI API to generate a tailor made compliment for the user. Few steps are taken for security, such as the unique API keys used for the API calls are stored in the server, and the pictures from users are deleted as soon as a compliment is generated. 
