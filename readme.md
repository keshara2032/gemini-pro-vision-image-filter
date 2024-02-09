# Gemini AI Model API Usage

This is a simple example for using Google Gemini AI models using their API for Educational and Research purposes.

## Getting Started

These instructions will get your copy of the project up and running on your local machine.

### Prerequisites

- Google API Console account and a project
- Google API Key for Generative Language Models
- Git
- Python
- Jupyter Notebook

### Setup

1. **Create a Project in Google API Console**  
   Create a new project in the [Google API Console](https://console.cloud.google.com/) to use the Google Generative Language Model API.

2. **Enable Google Generative Language Model API**  
   Enable the Google Generative Language Model API for your project in the Google API Console.

3. **Create an API Key for Gemini in AI Studio**  
   Generate an API key in [AI Studio](https://makersuite.google.com/app/apikey) under the Gemini project.

4. **Copy the API Key**  
   Securely copy the generated API key.

5. **Clone/Fork the GitHub Repository**  
   Clone or fork this repository to your local machine.

6. **Add Your API Key to `credentials.ini`**  
Add your API key to the `credentials.ini` file in the cloned repository.
```ini
[API_KEY]
google_api_key = #PASS YOUR API KEY HERE
```

7. **Create the Environment**  
Set up the Python environment. Note: Platform-specific libraries might cause errors.
Provided environment file is exported from a Linux Environment.


8. **Execute the Jupyter Notebook**  
Run Jupyter Notebook and navigate to the project notebook.
