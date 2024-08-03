# pratham_chatbot

1. Initially we scrape main page using websrapper.py.
2. Save the output in output.txt
3. Now scrape links from output.txt which contain text data like html pages with text and pdf .
4. Store all of them in text format in data folder ignoring jpg and other files which can cause gibberish content.
5. Move output.txt to to data folder.

# Developing model and frontend
I. have earlier made chatbot using RASA, LlamaIndex , Langchain . But this time used botpress over other frameworks because of--

 1. Easy modularity 
 2. No retraining need after updation of site i.e. pratham.org
 3. Free 5$ AI tokens with pay as you model
 4. Option to choose from AI models
 5. And separate plan for teams with upgradations.
    
II. For a detailed explanation and demonstration, please watch the YouTube video.-- @ https://www.youtube.com/watch?v=vr_4DAQYbRA
