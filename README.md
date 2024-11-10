# nvidia-healthcare-assistant
This project utilizes NVIDIA NIM and Llamaindex to assist in analyzing medical reports and health data. The platform allows users to capture ingredient labels of food or medication through the 
camera, providing recommendations tailored to the individual's health condition, supporting better lifestyle choices.

![image](https://github.com/user-attachments/assets/f0f77317-4e1b-4437-8b56-2e9745aeca75)


## Features

- **Medical Report Analysis**: The platform processes medical reports to extract key health information and provides tailored food recommendations.
- **Camera Integration**: By using a camera, users can upload images of food ingredients or medication labels, which are then analyzed to provide health-specific suggestions.
- **AI-driven Recommendations**: Using the latest in AI technology from **NVIDIA NIM** and **LlamaIndex**, the platform ensures that recommendations are based on the most accurate and up-to-date health information available.

## How It Works

1. **Upload Medical Reports**: Upload PDF medical reports to the platform.
2. **Capture Labels**: Use the integrated camera feature to capture images of food or medication labels.
3. **Receive Recommendations**: The system processes the data and offers personalized health suggestions based on the individual’s medical history and health conditions.

## Technologies Used

- **NVIDIA NIM (NVIDIA Intelligent Medical Models)**: For analyzing medical reports and generating insights based on the latest research and clinical data.
- **LlamaIndex**: For indexing and organizing documents and health-related information.
- **Google Colab**: A cloud-based platform used for the implementation and execution of the project.

## Setup Instructions

1. Clone the repository to your local machine or use Google Colab to run the code.
2. Install the necessary dependencies:

## Additional Notes

- **Rendered Image Storage**: When using the ocdrnet model to process the ingredient label images, the rendered images are stored in the `output_directory` for further analysis and processing.

