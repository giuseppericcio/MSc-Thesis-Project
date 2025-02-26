# 💊 MediCARE Framework
**MediCARE** is an advanced framework designed to revolutionize personalized medical recommendations through the integration of Machine Learning techniques and Graph Neural Networks (GNNs). Developed during MSc Thesis Internship at University of Naples "Federico II" in collaboration with _PicusLab_, this framework aims to optimize clinical decision-making by leveraging Electronic Health Records (EHRs) data, within the [MIMIC-III](https://physionet.org/content/mimiciii/1.4/) database (noteevents). The overall framework has been integrated within the open-source _PyHealth_ library (check the fork repo [here](https://github.com/LaErre9/PyHealth)).

## ✨ Features
- **Personalized Recommendations:** MediCARE utilizes state-of-the-art machine learning algorithms to generate personalized medical recommendations tailored to individual patient profiles;
- **Graph Representation:** The framework employs Heterogeneous Graph representations to capture complex relationships between medical concepts extracted from EHR data through _Named Entity Recognition_ and _Entity Linking_ (NER+EL), ensuring a comprehensive understanding of patient health;
- **Integration of External Knowledge:** MediCARE enriches patient graphs with static Medical Knowledge Graphs, such as [DRKG](https://github.com/gnn4dr/DRKG) and [SympGAN](http://www.sympgan.org/), enhancing the accuracy and depth of medical recommendations by introducing additional medical concepts and relationships;
- **Explainable AI (XAI):** The framework incorporates eXplainable Artificial Intelligence (XAI) methods such as _GNNExplainer_ and _Integrated Gradients_ to interpret the recommendations and internal mechanims of the GNN models;
- **Multi Agent Collaboration LLMs:** MediCARE with this solution generate, discuss, and revise comprehensive assessments to explain the predictions of the model.

## ⚙️ Project Workflow
![MediCARE](https://github.com/giuseppericcio/MSc-Thesis-Project/assets/7995055/52ba9438-e5f4-4b81-8c1a-36ee66612c77)

## 🛠️ Tools used
<div align="center">
    <img src="https://th.bing.com/th/id/OIP.LgBY7F5nE1w8PouW1rcKxAAAAA?rs=1&pid=ImgDetMain" alt="PyG" height="45">
    <img src="https://th.bing.com/th/id/R.57a29f26dfe89aab83678539e9747b98?rik=iihjn%2boAqZfTng&pid=ImgRaw&r=0" alt="PyHealth" height="45">
    <img src="https://github.com/CogStack/MedCAT/blob/master/media/cat-logo.png?raw=true" alt="MedCat" height="45">
    <img src="https://th.bing.com/th/id/R.7494e83354e2662240d06630cc31f08d?rik=9tIRLZpYS9oTfQ&pid=ImgRaw&r=0" alt="Python" height="45">
    <img src="https://th.bing.com/th/id/OIP.8CuA1RVvzjfpIVXMWW_TFQHaBj?pid=ImgDet&rs=1" alt="OpenAI" height="45">
    <img src="https://microsoft.github.io/autogen/img/ag.svg" alt="AutoGen" height="45">    
    <img src="https://streamlit.io/images/brand/streamlit-logo-primary-colormark-darktext.svg" alt="Streamlit" height="45">
</div>

## ⚠️ Warning
**It is essential to note that MIMIC-III** **contains sensitive patient data** and, therefore, must be handled with the utmost care and in compliance with privacy regulations and institutional policies. Before using the dataset, carefully review and adhere to the guidelines provided by the MIMIC team and consult your local ethics committee.

## ✅ Project realised for demonstration and educational purposes only
**Copyright © 2024** - MediCARE Framework project carried out for the MSc Internship held at the University of Naples "Federico II". Realised for demonstration and teaching purposes only.
<br>
**Antonio Romano, Giuseppe Riccio**
