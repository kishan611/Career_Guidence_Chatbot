# Career Guidance Chatbot

## Overview
The Career Guidance Chatbot is designed to help users explore career options, prepare for interviews, understand industry trends, and adapt to future job market changes. It utilizes Natural Language Processing (NLP) to understand user queries and provide relevant guidance. The chatbot's knowledge spans various domains, including technology, healthcare, sustainability, and more.

---

## Features
- **Personalized Career Guidance:** Offers insights tailored to user queries about different career paths.
- **Future Trends Analysis:** Provides information on emerging roles influenced by AI, geopolitical tensions, and climate change.
- **Interactive Interface:** Engage with the chatbot through a user-friendly web application.
- **Customizable Intents:** Modify the `intents.json` file to add or refine chatbot responses.
- **Conversation History:** Saves interaction logs for future reference and analysis.

---

## Technologies Used
- **Python** for backend logic and NLP processing.
- **NLTK** for text tokenization and preprocessing.
- **Scikit-learn** for any machine learning-based enhancements.
- **Streamlit** for building the web interface.
- **JSON** for managing chatbot intents and responses.

---

## Installation

### 1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-directory>
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Required Packages
```bash
pip install -r requirements.txt
```

### 4. Download NLTK Data
```python
import nltk
nltk.download('punkt')
```

---

## Usage
To launch the Career Guidance Chatbot, run the following command:
```bash
streamlit run app.py
```

This will open the chatbot interface in your default web browser. Users can type their questions about careers and receive instant responses.

---

## Intents Data
The chatbot's logic is governed by the `intents.json` file, which defines various topics, patterns, and responses. You can customize this file to include additional career domains or refine existing answers.

---

## Career Domains Covered
- **Technology:** Insights into AI, robotics, and cybersecurity careers.
- **Healthcare:** Roles in telemedicine, mental health, and bioinformatics.
- **Sustainability:** Careers in green tech, renewable energy, and environmental science.
- **Creative Industries:** Opportunities in digital content, virtual storytelling, and design.
- **Geopolitical Influence:** Guidance on roles affected by conflicts, diplomacy, and global trends.
- **Education:** Emerging careers in e-learning, lifelong learning, and edtech.

---

## Conversation History
User interactions are logged in a CSV file (`chat_log.csv`) for review and analysis. The "Conversation History" option in the web app sidebar allows users to revisit past interactions.

---

## Contributing
We welcome contributions! If you have ideas for improving the chatbot or expanding its knowledge base, feel free to open an issue or submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- **NLTK** for natural language processing.
- **Scikit-learn** for machine learning enhancements.
- **Streamlit** for creating the interactive web interface.
- Inspiration from real-world career challenges and trends shaping the future of work.

---

Replace `<repository-url>` and `<repository-directory>` with the appropriate details for your repository. Adjust sections as necessary to better fit your project specifics.
