# extrinos team.

# AI Blog Content Assistant
### Overview
This Python script leverages the Hugging Face LLM and Streamlit to create an AI-powered blog content assistant. The tool assists users in generating blog titles and content based on provided inputs.

### Dependencies
* huggingface_hub
* langchain
* streamlit
* secret_api_keys (custom module for storing Hugging Face API key)

### Setup
Create a Hugging Face API token: Obtain a token from your Hugging Face account settings.
Store your Hugging Face API token in secret_api_keys.py in variable named huggingface_api_key.

### Install dependencies:
pip install huggingface_hub langchain streamlit

### Run the script:
streamlit run your_script_name.py

### How to Use

#### Title Generation:
* Enter a topic in the "Input the topic" expander.
* Click the "Submit the topic" button to generate a list of potential titles.

#### Blog Generation:
* Enter the desired blog title in the "Input Blog details" expander.
* Set the desired blog length using the slider.
* Add keywords by entering them in the input field and clicking "Add Keyword".
* Click the "Submit the Info" button to generate the blog content.

#### Key Features
* Generates creative and attention-grabbing blog titles.
* Produces high-quality, informative, and plagiarism-free blog content.
* Allows customization of blog length and keywords.
* Provides a user-friendly Streamlit interface.

#### Limitations
* Relies on the quality of the Hugging Face LLM.
* Generated content may require editing and refinement.


