# Cloudprojects


For the following projects:

create a docker image and upload it to your AWS space, connecting properly task and service


Available projects

**1. Asynchronous learning with Kafka**

Set up a Kafka messaging-based architecture as depicted in
https://github.com/alecrimi/mobula
where data should be uploaded and a watchdog is constantly looking for new data, requesting the training of the data through the river library, assume a simple case of classification as with the Sklearn library.

River library: https://riverml.xyz/latest/


**2. Deploy a retrivial-augmented generation (RAG) LLM using Chainlit, Haystack, ChromaDB and Mistral**

Deploy a retrivial-augmented generation (RAG) LLM using ChromaDB and Mistral as a vector database and Mistral LLM, either accessing the endpoint online or downloading it and putting the AWS repository (be aware of the size of the model you use). For NPL orchestration you can use Haystack.
For the augementation please use a recent scientific paper which cannot be already included in the Mistral Model.
I recommend Chainlit to have an easy front-end integration. Using more proper front-end (as Bootstrap or React is beyond the purpose of this project but welcome). 


**2. Deploy a retrivial-augmented generation (RAG) LLM using Chainlit, ChromaDB and Mistral**

Deploy a retrivial-augmented generation (RAG) LLM using ChromaDB and Mistral as a vector database and Mistral LLM, either accessing the endpoint online or downloading it and putting the AWS repository (be aware of the size of the model you use).
For the augementation please use a recent scientific paper which cannot be already included in the Mistral Model.
I recommend Chainlit to have an easy front-end integration. Using more proper front-end (as Bootstrap or React is beyond the purpose of this project but welcome). 

ChromaDB: https://www.trychroma.com/
HayStack: https://haystack.deepset.ai/
Chainlit https://chainlit.io/
Mistral AI: https://mistral.ai/


**3. Deploy a retrivial-augmented generation (RAG) LLM using Chainlit, Weaviate and Mistral**

Deploy a retrivial-augmented generation (RAG) LLM using Weaviate and Mistral as a vector database and Mistral LLM, either accessing the endpoint online or downloading it and putting the AWS repository (be aware of the size of the model you use).
For the augementation please use a recent scientific paper which cannot be already included in the Mistral Model.
I recommend Chainlit to have an easy front-end integration. Using more proper front-end (as Bootstrap or React is beyond the purpose of this project but welcome). 

Weaviate:  https://weaviate.io/ 
HayStack: https://haystack.deepset.ai/
Chainlit https://chainlit.io/
Mistral AI: https://mistral.ai/


**4. Deploy on AWS the GeminiPro vision model or even better LLAVA**

Read how multimodal are used, and deploy a query system even without a GUI or with simple NodeJs extension. 
Most of the tutorial online assumes you are using GoogleCloud, so the challenge is the portng on AWS.

Read the article
https://developers.google.com/solutions/content-driven/ai-images?continue=https%3A%2F%2Fdevelopers.google.com%2Flearn%2Fpathways%2Fsolution-ai-gemini-images%23article-https%3A%2F%2Fdevelopers.google.com%2Fsolutions%2Fcontent-driven%2Fai-images

Llava would be even better: https://llava-vl.github.io/
I have currently managed to deploy this model on a RaspberryPI 5 with 8GB RAM (current challenge RaspberryPI 4 with 2 GB RAM), so you should be able to put it on AWS
