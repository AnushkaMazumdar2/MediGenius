# 🏥 MediGenius: Your Personal Healthcare Bot 🩺
![MediGenius](https://github.com/SoheliPaul/MediGenius/assets/140196197/05621210-1882-4553-8598-04a41e1518d0)

**About the Project**

MediGenius is a desktop application developed by the HealthHackers, Anushka Mazumdar, and Soheli Paul, for the Intel OneAPI hackathon. It serves as a healthcare assistant designed to provide users with preliminary healthcare assistance in an accessible and user-friendly manner.

The application utilizes Python's tkinter library for the frontend, ensuring a simple and intuitive user interface. Users are prompted to enter their symptoms and the duration of their suffering. Based on this information, MediGenius leverages a predictive model trained on disease-symptom datasets. While the prediction may not be as accurate as a professional diagnosis, it offers valuable insights and guidance to users.

Additionally, if a user has been experiencing symptoms for more than 10 days, MediGenius proactively suggests seeking medical attention. It integrates with Google Maps to provide users with a list of nearby hospitals, ensuring timely access to medical care.

**Inspiration**

- 🌟 Addressing Healthcare Accessibility: Our inspiration stems from the pressing need to address healthcare accessibility issues, particularly in underserved communities.
  
- 🚀 Rising Need for Telemedicine: We recognized the growing importance of telemedicine and virtual healthcare consultations, especially in response to the COVID-19 pandemic, driving us to develop a digital healthcare solution.

**Social Impact**

- 💪 Empowerment: The application empowers individuals to take proactive steps towards managing their health by providing timely information and guidance.
  
- 🌍 Reduced Healthcare Disparities: By bridging the gap between individuals and healthcare services, MediGenius helps reduce disparities in healthcare access and outcomes.
  
- 📚 Health Literacy: It promotes health literacy by educating users about common symptoms and potential diseases, enabling them to make informed decisions about their health.
  
- ⏰ Timely Intervention: Prompting users to seek medical attention after prolonged symptoms ensure timely intervention, potentially preventing complications and improving health outcomes.

**Project Building 🛠️**

- **Frontend Development:**
For the frontend of the MediGenius application, we opted to use Python's tkinter library. Tkinter is a built-in library in Python, providing a simple and efficient way to create graphical user interfaces. We chose tkinter for its ease of use and cross-platform compatibility, ensuring that the application can run smoothly on various operating systems.

- **Data Handling:**
The core of MediGenius lies in its ability to analyze user-provided symptoms and predict potential diseases. To accomplish this, we structured disease and symptom data in a CSV file. This format allows for easy access and manipulation of the data within Python. By storing the data in a CSV file, we ensure flexibility and scalability, enabling future updates and additions to the disease-symptom database.

- **Predictive Model:**
MediGenius utilizes a predictive model trained on disease-symptom datasets to analyze user-provided symptoms and predict potential illnesses. Specifically, we leveraged Hugging Face's NER (Named Entity Recognition) model, pretrained on disease datasets. This model is capable of identifying and extracting disease-related entities from text, allowing us to match user symptoms to potential diseases. While the prediction may not be as accurate as a professional diagnosis, it serves as a valuable tool for preliminary healthcare assistance.

- **Dependencies:**
To implement various functionalities and ensure the smooth operation of the application, we relied on several Python libraries and dependencies. These include:

  - nltk: Natural Language Toolkit for natural language processing tasks.
  - numpy: Fundamental package for scientific computing with Python.
  - pandas: Data manipulation and analysis library.
  - regex: Library for regular expressions.
  - requests: HTTP library for making requests.
  - scikit-learn: Machine learning library for predictive modeling.
  - scipy: Scientific computing library.
  - spacy: Library for natural language processing tasks.
  - torch: Machine learning library for deep learning tasks.
  - transformers: Library for natural language processing tasks, including pretrained models.

By leveraging these dependencies, we were able to implement various features and functionalities within the MediGenius application, ensuring its effectiveness and reliability in providing preliminary healthcare assistance to users.

**Demo Video**

The video below demonstrates how our chatbot assists people in diagnosing early symptoms, and informing them about what they may have, and also asking them to take precautionary measures.



https://github.com/AnushkaMazumdar2/MediGenius/assets/140642505/ba1bf750-1138-45ef-bc9e-538af8d70f6c



**Use of Intel API**

**🚀 Usage **

1. Run the desktop application.
2. MediGenius will greet you and ask for your name.
3. Enter your symptoms one by one when prompted.
4. MediGenius will predict possible diseases based on your symptoms.
5. If suffering for more than 10 days, MediGenius suggests nearby hospitals using Google Maps.

**🔮 Future Scope**

Our future plans include integrating mental health disease prediction into MediGenius. With mental health issues becoming increasingly prevalent, especially among the youth, this addition will further enhance the bot's utility and impact.

Feel free to contribute and improve the functionality of MediGenius!
