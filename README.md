## The Canine Classifier

# Contributors
Sarah Wilsoncook
Marcel Lommerzheim
Pessi Virta
Jaydeep Bhat

# Description
Information about the breed of dog is important. But we can't identify more than 50% of dog breeds correctly. So, we used the computer vision approach to solve this problem. We used the convolutional neural network (CNN, a deep learning method). We tested different model families of CNN architecture and then implemented the EfficientNetV2S, a pre-trained model for this project. We added gradcam features in the last prediction layer. This model was assembled into Docker and deployed on the Google Cloud Platform (GCP) in Artifact Registry. For the front end, we used Streamlit to make the user interface available. The output is the prediction probability score in percentage and relevant information of the dog's breeds (pure or mixed).

# Usage of this app
Open this app using URL here: ![web-app](https://canine-classifier.streamlit.app/)
or using [QR code](https://github.com/wilsoncooked/canine-classifier-app/blob/master/images/qrcode.png)

How to use the app:
Step 1: Either take a photo using camera or upload an image from your device
Step 2: Adjust the square frame around the dog in the image
Step 3: Click 'Identify dog'
Step 4: You get a result of your dog's breeds information
Step 5 (optional): Try another dog's image by clicking on 'Try another dog' option

# Source code
These two repositories are linked to the GitHub repositories of Sarah Wilsoncook. As project lead, all the original codes and commits can be found in her repo. Please follow the  submodule links for the same.

# License
GNU General Public License (GPL) v3
    Copyright (C) 2024 Sarah Wilsoncook, Marcel Lommerzheim, Pessi Virta, Jaydeep Bhat

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.


# Your Dog's info in a Snap

![Dogs all lined up](https://images.unsplash.com/photo-1494947665470-20322015e3a8?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTJ8fGRvZ3N8ZW58MHx8MHx8fDI%3D)
