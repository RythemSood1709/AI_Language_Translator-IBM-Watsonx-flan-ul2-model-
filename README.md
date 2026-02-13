## Babel Fish: English to Spanish Translator
This project is a language translation system. It leverages the FLAN-UL2 model via IBM watsonx.ai to provide high-quality translations from English to Spanish.

## Project Overview
The "Babel Fish" system is designed to demonstrate the integration of Large Language Models (LLMs) into functional applications. By utilizing the FLAN-UL2 model—an encoder-decoder model trained on a large collection of datasets—the application can understand nuances in English prose and convert them into grammatically correct Spanish.

## Key Features
Model: Powered by google/flan-ul2 available on IBM watsonx.ai.

Zero-Shot Translation: Uses prompt engineering to translate text without specific fine-tuning for the Spanish language pair.

IBM Cloud Integration: Utilizes IBM Cloud credentials and Project IDs for secure API communication.

Streamlined Interface: Built to handle English input and return near-instantaneous Spanish output.

## Prerequisites
Before running the project, ensure you have the following:

Python 3.10+

IBM Cloud Account with watsonx.ai access.

IBM API Key and a Project ID from your watsonx instance.

Library: ibm-watsonx-ai
