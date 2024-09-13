
# **Sentiment Analysis Using Hugging Face and Gradio**

## **Project Overview**

This project demonstrates the integration of Hugging Face's **text-to-text models** with **Gradio**, a tool for building interactive user interfaces, to perform **sentiment analysis**. The task involves classifying text data as **positive**, **neutral**, or **negative** sentiments. Two pre-trained models are utilized: one for **English** and another for **Arabic** sentiment analysis.

This project is part of **Assignment #1: Integrating Text-to-Text AI Pipelines with Gradio**, where students are required to demonstrate their understanding of Gradio, Hugging Face models, and the integration of these tools into interactive applications. The project also includes data manipulation and visualization using **Pandas** and **Matplotlib**.

---

## **Key Features**

1. **Sentiment Analysis**:
   - Classifies text into **positive**, **neutral**, or **negative** sentiments.
   - Supports both **English** and **Arabic** languages through pre-trained models.

2. **Interactive Gradio Interface**:
   - Users can upload a text file with sentences.
   - Users can select the language of the text (English or Arabic) for analysis.
   - Results are displayed in a structured DataFrame, and a bar plot visualizes the sentiment distribution.

3. **Data Visualization**:
   - A **bar plot** shows the number of sentences categorized under each sentiment label (positive, neutral, negative).

4. **Three Jupyter Notebooks**:
   - **Full Implementation Notebook**: Full integration of Hugging Face text-to-text pipelines with Gradio.
   - **Simple Pipeline Notebook**: Demonstrates how the Hugging Face pipeline works without Gradio.
   - **Gradio Example Notebook**: Showcases how Gradio components work using hardcoded data.

---

## **Notebooks Description**

1. **Full Implementation Notebook**:
   - This notebook contains the complete code for integrating Hugging Face's sentiment analysis models with Gradio.
   - The interface allows users to:
     - Upload a text file containing sentences.
     - Select a language (English or Arabic) for sentiment analysis.
     - View results in both a table and a sentiment distribution bar plot.

2. **Simple Pipeline Notebook**:
   - This notebook demonstrates how the Hugging Face **text-to-text pipeline** works without using Gradio.
   - The notebook processes predefined English and Arabic sentences and presents the sentiment analysis results in a DataFrame format.

3. **Gradio Example Notebook**:
   - This notebook demonstrates the use of **Gradio components** (like file upload, dropdown menu, DataFrame, etc.).
   - The notebook uses hardcoded data to demonstrate how these components work in practice.

---

## **Understanding the Hugging Face Text-to-Text Pipeline**

- Hugging Face offers pre-trained models capable of processing various natural language tasks. This project utilizes two sentiment analysis models:
  1. **English Model**: `distilbert-base-uncased-finetuned-sst-2-english`, designed to classify sentences into positive or negative sentiments.
  2. **Arabic Model**: `CAMeL-Lab/bert-base-arabic-camelbert-da-sentiment`, trained for sentiment analysis of Arabic text.
- The models take a sentence as input and return a **sentiment label** (positive, neutral, or negative) along with a **confidence score**.

---

## **How to Run the Code**

### **1. Clone the Repository**

- git clone https://github.com/your-repo-url

- This command downloads all the project files to your local machine.
  giving you access to everything needed to run the project locally

### **2. Install the Required Libraries**

This project uses the following libraries:
- Gradio
- Transformers -> Pipeline (Hugging Face)
- Pandas
- Matplotlib

### **3. Running the Notebooks**

- Open the notebooks in **Jupyter Notebook**, **Google Colab**, or any other environment(IDE) that supports `.ipynb` files.

### **4. Launching the Gradio Interface**

- Run the **Full Implementation Notebook**, to start the Gradio interface.

- Upload a text file and select the desired language (English or Arabic). The model will analyze the sentences and display the results in a formatted table and a bar plot.

---

## **Expected Output**

1. **DataFrame**: Displays the analyzed sentences along with their sentiment labels (positive, neutral, negative) and confidence scores for each analyzed sentence.

2. **Bar Plot**: Displays a visual representation of the sentiment distribution.

---

## **Hugging Face Project Page**

- You can also view the whole project on Hugging-Face space
- https://huggingface.co/spaces/Abduuu/Sentiment-Analysis

## **Video Walkthrough**

A short video walkthrough is included in the repository, demonstrating how to use the **Gradio interface** for sentiment analysis.

- **URL**

