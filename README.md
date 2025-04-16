# movie-recommender
Exploration Exercise for Prototype 1.2 – Movie Recommender Chatbot using OpenAI API

In this exercise, I worked on a medium-level exploration using the recommender prototype v.2 to return the amount of text produced for each request. The modification that I made to the original file is to set a new variable called "resp_usage" to identify the usage of the response from the API that was obtained from 'completion_tokens' and return the value in the function 'make_chat_request()'.  After that, I modified the while in the main() by adding a new variable named 'usage' to assign the returned value 'resp_usage' from the make_chat_request. Lastly, I added a new formula, 'total_token += usage', to sum the total token and added print() to display the text that says 'Total token used: XX' in the terminal.

'completion_tokens' is the new data I obtained from the API because it is the best data to represent the total number of tokens the model generates per use, which I think is the best representation of the total usage for a chat session.  

One caveat for you to keep in mind is that in the prototype directory, there are two other files for v.0 and v.1, however, there are no updates on both files because I only selected v.2 to modify, as specific instructions on which file to choose were not given. So, I would like you to focus on the v.2 file for grading purposes. 

You can view a short video of the user interaction with the modified prototype from this link: https://drive.google.com/file/d/1PpJehoSDlJ8TK14PQTdkqgoAOOu9Fy-q/view?usp=drive_link
