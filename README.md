#  **InfoElixir**

### **Team Members**
- Rashmi R
- Sneh Shah
- Shreyan Manher

## **Theme: Improving Work Efficiency**

### **Problem Statement: Knowledge Distiller App**

## **Introduction**
- InfoElixir is designed to streamline study material organization and retrieval.
- The app supports multiple input formats: text, images, handwritten notes, and audio.
- It automatically parses and extracts meaningful data from these formats.
- A personalized knowledge graph connects key concepts for better study efficiency.
- The chatbot enables quick information retrieval based on individual study needs.

## **Approach**

1. **User Authentication**:  
   Users can log in or register to access their personalized dashboard.
   
2. **Dashboard & File Upload**:  
   Users upload study materials which dynamically update their personal knowledge graph.
   
3. **Knowledge Graph**:  
   Neo4j graph database is integrated via its API to create and visualize knowledge graphs.
   
4. **Chatbot Integration**:  
   A chatbot powered by OpenAI and backed by Neo4j's API retrieves relevant information from the knowledge graph.
   
5. **Collaborative Features**:  
   Users can plot and view graphs of their friends, fostering a collaborative learning environment.

## **Tech Stack**

### **Backend**
- Node.js
- MySQL
- Flask
- Flask-RESTx

### **Frontend**
- HTML, CSS (EJS templating)
- Streamlit

### **Chatbot**
- Streamlit
- OpenAI

### **Graph Database**
- Neo4j: **Retrieval augmented generation based on the Neo4j knowledge graph**

## **System Architecture Diagram**
![image](https://github.com/user-attachments/assets/58de9d74-720a-48fd-85ea-ef40f3bcbf83)


**Sample Knowledge Graph**
![c9530b65-3d29-4744-adce-6db35de3620f](https://github.com/user-attachments/assets/dab86ac2-f70b-462f-9639-541b2a774993)

## **Conclusion**
our app offers an innovative solution to enhance students’ learning efficiency by organizing study materials and connecting key concepts through personalized knowledge graphs. With multi-format input support and seamless information retrieval via an intelligent chatbot, the app provides a tailored and collaborative study experience.
