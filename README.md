# Aurum AI🧠

**Aurum AI** is a cutting-edge personal finance and investment assistant designed to empower retail investors. It combines a suite of powerful tools to provide personalized financial insights and recommendations.

### 🔍 Overview

At Mumbai Hacks 2024, we tackled the finance domain within the investment track, creating an assistant that seamlessly integrates AI-driven insights for enhanced investment strategies. Aurum AI's primary features include:

1. **Phi 3.5-Based Real-Time RAG Chat Assistant**  
   A conversational AI chat assistant answers personal finance questions in real-time, using Phi 3.5 to retrieve and generate accurate responses.

2. **Mutual Fund Recommendation Engine**  
   Leveraging a machine learning model trained on a custom-scraped dataset of 14,000 data points, this engine provides personalized mutual fund recommendations based on user requirements.

3. **IPO Prediction Neural Network**  
   Our custom black box neural network, trained on a meticulously updated dataset of 300 data points, achieves **100% accuracy** in identifying viable IPOs for investment.

---

### 🛠️ Tech Stack

We utilized the following technologies to build Aurum AI:

- **Backend**: Django, FastAPI, SQLite
- **Frontend**: HTMX, Tailwind CSS
- **Machine Learning**: TensorFlow, Keras, Scikit-learn, Statsmodels, Spacy
- **Data Processing**: Pandas, NumPy

---

### 🚀 Features

- **Real-Time Chat**: Seamlessly answer finance-related queries.
- **Personalized Investment Insights**: Tailored mutual fund suggestions based on 14k+ data points.
- **Accurate IPO Predictions**: A neural network providing reliable IPO recommendations with unmatched precision.

---

### ⚙️ Getting Started

To set up and run Aurum AI, follow these steps:

#### 1. Environment Setup

1. Clone this repository:
   ```bash
   git clone github.com/Aurum-MumbaiHacks2024/aurum
   cd aurum-ai
   ```
2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

#### 2. Install Backend Dependencies

```bash
pip install -r requirements.txt
```

#### 3. Frontend Setup

```bash
npm install
npm run build:css
npm run dev
```

#### 4. Start the Backend API Services

- Run FastAPI for API endpoints:
   ```bash
   uvicorn app:app --reload
   ```
- Alternatively, use FastAPI's `run` command:
   ```bash
   fastapi run app.py
   ```

- Run Django for additional backend services:
   ```bash
   python manage.py runserver
   ```

---


### 🎯 Future Plans

- **Expand Financial Services**: Add advisory features tailored for venture capitalists (VCs), offering investment insights and portfolio guidance.
- **Commercialization**: Introduce a subscription-based payment model, allowing users to access advanced analytics and premium support.

--- 

### 🤝 Contributors

- [Varad Joshi](https://github.com/Varad-13)
- [Meet Jamsutkar](https://github.com/MeJaM35)
- [Rohan Waghode](https://github.com/RSW1511)
- [Vaishnavi Saarang](https://github.com/RSW1511)
  
For feedback or collaboration, reach out to us at [varad,gcs@gmail.com](mailto:varad.gcs@gmail.com).



--- 


