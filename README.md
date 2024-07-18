# Artificial Intelligence Internship Projects

1. Image Captioning with Vision-Encoder-Decoder Model 
This task demonstrates the use of a pre-trained Vision-Encoder-Decoder model to generate captions for images. The model is trained on a large dataset of images and corresponding captions, and can be fine-tuned for specific tasks.

Features
Load pre-trained ResNet model and tokenizer, and Vision-Encoder-Decoder model for caption generation
Define image preprocessing function to resize and normalize images
Extract image features using ResNet model
Generate captions from image features using Vision-Encoder-Decoder model
Display image with generated caption using Matplotlib

Usage
Upload an image file to the notebook using the files.upload() function.
Run the generate_caption() function to generate a caption for the image.
Run the display_image_with_caption() function to display the image with the generated caption.


2. Movie Recommendation System using Autoencoder
This task demonstrates the use of an autoencoder to build a movie recommendation system. The system takes in user ratings and generates recommendations based on the user's preferences.

Features
Load movie ratings data and merge with movie metadata
Filter movies by genre using the filter_movies_by_genre() function
Create user-item matrix using the create_user_item_matrix() function
Build and train an autoencoder model using the build_autoencoder() function
Make movie recommendations using the recommend_movies() function

Usage
Upload the movie ratings data and movie metadata files to the notebook using the files.upload() function.
Run the recommend_movies() function to generate recommendations for a user based on their preferred genre.


3. AlienBot Chatbot
This task demonstrates the use of a chatbot to engage in conversation with users. The chatbot uses natural language processing to understand user input and respond accordingly.

Features
Define intents and responses for the chatbot using regular expressions
Implement a conversation flow using the greet() and chat() functions
Use the match_reply() function to match user input to intents and generate responses

Usage
Run the run_bot() function to start the chatbot.
Engage in conversation with the chatbot by typing in responses to its questions.
