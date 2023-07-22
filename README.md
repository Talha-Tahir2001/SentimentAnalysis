# SentimentAnalysis
A Machine Learning Model built using ML.NET and C# for a Console App that analyzes sentiments or emotions expressed in a piece of text. The model can predict the sentiment (positive, negative, or neutral) expressed in a given text. A prediction of 1 indicates a positive sentiment, while a prediction of 0 indicates a negative sentiment.

## Dataset

The model was trained on the "yelp_labelled.txt" dataset, which contains text examples from Yelp reviews along with their corresponding sentiment labels. The dataset was preprocessed to prepare it for training.

## Prerequisites

Before running the Sentiment Analysis model, make sure you have the following prerequisites installed:

1.  [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) - Install the latest version of Visual Studio 2022 on your system.

## Getting Started

1.  Clone the repository to your local machine:


`git clone https://github.com/Talha-Tahir2001/SentimentAnalysis.git` 

2.  Open the solution in Visual Studio:
    
    -   Launch Visual Studio 2022.
    -   Choose "Open a project or solution."
    -   Navigate to the cloned repository and select the solution file.
3.  Build the solution:
    
    -   After opening the solution, click on "Build" in the top menu and select "Build Solution."
4.  Run the console application:
    
    -   Press F5 or click on "Start Debugging" to run the console application.

## How the Model Works

The Sentiment Analysis model is based on a machine learning algorithm trained to predict the sentiment of a given text. The training data consists of labeled text examples with their corresponding sentiment (positive, negative, or neutral).

The model uses the following steps to perform sentiment analysis:

1.  Data Preprocessing: The input text is preprocessed by removing special characters, converting it to lowercase, and tokenizing the text into individual words.
    
2.  Feature Engineering: The preprocessed text is transformed into numerical features using a bag-of-words representation.
    
3.  Sentiment Prediction: The model predicts the sentiment of the text based on the extracted features. If the prediction is 1, it indicates a positive sentiment; otherwise, it indicates a negative sentiment.
    

## Customizing the Model

If you want to customize or retrain the sentiment analysis model:

1.  Prepare your labeled data: Collect a dataset of text examples with their corresponding sentiment labels (e.g., positive, negative, neutral).
    
2.  Update the model training code: Open the C# files related to the model training and modify the data loading and training pipeline as needed.
    
3.  Rebuild the solution: After customizing the model, rebuild the solution by clicking on "Build" in the top menu and selecting "Build Solution."
    
4.  Run the console application: Test your updated model by running the console application in Visual Studio.

## Using and Consuming the Model

The ML.NET model you built can be used and consumed in various .NET app types, including:

-   **Web Apps and Services:** You can integrate the ML.NET model into web applications built using ASP.NET Core or ASP.NET Framework. This allows you to analyze sentiment in user-provided text inputs, process customer feedback, or perform sentiment analysis on social media comments within your web application.
    
-   **Microservices/Containers:** ML.NET models can be packaged into Docker containers, allowing you to deploy them as microservices in containerized environments. This approach enables scalable and efficient sentiment analysis as part of a larger microservices architecture.
    
-   **Desktop Apps (WPF and WinForms):** Incorporating the sentiment analysis model into desktop applications allows you to analyze sentiment from user interactions, process textual data, or provide insights from user-generated content within your desktop application.
    
-   **Azure Functions:** ML.NET models can also be used within serverless Azure Functions. This lets you perform sentiment analysis as part of serverless workflows, such as processing incoming messages, emails, or chat interactions in real-time.
    
-   **Any Azure Server-Side App Type:** Whether it's Azure Web Apps, Azure API Apps, Azure Logic Apps, or others, you can integrate the ML.NET model seamlessly into various Azure app types to enable sentiment analysis within your cloud-based applications.
    
-   **Console Apps:** As you have already built the sentiment analysis model in a console application, you can continue using it in a standalone manner for sentiment analysis on-the-go or as part of a command-line tool.
    

ML.NET's flexibility and compatibility make it a powerful choice for incorporating machine learning capabilities into various .NET application scenarios. By leveraging ML.NET's ability to consume the trained model in different app types, developers can easily integrate AI and ML functionalities into their applications without significant overhead or complexity.

## Model Performance and Improvements

The model's performance can be evaluated based on metrics such as accuracy, precision, recall, and F1-score. If you notice room for improvement, you can experiment with different machine learning algorithms, feature representations, or hyperparameters to enhance the model's accuracy.

## License

This project is licensed under the MIT License - see the [LICENSE](https://chat.openai.com/LICENSE) file for details.

## Acknowledgments

-   The model is built using [ML.NET](https://dotnet.microsoft.com/apps/machinelearning-ai/ml-dotnet) - a cross-platform, open-source machine learning framework for .NET.
-   Special thanks to the ML.NET community for providing valuable resources and examples.

----------
