# This project is uploaded in Hugging Face Space. Check it now : 
https://huggingface.co/spaces/Shiladitya123Mondal/Food-Nutrition-app

# Food Identification and Nutrition Info
This application identifies food items from an uploaded image and retrieves their nutritional information, including calories, fat content, protein, and more. The model leverages a pre-trained Vision Transformer (ViT) for image classification, and the nutritional data is fetched using the Nutrition API.

# Features
Food Identification: Upload an image of a food item, and the application will identify the food using a Vision Transformer model.
Nutritional Information: Once the food is identified, the application fetches and displays detailed nutritional information including calories, fat, protein, and more.
User-Friendly Interface: The application is built using Gradio, providing an easy-to-use interface for users.
How It Works
Image Upload: The user uploads an image of a food item.
Image Classification: The image is processed using a pre-trained Vision Transformer (ViT-base-patch16-224) to identify the food item.
API Call: The identified food name is used to query the Nutrition API to retrieve the nutritional information.
Display Results: The nutritional information is formatted and displayed in a table for easy reading.

# Usage
Open the application in your browser.
Upload an image of the food item you want to identify.
The application will display the nutritional information for the identified food item.
# Example
Here’s an example of the app in action:

Upload Image: Upload an image of a banana.
Result: The app identifies the food as "Banana" and displays the nutritional information such as calories, serving size, total fat, protein, carbohydrates, and more.
API
Nutrition API: The app uses the API-Ninjas Nutrition API to fetch nutritional information.
# Dependencies
Python 3.8+
transformers
gradio
PIL (Pillow)
requests
All dependencies are listed in the requirements.txt file.

# Limitations
The application relies on the accuracy of the pre-trained Vision Transformer model, which may not always correctly identify every food item.
The nutritional information is based on typical values and may vary based on the food's preparation or other factors.
# Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Contributions are welcome!
