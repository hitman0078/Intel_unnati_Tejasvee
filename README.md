# Intel_unnati_Tejasvee
Industrial Training Project 2024

This problem statement is crafted to introduce the fascinating domain of Generative Artificial Intelligence (GenAI) through 
a series of interactive exercises. Participants will gain foundational knowledge of GenAI, conduct basic Large Language 
Model (LLM) inference on a CPU, perform inference with OpenVINO, and delve into the process of fine-tuning an LLM to 
develop a personalized Chatbot.

Approach: 
Intel OpenVINO is an open-source toolkit used for accelerating, optimizing and deploying LLMs (Large Language Models) 
on the edge and on the cloud irrespective of the hardware present on the computing machines. 
It also allows very large language models which require a lot of memory and space to be run locally on any intel machine. 
Using OpenVINO to optimize and run the language model can significantly affect CPU usage in the following ways: 
Imagine you have a traditional model and an optimized model: 
• Traditional Model: Requires a lot of CPU power to process data, causing high CPU usage and potentially slower 
response times. And we have to shift towards dedicated GPUs. 
• Optimized Model with OpenVINO: Uses less CPU power by making the computations simpler and more efficient, 
resulting in lower CPU usage and faster response times.

The Tiny LLaMA 1B chat model is used by us as it balances performance and efficiency, providing robust conversational capabilities 
while being lightweight enough to run on less powerful hardware. It offers faster inference times and requires less memory, making it 
suitable for applications where resources are limited. Additionally, its smaller size facilitates easier deployment and integration into 
various systems. However, the trade-off is that it may not perform as well as larger models in terms of generating highly nuanced or 
contextually rich responses.
 Model Size: Approximately 1 billion parameters.
 Using INT4 and INT8 precision for better compression and less load over the CPU.

 Steps Involved:
1. Configuring and Fetching the LLM Configuration File.
 2. Importing SUPPORTED_LLM_MODELS and Selecting Model Language.
 3. Generating and Executing Commands for Model Conversion to INT8 and INT4.
 4. Setting up OpenVINO configuration using certain parameters.
 5. Setting up Conversational AI with OpenVINO Model Integration.
 6. Setting up Gradio interface, to use the chatbot.


![image](https://github.com/user-attachments/assets/49bdae2e-cd75-45bf-81cf-31a5bc4c9851)


