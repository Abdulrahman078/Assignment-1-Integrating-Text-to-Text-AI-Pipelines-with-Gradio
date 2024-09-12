# Sentiment Analysis Using Hugging Face and Gradio
## **Project Overview**

   This project demonstrates the integration of Hugging Face's **text-to-text** models with **Gradio**, a tool
for building interactive user interfaces, to perform **sentiment analysis**. The task involves classifying
text data as **positive**, **neutral**, or **negative sentiments**. Two pre-trained models are utilized: one for
**English** and another for **Arabic** sentiment analysis.



## **Main Files**

1. **Full Implementation Notebook**:
   - This notebook contanins the complete code for Integrating Hugging Face's sentiment analysis Using Gradio's Interface
   - The interface allows users to:
      - Select a language (Arabic, English) for sentiment analysis
      - Upload a text file that contains sentences.
      - View results in both formatted DataFrame table and a bar plot distribution.
2. **Simple Pipeline Notebook**:
   - This notebook illustrates how the Hugging Face pipeline without the Gradio interface.
   - The notebook processes predefined English and Arabic sentences and presents the output in a DataFrame format
3. **Gradio Example Notebook**:
   - This notebook illustrates the use of **Gradio components**
      - Like file upload, dropdown menu, DataFrame, etc.
   - The notebook uses Hardcoded data to illustrate how these component work.


## ""How the Hugging Face text-to-text pipeline works""

- Hugging Face offers pre-trained models that process different natural language tasks. In this project we used two Sentiment-analysis models:
  1. **Arabic Model**: "CAMeL-Lab/bert-base-arabic-camelbert-da-sentiment", Designed and trained for sentiment-analysis of Arabic text.
  2. **English Model**: "distilbert-base-uncased-finetuned-sst-2-english", Designed and trained for sentiment-analysis of Arabic text.
- The models take a sentence or list of sentences as an input and returns its label (positive,neutral,negative) along with a **confidence score**.
