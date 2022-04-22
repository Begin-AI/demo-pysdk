This example is built using the Goodreads public dataset available on: https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home

In this directory you'll find the following notebooks:

This dataset contains 300k books and 200 million users interactions with these books.


- Schema.json: required by beginai platform for integration, to be submitted in your acconut on app.begin.ai.

- BeginAI_SDK: demonstrates using beginai's sdk to generate signatures and submit them to Beginai's platform.

- Recommend: Shows how to retrieve recommendations for a user. 
Once the platform has run training (few hours post submission, as this is a large dataset) you'll receive a notification to let you know when you can start querying the model.
