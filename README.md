# 🌾 AgriVision: SMART CROP MANAGEMENT 🚜
Welcome to AgriVision, the cutting-edge platform designed to revolutionize crop management with advanced AI and deep learning techniques. Whether you're a farmer aiming to enhance your yield, an agricultural scientist, or just someone passionate about technology in farming, this tool is built for you!

## 📜 Abstract
Agriculture is the cornerstone of many economies, particularly in developing nations. However, modern agriculture faces numerous challenges, including plant diseases, soil depletion, and climate change, which threaten food security and disrupt farmers' livelihoods. AgriVision is a revolutionary platform that leverages Artificial Intelligence (AI) and Machine Learning (ML) to transform traditional farming practices. It provides a comprehensive crop management system for optimal crop health, soil management, and resource utilization.

AgriVision incorporates cutting-edge technologies such as image recognition for crop disease detection, data analysis for soil evaluation, and machine learning algorithms for actionable insights. Built using Python and Streamlit, it offers an intuitive interface with modules for crop disease prediction, soil composition detection, soil type classification, and weather forecasting.

This project report details AgriVision’s journey from concept to implementation, including methodologies, tools, and technologies employed. The results showcase significant advancements in early disease diagnosis, soil health assessment, and overall farming efficiency, positioning AI as a transformative force in modern agriculture.

## 🌱 Introduction
Agriculture, a vital component of many developing economies, faces unprecedented challenges, including climate change, soil degradation, and the emergence of new plant diseases. Traditional farming practices, passed down through generations, are often insufficient to meet these modern challenges. AgriVision addresses this gap by integrating advanced technological solutions into a user-friendly platform that empowers farmers to make informed, data-driven decisions.

AgriVision simplifies the complexities of modern farming, offering tools for early disease detection, soil analysis, and weather forecasting, all accessible through an easy-to-use interface. The platform supports multiple languages, ensuring that even farmers in remote areas can benefit from the latest agricultural technologies.

## 🎯 Objectives
**Empower Farmers with Technology:** Democratize access to modern agricultural technologies, ensuring usability even for those with limited technical skills.

**Improve Crop and Disease Detection:** Utilize advanced image analysis to enable early detection and intervention of crop diseases, preventing widespread crop loss.

**Accurate Soil Composition Prediction:** Provide farmers with detailed soil composition analysis, helping them optimize crop selection and soil management.

**Soil Type Prediction:** Offer precise soil type classification through image recognition, aiding farmers in making informed decisions based on local soil characteristics.

**Immediate Assistance and Customized Guidance:** Deliver real-time, context-specific recommendations to farmers, reducing uncertainty and risk.

**Implement Retrieval-Augmented Generation (RAG):** Enhance decision support with RAG technology, providing relevant and comprehensive responses to farmers' queries.

**Support Multilingual Needs:** Break language barriers by offering multilingual support, making advanced agricultural advice accessible to a wider audience.

## 🔍 AgriVision in Detail
### Proposed System
*System Description:* AgriVision is a comprehensive agricultural platform designed to address critical challenges in modern farming. It simplifies complex agricultural tasks, automates essential processes, and delivers actionable insights to farmers, ultimately enhancing productivity and accuracy in farming operations.

### 🌟 Features at a Glance:

**1. Crop Disease Detection 🌱**
Precision at its best: Detect crop diseases with a whopping 99% accuracy!
*Why it matters:* Early detection means you can save your crops before the disease spreads, leading to healthier yields.

**2. Soil Composition & Type Prediction 🌍**
*Accuracy:* Our soil composition model achieves 88% accuracy, focusing on critical factors like sand and gravel proportions to determine water holding capacity.
*A Beta Feature:* Soil type prediction stands at 87.5% accuracy. We’ve included a dynamic dropdown feature that allows users to manually input location data for precise soil type information.
*Innovative yet Practical:* This two-pronged approach ensures you get both the latest AI-driven predictions and reliable, data-backed soil type information.

**3. Weather Prediction Module ☀️🌧️**
*Real-Time Insights:* Stay ahead of weather patterns with our predictive model, allowing you to make informed decisions to optimize crop health and yield.
*Localized Accuracy:* Combine temperature, precipitation, and other elements to refine your farming strategies.

**4. RAG (Retrieval-Augmented Generation) with Reciprocal Rank Fusion 📊**
*Get Reports on Demand:* Our "Get Report" module delivers specific, actionable insights for managing crops like oranges in black soil, integrating soil health, disease management, and weather patterns.
*Precision & Tailoring:* Unlike generic models, our system provides contextually precise, tailored advice, minimizing the risk of misinformation.

**🔖Why AgriVision’s RAG is Superior to Generic LLMs:**

*Contextual Precision:* AgriVision delivers specific, up-to-date information relevant to the user’s query, ensuring accuracy and relevance.
*Tailored Approach:* Our platform provides actionable solutions tailored to individual farmer’s needs, unlike generic LLMs which offer generalized advice.
*Reduced Risk of Hallucinations:* Grounded in verified sources, AgriVision minimizes errors and provides trustworthy information.
*Farmer-Friendly:* Information is presented in a way that is easy for farmers to understand and implement, making it more practical.
*Reliability and Transparency:* AgriVision anchors responses in traceable source documents, providing users with credibility and transparency.
*Real-time Updates:* Unlike generic LLMs, our model continuously adapts to new information without the need for iterative prompting.

**5. Chat with RAG 💬**
*Interactive Support:* Engage with our Retrieval-Augmented Generation (RAG) chat to receive real-time, document-based answers to your agricultural queries.
*Reliable & Transparent:* Responses are grounded in verified sources, ensuring trustworthiness and immediate applicability.

**6. Multilingual Support 🌐**
*Accessible to All:* The platform is fully translated into multiple languages including Telugu, Tamil, Marathi, Hindi, and English, ensuring no one is left behind.
*Consistent Experience:* Every feature, report, and insight is available in your preferred language for seamless interaction.

## ⚙️ Working Methodology
**Browse for Crop Image to Detect:**
*How it works:* Users upload images of crops, which are analyzed using computer vision techniques and deep learning models like ResNet to identify crop species and diagnose diseases.
*Objective:* Early detection of crop diseases for timely intervention.

**Upload Image of Soil to Analyze:**
*Gravel and Sand Percentage Detection:* Analyzes soil images to estimate the sand and gravel content, helping assess soil quality.
*Soil Type Classification:* Classifies soil type based on image analysis, providing location-specific recommendations.

**Weather Forecasting:**
*How it works:* Retrieves and analyzes historical weather data and forecasts weather conditions for the next 15 days, aiding in informed decision-making.

**Reciprocal Rank Fusion with RAG:**
*How it works:* Integrates RAG technology to generate comprehensive reports, including disease diagnosis, treatment options, soil health insights, and weather impact analysis.

**Multilingual Support:**
*How it works:* Allows users to select their preferred language, ensuring that the platform’s insights and recommendations are accessible in the user's native language.

## 📊 Conclusion
AgriVision is poised to revolutionize the agricultural sector by providing farmers with the tools they need to overcome modern challenges. By combining advanced technologies into a single, user-friendly platform, AgriVision offers a powerful solution for improving crop health, soil management, and overall farm productivity. With its focus on accessibility and accuracy, AgriVision bridges the gap between traditional farming practices and modern technological advancements, paving the way for a more sustainable and prosperous future in agriculture.

## 🚀 Getting Started: Installation Guide
Ready to dive in? Follow these steps to set up AgriVision on your local machine:

### 1. Download the Repository 📂
*Option 1:* Download the repository as a ZIP file and extract it to your desired location.
*Option 2:* Clone the repo using Git:
          git clone <your-repo-link>

### 2. Create a Virtual Environment 🌐
Open Anaconda PowerShell and navigate to the folder where you want to set up the project.
*Create a virtual environment:*
      conda create --name agrivision-env python=3.9
*(Feel free to use the LTS or latest Python version you prefer)*

### 3. Open the Project in Your IDE 💻
Navigate to the unzipped folder.
Open the project in PyCharm or VS Code—whichever you prefer.

### 4. Install Dependencies 📦
Ensure your virtual environment is activated:
      conda activate agrivision-env

Install all required dependencies using the requirements.txt file:
      pip install -r requirements.txt

### 5. Set Up API Keys 🔑
Obtain your Visual Crossing Weather API and OpenAI API keys.
Add these keys to the project settings to utilize weather prediction and RRF RAG functionalities.

### 6. Install Streamlit 📊
Install Streamlit if it's not already included:
      pip install streamlit
Verify the installation and compatibility:
      streamlit --version

### 7. Run the Application 🏃‍♂️
In the terminal, navigate to the directory containing your main application file.
*Launch the app:*
    streamlit run <app-name>.py
The application will open in your default web browser, ready for interaction.

### 8. Interact with the App 🌾
Upload crop and soil images for real-time predictions.
Generate detailed reports using RAG assistance tailored to your needs.

### 9. Have Questions? 🤔
Use the RRF RAG Chat feature to get personalized answers and recommendations based on your agricultural queries.

## 🤝 Contributing
We welcome contributions to enhance AgriVision! Feel free to fork the repository and submit a pull request with your improvements.

## 📜 License
This project is licensed under the Apache 2.0 license.
