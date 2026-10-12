# Syed Zaid Ali

AI/ML engineer focused on RAG systems, LLM agents, and applied deep learning.

## About me

I graduated in Computer Science Engineering from Gyan Ganga College of Technology, Jabalpur (2022–2026). Over the past year I've mostly been building with LLMs — RAG pipelines, multi-agent systems, that kind of thing — along with a few more traditional machine learning and deep learning projects.

What I care about most is reliability. It's easy to get an LLM demo to look impressive; it's harder to get it to consistently ground its answers in real sources and fail gracefully when it doesn't know something. A lot of my project work has been about evaluation and catching failure modes rather than just getting a model to run.

Based in Jabalpur, India. Currently looking for AI Engineer or Data Science roles.

## Skills

**Languages & data:** Python, SQL, NumPy, Pandas, Matplotlib

**ML & deep learning:** TensorFlow, Keras, Scikit-learn, model evaluation

**LLM engineering & NLP:** LangChain, RAG, prompt engineering, AI agents, HuggingFace Transformers, embeddings, vector search, transformer models

**Tools:** Git, GitHub, AWS, FastAPI, Docker

## Projects

**ResearchMind: Multi-Agent Research System**
Built a four-stage multi-agent pipeline that turns any topic into a structured report: search agent, page-scraping
agent, report writer, and a critic that scores the output out of 10. Created tool-using LangChain agents with Tavily search and a BeautifulSoup scraper, running entirely on free-tier Gemini and Tavily APIs. Fixed a reliability bug where the model answered from memory without searching, by verifying the search tool
was called, retrying once, and failing safely with a clear error. Developed a Streamlit app with a live progress tracker, tabbed results, Markdown export, and rate-limit error
handling.


**You-Can't-Fool-Me: Deepfake Detection System**
Developed an AI-powered deepfake detection system using EfficientNetV2B3 and TensorFlow/Keras to classify face images as real or fake. Trained on the DF40 dataset, the model leverages transfer learning to generate predictions with confidence scores. Built an interactive Streamlit web application for image-based detection and evaluated model performance using accuracy, precision, recall, F1-score, and a confusion matrix. Tech Stack: Python, TensorFlow, Keras, EfficientNetV2B3, Streamlit, NumPy, Scikit-learn.

**Anomaly Detection System**
Anomaly detection on a time-series dataset with 1.6M+ records and severe class imbalance. Engineered 130+ features and built ensemble models with LightGBM and XGBoost, then spent a good chunk of time on threshold optimization to get the F1-score up to 0.82 — accuracy alone was meaningless given how imbalanced the classes were.

## Certifications

- Machine Learning for Engineering and Science Applications — NPTEL, IIT Madras
- National Entrepreneurship Challenge (NEC) — IIT Bombay

## Education

**Bachelor of Technology in Computer Science Engineering**
Gyan Ganga College of Technology, Jabalpur — 2022 to 2026, CGPA 7.35/10.00

**Higher Secondary (Class XII)**
Small Wonders Senior Secondary School, Jabalpur — 2022

## Contact

Email: syedzaidali004@gmail.com
LinkedIn: [https://www.linkedin.com/in/syedzaidaliii/]
GitHub: [(https://github.com/syedzaidaliii/)]
