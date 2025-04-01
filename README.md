Introduction :  
Pests pose a major threat to agricultural productivity, leading to reduced yields and nutrient depletion in crops. The excessive use of pesticides not only contaminates the food chain but also causes environmental and health hazards. Traditional pest identification methods rely on manual inspection, which is often inefficient, time-consuming, and prone to errors. These challenges contribute to economic losses for farmers and, in extreme cases, may even endanger lives.

Early and accurate pest detection can help reduce unnecessary pesticide application, leading to a more sustainable and eco-friendly farming approach. This project introduces an advanced pest classification and detection system utilizing deep convolutional neural networks (CNNs). The proposed model effectively identifies common agricultural pests by analyzing images captured from various sources. By leveraging pre-trained models fine-tuned on a diverse dataset, the system improves accuracy, even when dealing with a limited dataset specific to pests.

This deep learning-based solution empowers farmers by providing precise pest identification, facilitating better decision-making in pest control, and ultimately enhancing agricultural sustainability and productivity.

Proposed System
Many existing agricultural information platforms lack dedicated pest classification and detection features. Our proposed system fills this gap by offering a robust pest detection solution that meets the needs of farmers. Additionally, the platform allows users to consult agricultural experts and officers for guidance on pest-related issues.

Key Features
Query System – Farmers can ask experts or agricultural officers for advice regarding pest infestations.
 Pest Identification – The system provides detailed information about identified pests, including their characteristics and the recommended pesticides for control.
 Expert Insights – Agricultural officers and experts can access pest details and provide guidance.

System Functionalities
 Automated Pest Detection – Uses a deep learning model to classify and detect pests from images.
 High Efficiency – Processes images quickly, outperforming traditional manual inspections.
 Accurate Classification – The deep learning approach ensures precise identification of different pests.
 Scalability – Can be deployed on a larger scale to analyze a vast number of pest images.
 User-Friendly Interface – Designed to be accessible to users with no technical expertise in pest identification.
 Comprehensive Pest Details – Provides in-depth information on detected pests and recommended pesticide treatments.

Technologies Used 🛠️
Development Tools:

VS Code

Flask

Platforms:

Jupyter Notebook

Google Colab

Libraries:

Flask

NumPy

Pandas

Torch (PyTorch)

PyMongo

System Interface
 Prediction Page – Displays the pest classification results.
 Result Page – Shows the identified pest along with relevant information.
 Officer Dashboard – Allows agricultural officers to access pest-related data and respond to queries.

Setup & Execution ⚙️
1️ Create a folder named models and place pest_model.pth inside it.
2️ Run the following command to start the application:
