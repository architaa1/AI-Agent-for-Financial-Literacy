# 🤖 AI Agent for Digital Financial Literacy

This project was developed as part of the **IBM SkillsBuild Internship (AI & Cloud)** conducted by **Edunet Foundation in collaboration with AICTE**.  
The project leverages **Retrieval-Augmented Generation (RAG)** with **IBM Granite / Watsonx.ai models** to build an intelligent assistant that simplifies financial concepts for users in India and beyond.  

---

## 🏦 Problem Statement
Many users in India struggle with understanding digital finance tools like **UPI, online banking, EMI, and budgeting**.  
Due to limited awareness, they are prone to **online scams, fraud, and poor loan decisions**.  

There is a need for a **multilingual AI agent** that can provide **step-by-step financial guidance**, protect users from fraud, and promote **financial literacy in a culturally inclusive way**.  

---

## 💡 Proposed Solution
An **AI-powered chatbot** that:
- Answers user queries on UPI, EMI, budgeting, loans, and scams.  
- Works in **English, Hindi, and regional languages**.  
- Uses **RAG** to fetch data from reliable sources like **NPCI, RBI, SEBI**.  
- Provides **personalized, simple, and safe financial guidance**.  
- Deployed using **IBM Cloud Lite (Watsonx.ai Agentic Lab)**.  

---

## 🔧 System Approach
**Platform:** IBM Cloud Lite  
**Tools Used:**
- Search Tool (document retrieval)  
- Code Interpreter (EMI, interest, savings calculations)  
- File Tool (RAG with financial documents)  
- Translator Tool (multilingual support)  
- Memory Tool (context awareness)  

**Data Sources:**
- [NPCI](https://www.npci.org.in/) (UPI guidelines)  
- [RBI](https://www.rbi.org.in/) (fraud prevention & financial safety)  
- [SEBI](https://www.sebi.gov.in/) (investment awareness)  
- [Digital India](https://www.digitalindia.gov.in/) initiatives  

---

## 🧠 Algorithm & Deployment
1. **RAG Architecture**  
   - Searches uploaded docs (PDF/JSON) based on user query  
   - Retrieves top documents  
   - Uses **IBM Granite / Mistral-large** to generate contextual answers  

2. **Multilingual Support**  
   - Translator tool enables Hindi & other languages  
   - Context preserved via memory  

3. **Deployment Flow**  
   Watsonx.ai Sandbox → Associate Runtime → Create Agent → Deploy on IBM Cloud  

---

## 📊 Results
- Accurate answers in **English & Hindi**.  
- Guides users with **step-by-step responses**.  
- Promotes safe and inclusive financial literacy.  

---

## 📈 Future Scope
- Voice-based interaction for accessibility  
- Expand support to more languages (Tamil, Bengali, etc.)  
- Real-time API integration for **interest rates & financial offers**  
- Mobile app or WhatsApp bot deployment  
- Visual EMI calculators and interactive finance tools  

---

##🙌 Acknowledgments

@IBM for Watsonx.ai & Granite Models

@Edunet Foundation

@AICTE
