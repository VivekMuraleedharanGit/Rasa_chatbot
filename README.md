
# Rasa_chatbot
Conversational chatbot using Rasa framework

In Terminal rasas input and output will look like this
![Capture](https://user-images.githubusercontent.com/23051888/123743816-6c305680-d8cb-11eb-950f-51370089dd02.PNG)


## We can integrate this with pur website and giving UI to it like this 

![Chatbot Image](https://user-images.githubusercontent.com/23051888/123742442-43a75d00-d8c9-11eb-9bd2-557027df24d5.PNG)

You can checkout here to understand it more : https://www.youtube.com/watch?v=eJMT2FovZsM&t=312s

# Installation notes

1. Create a virtual env on your system 
  * run on the command prompt -- virtualenv env
  * Activate the virtual command by -- activate env
2. Install the rasa in the virtual env by -- pip install rasa
3. Create a new project in rasa by -- rasa init
4. You can train your rasa by command - rasa train
5. Runing the rasa model by - rasa shell
6. running the rasa server -- rasa run 
7. running the chat bot from api is by -- rasa run -m models --enable-api --cors "*"

## More details about rasa can be found here : https://rasa.com/docs/
