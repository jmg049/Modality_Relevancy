# Understanding the Relevancy of Modality Information in Multimodal Machine Learning
Multimodal machine learning aims to improve the performance of a model, including accuracy, precision, and robustness,  that is trained using multiple modes of data such as audio, video and text. Recent research has improved these measures by focusing on the intersection of information between modalities. However, there is a lack of research that focuses on how a multimodal model utilizes unique modality information and how a target task changes the distribution of relevant modality information. Understanding the relevancy of each modality can help with the development of future multimodal models, quantifying model robustness when a modality is missing and understanding how the inference process depends on each modality. This paper investigates how multimodal models learn within and across modalities and how the distribution of relevant information per modality changes depending on the target task being carried out. To achieve this, two multimodal classifiers were trained for three different tasks using audio and video. Using these models, we demonstrate that depending on the target task, the amount of relevant modality information will change and that an individual modality may contain more relevant information than the intersection of all modalities for predicting the ground truth.
