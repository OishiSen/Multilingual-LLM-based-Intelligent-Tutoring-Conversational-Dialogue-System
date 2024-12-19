# Multilingual-LLM-based-Intelligent-Tutoring-Conversational-Dialogue-System
Development of a Multilingual LLM-Based Intelligent Tutoring Conversational Dialogue System" aims to create an advanced, multilingual AI chatbot for tutoring high school students in Physics.

## Overview  
Developed as part of an internship at **C-DAC Kolkata**, this project focuses on creating a multilingual intelligent tutoring system designed to assist high school students (grades 11 and 12) in understanding Physics concepts. The chatbot uses cutting-edge Large Language Models (LLMs) to provide real-time, interactive, and personalized tutoring, breaking down complex topics into simpler explanations. By supporting multiple languages, it ensures inclusivity and accessibility for students from diverse linguistic and cultural backgrounds.  

## Features  
- **Multilingual Support**: Offers assistance in various languages, making quality education accessible to a broader audience.  
- **Physics-Specific Expertise**: Aligned with the 11th and 12th-grade curriculum for accurate and relevant guidance.  
- **Interactive and Engaging**: Simulates a human tutor for an intuitive learning experience.  
- **Real-Time Responses**: Provides instant solutions to students' questions.  
- **Personalized Learning**: Adapts responses to individual students' progress and needs.  

## System Requirements  
- **Processor**: Intel Core i5/AMD Ryzen 5 (8th Gen or newer).  
- **RAM**: Minimum 16 GB (32 GB recommended).  
- **GPU**: NVIDIA Tesla T4/V100 with at least 12 GB VRAM.  
- **Storage**: 50 GB of free disk space.  
- **Operating System**: Ubuntu Linux or Windows (with WSL2). Google Colab is also supported for cloud-based workflows.  

## Libraries and Tools  
- **Unsloth**: For efficient LLM management.  
- **Torch**: Deep learning framework for training and computations.  
- **Datasets**: Prepares and processes training data.  
- **TRL**: Fine-tunes models using reinforcement learning.  
- **Transformers**: Tokenization and natural language processing.  
- **Google Colab Drive**: Cloud-based data handling.  
- **Pandas**: For dataset organization and analysis.  

## Methodology  
1. **Requirement Analysis**: Collaborate with educators to identify curriculum needs and language preferences.  
2. **Dataset Preparation**: Collect and preprocess Physics question-answer datasets covering diverse topics and languages.  
3. **Model Fine-Tuning**: Train a pre-trained LLM with subject-specific data for accuracy and context-aware responses.  
4. **System Development**: Build a modular architecture with a user-friendly interface for seamless interaction.  
5. **Optimization**: Apply 4-bit quantization for efficient resource usage.  
6. **Testing and Feedback**: Validate the system with real users and refine it based on feedback.  
7. **Deployment**: Launch the chatbot for student use with scalability and reliability.  

## Challenges  
- Achieving precise multilingual understanding and responses.  
- Curating a high-quality dataset for training.  
- Balancing computational efficiency and system scalability.  
- Delivering in-depth Physics expertise for diverse queries.  

## Future Scope  
1. **Expansion to Other Subjects**: Extend support to Chemistry, Mathematics, and beyond.  
2. **Virtual Labs**: Incorporate interactive Physics simulations.  
3. **Voice Interaction**: Add speech recognition for enhanced accessibility.  
4. **Gamification**: Introduce quizzes and rewards for engagement.  
5. **Offline Capabilities**: Develop features for areas with limited internet connectivity.  
6. **Integration with LMS**: Seamlessly connect with platforms like Moodle or Google Classroom.  

## Getting Started  
1. Clone the repository:  
   ```bash  
   git clone <repository_url>  
   ```  
2. Install the dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run the application:  
   ```bash  
   python app.py  
   ```  

## Acknowledgments  
This project was developed as part of an internship at **C-DAC Kolkata** under the mentorship of **Mr. Bibekananda Kundu** and guidance from **Dr. Asok Bandyopadhyay**. Their support and expertise were instrumental in the project's success.  
