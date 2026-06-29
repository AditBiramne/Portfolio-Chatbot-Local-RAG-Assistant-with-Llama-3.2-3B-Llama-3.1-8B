# Adit Biramne — Portfolio Chatbot Knowledge Base

> This file is the single source of truth for the portfolio chatbot. All answers must be grounded in this document only.

---

## 1. BASIC INFO

- **Full Name:** Adit Biramne
- **Location:** Navi Mumbai, India
- **Degree:** B.E. in Computer Engineering — MGM College of Engineering and Technology, Kamothe (University of Mumbai)
- **Graduation Year:** 2026
- **Email:** aditbiramne2@gmail.com
- **Mobile:** +91 8850261086
- **LinkedIn:** https://linkedin.com/in/adit-biramne
- **GitHub:** https://github.com/AditBiramne

---

## 2. PROFESSIONAL SUMMARY

**Professional Summary**

AI/ML Engineer and Computer Engineering student with hands-on experience in Natural Language Processing (NLP), sentiment analysis, and end-to-end machine learning pipelines. Proven track record of building AI-powered applications, including news synthesis and summarization systems, resume parsing tools, and sentiment-driven stock forecasting models. Skilled in Python, PyTorch, TensorFlow, Scikit-learn, and Hugging Face Transformers, with experience designing and deploying full-stack ML pipelines from data ingestion through model inference. Passionate about turning messy, unstructured information into clear, actionable insights, and currently seeking his next role in AI/ML or NLP.

---

## 3. INTERNSHIP EXPERIENCE

### Indian Oil Corporation Ltd. (IOCL) — AI/ML Intern

**Duration:** June 2025 – August 2025
**Location:** Head Office, Bandra, Mumbai

- Built a real-time **Negative News Article Portal** for IOCL to detect negative media coverage about the company using VADER sentiment analysis and BERT models, achieving 90%+ sentiment accuracy.
- Designed and deployed a **full end-to-end AI pipeline** covering data ingestion, preprocessing, model inference, and a Flask-based web interface, serving insights to executive stakeholders.
- Reduced dependency on manual media monitoring across departments — a direct operational impact on a large-scale enterprise.
- (Per GitHub profile, this internship was also referred to as a Data Science Intern role, based in the Networks & SAP Department, gaining hands-on experience in enterprise infrastructure and ERP systems alongside the AI/ML work.)
- Tech used: Python, VADER, BERT, Flask, NLP, HuggingFace Transformers.

---

### Prudent Infotech — AI Intern

- Worked on analysing and understanding the difference in usage, cost, and other aspects of LLMs (Large Language Models) in comparison to GPT-4.1 for production chatbot use cases.
- Analysed other requirements to optimize the running of open-source models in production environments.
- Tech used: LLMs, GPT-4.1, Open-Source Models, Production Chatbot Optimization.

---

### Ganishka Technologies — AI/ML Intern

**Duration:** July 2024 – December 2024
**Location:** Mumbai, Maharashtra

- Developed and evaluated classification models (SVM, Decision Trees, Linear Regression) using scikit-learn on real datasets, optimizing preprocessing pipelines to improve model performance.
- Built text extraction modules using spaCy for Named Entity Recognition (NER) — this work became the **Resume Screening System** project.
- Managed deadlines, code reviews, and iterative model improvements over a 6-month engagement, working as part of the product team.
- Tech used: Python, Scikit-learn, spaCy, NER, pdfplumber, Flask.

---

## 4. PROJECTS

### Project 1: AI-Powered News Synthesizer _(Published Research)_

**Problem:** Misinformation and fake news are rampant online. Motivated by the "Operation Sindoor" media coverage, Adit noticed a surge of fake news and politically twisted narratives, while traditional, editorially-reviewed newspapers remained the most reliable source — but manually cross-referencing multiple papers is time-consuming.
**What Adit built:** An AI-Powered Newspaper Synthesizer that collects news from multiple reliable sources, synthesizes and summarizes them using AI + NLP (BART-like summarization via HuggingFace Transformers and BERT), and presents them on an interactive, dark-mode web interface with clickable source validation. Built during the IOCL internship; also built a dedicated IOC-specific negative-news filtering module to detect articles portraying the company negatively.
**Tech Stack:** Python, Google Colab, Pandas, NumPy, NLTK, HuggingFace Transformers, BERT, BART, HTML, CSS, JavaScript
**Result:** Delivered bias-reduced, multi-source news summaries through an entirely frontend-based system (no server setup needed), with clickable source tags and AI-generated summaries.
**Publication:** Published in International Journal of Innovative Research in Technology (IJIRT), ISSN 2349-6002, Vol. 12, Issue 11, April 2026 — Impact Factor 8.412.
**GitHub:** https://github.com/AditBiramne/News-Synthesizer

---

### Project 2: AI-Based Resume Parsing & Extraction Tool (Resume Screening System)

**Problem:** Manual resume screening is slow and error-prone for HR teams and recruiters processing large volumes of applications.
**What Adit built:** A Flask web app that automates extracting names, emails, phone numbers, and skills from PDF resumes using `pdfplumber` and `spaCy`. Originally built during the Ganishka Technologies internship to streamline the recruitment process.
**Tech Stack:** Python, Flask, pdfplumber, spaCy, HTML, CSS
**Result:** Streamlined resume parsing for recruiters, saving time and reducing manual extraction errors through a user-friendly interface.
**GitHub:** https://github.com/AditBiramne/Resume-Screening-System

---

### Project 3: Twitter Sentiment Analysis for Stock Forecasting

**Problem:** Traditional stock prediction models often ignore investor sentiment on social media, missing short-term market psychology signals.
**What Adit built:** An end-to-end pipeline combining historical stock data with sentiment from stock-related tweets — using VADER adjusted for financial terms, lagged sentiment feature engineering (t-1, t-2, t-3), and an LSTM model built in TensorFlow/Keras to forecast next-day stock price direction.
**Tech Stack:** Python, Pandas, NLTK (VADER), TensorFlow/Keras, LSTM, NumPy, Matplotlib, Seaborn
**Result:** Achieved 85% accuracy forecasting next-day stock direction; evaluated using MAE, RMSE, and MAPE.
**GitHub:** https://github.com/AditBiramne/-Twitter-Sentiment-Analysis-for-Stock-Market-Forecasting

---

### Project 4: Product Recommendation for Walmart Products

**Problem:** Customers struggle to find relevant products in large e-commerce catalogs; personalization improves satisfaction, discovery, and conversion.
**What Adit built:** A content-based recommendation system using product descriptions, applying TF-IDF vectorization and cosine similarity to suggest relevant products.
**Tech Stack:** Python, Pandas, NumPy, Scikit-learn, TF-IDF, Cosine Similarity
**Result:** Generates relevant product recommendations from a ~5k-record Walmart product review dataset (July–Dec 2020).
**GitHub:** https://github.com/AditBiramne/Product-Recommendation-for-Walmart-Products

---

### Project 5: Movie Recommendation System

**Problem:** Users want movie suggestions similar to ones they already like, based on content rather than ratings alone.
**What Adit built:** A Python-based recommender using `CountVectorizer` and cosine similarity on movie descriptions/genres, with a simple Tkinter GUI for user interaction.
**Tech Stack:** Python, NumPy, Pandas, Scikit-learn, Tkinter
**Result:** Returns the top-5 most similar movies for a given input title (e.g., `recommend('Inception')`).
**GitHub:** https://github.com/AditBiramne/Movie-Recommendation-System

---

### Project 6: Housing Price Prediction Using AdaBoost

**Problem:** Predicting house prices from multiple property features is complex and subjective.
**What Adit built:** A machine learning pipeline that converts categorical housing features (furnishing status, guestroom, mainroad access, basement, hot water heating, air conditioning, preferred area) into numerical form and trains an `AdaBoostClassifier` for price prediction.
**Tech Stack:** Python, NumPy, Pandas, Scikit-learn, AdaBoost
**Result:** Predicts housing price categories from the `Housing.csv` dataset; future plans include extending to `AdaBoostRegressor` for continuous price prediction.
**GitHub:** https://github.com/AditBiramne/Housing-Price-Prediction-using-AdaBoost

---

### Project 7: SVM-based Email/SMS Spam Classifier

**Problem:** Spam emails and SMS messages reduce communication efficiency and pose phishing/fraud risks.
**What Adit built:** A text classification system using TF-IDF vectorization and a Support Vector Machine (SVM, linear kernel) to distinguish spam from legitimate (ham) messages, based on the SMS Spam Collection dataset (UCI ML Repository).
**Tech Stack:** Python, Pandas, NumPy, Scikit-learn, TF-IDF, SVM
**Result:** Evaluated using accuracy, precision, recall, and F1-score metrics.
**GitHub:** https://github.com/AditBiramne/SVM-based-Email-Spam-Classifier

---

### Project 8: Autocorrect System Using Naive Bayes

**Problem:** Misspelled words reduce the effectiveness of text processing and communication.
**What Adit built:** A lightweight autocorrect system using the Naive Bayes approach combined with edit distance — computing posterior probability for candidate words from word-frequency priors and edit-distance-based likelihood.
**Tech Stack:** Python, Naive Bayes, Edit Distance, Collections (Counter)
**Result:** Generates ranked correction suggestions for misspelled words (e.g., "helo" → "hello") using a simple unigram corpus, with no external dataset required.
**GitHub:** https://github.com/AditBiramne/Autocorrect-System-using-Naive-Bayes

---

### Project 9: Academic Evaluation System

**Problem:** Manually evaluating and managing student academic performance is inefficient for institutions.
**What Adit built:** A Flask-based web application with separate interfaces for students and administrators to input, view, and manage academic data — including a login page, mark-entry form, and admin dashboard.
**Tech Stack:** Python, Flask, HTML, CSS, Jinja2, MySQL/SQLite
**Result:** Provides a clean, responsive system for student data entry and admin-side performance management.
**GitHub:** https://github.com/AditBiramne/Academic-Evaluation-System

---

### Project 10: Iris Flower Classification Using ANN

**Problem:** Multiclass classification of flower species from physical measurements — a benchmark deep learning task.
**What Adit built:** A multi-layer feedforward Artificial Neural Network (ANN) built with Keras (TensorFlow backend) to classify Iris flowers (Setosa, Versicolor, Virginica) from sepal/petal measurements, using `StandardScaler`, one-hot encoding via `LabelBinarizer`, and a 70/30 train-test split.
**Tech Stack:** Python, TensorFlow/Keras, Scikit-learn, NumPy
**Result:** Trained over 120 epochs with the Adam optimizer and categorical cross-entropy loss, with accuracy and validation-accuracy tracked during training.
**GitHub:** https://github.com/AditBiramne/Artificial-Neural-Network-Implementation

---

### Project 11: Wine Quality Prediction Using Logistic Regression

**Problem:** Expert wine quality evaluation is time-consuming and subjective.
**What Adit built:** An ML pipeline applying Logistic Regression to predict the quality score (3–9) of white wine based on 11 chemical attributes, using an 80/20 train-test split and evaluated with accuracy, classification report, and confusion matrix.
**Tech Stack:** Python, Pandas, NumPy, Scikit-learn, Logistic Regression, Seaborn, Matplotlib
**Result:** Demonstrates multi-class classification on the UCI white wine dataset (~4,898 samples), highlighting the impact of imbalanced classes on prediction quality.
**GitHub:** https://github.com/AditBiramne/Wine-Quality-Prediction-Using-Logistic-Regression

---

## 5. SKILLS

### Frameworks & Libraries

PyTorch, TensorFlow, Keras, Scikit-learn, spaCy, Pandas, NumPy, Matplotlib, Flask, NLTK (VADER), HuggingFace Transformers, SciPy, OpenCV, BeautifulSoup, Regex, Seaborn

### Tools & Platforms

Jupyter Notebook, Google Colab, MySQL, VS Code, Microsoft Azure, Power BI, Tableau

### AI/ML Concepts

Deep Learning, Natural Language Processing (NLP), Large Language Models (LLMs), RAG (Retrieval-Augmented Generation), ANN, RNN, LSTM, SVM, KNN, TF-IDF, Cosine Similarity, XGBoost, Boosting & Bagging, Model Evaluation Metrics, RESTful APIs

### Programming Languages

Python (primary), HTML, CSS, JavaScript (basic)

---

## 6. CERTIFICATIONS & ACHIEVEMENTS

- **Certifications:** Python Programming (Aptech Certified), AIML — Artificial Intelligence & Machine Learning (Aptech Certified), AZ-900: Microsoft Azure Fundamentals
- **Published Research Paper:** "Multi-Source News Synthesizer Using Deep Learning" — International Journal of Innovative Research in Technology (IJIRT), ISSN 2349-6002, Vol. 12, Issue 11, April 2026, Impact Factor: 8.412
- **Cultural Co-Head** (Jul 2024 – Jun 2025): Co-led the college cultural committee, organizing major fests and intercollegiate events; managed student teams, budgeting, and sponsorships to boost participation and campus engagement.
- **Event Team Leader — NSS Unit** (Jul 2024 – Jun 2025): Led community service and awareness programs, including donation and cleanliness drives, managing volunteers, logistics, and coordination with faculty and local bodies.
- **NSS Volunteer** (Jul 2023 – Jun 2024): Contributed 120+ hours to community service activities including cleanliness drives, blood donation camps, and awareness campaigns — developing teamwork, empathy, and public engagement skills.

---

## 7. Sample QnA 

> Training Q&A pairs for the portfolio chatbot. Every answer is grounded strictly in the Adit Biramne knowledge base. The chatbot should answer in a friendly, professional, third-person (or first-person, if styled as Adit) voice and should not invent information beyond what appears here.

---

## A. BASIC INFO & IDENTITY

**Q1. Who is Adit Biramne?**
Adit Biramne is an AI/ML Engineer and Computer Engineering student based in Navi Mumbai, India. He has hands-on experience in Natural Language Processing, sentiment analysis, and building end-to-end machine learning pipelines, and is currently seeking a role in AI/ML or NLP.

**Q2. Where is Adit located?**
Adit is based in Navi Mumbai, India.

**Q3. What is Adit's educational background?**
Adit is pursuing a B.E. in Computer Engineering from MGM College of Engineering and Technology, Kamothe (affiliated with the University of Mumbai).

**Q4. When did or will Adit graduate?**
Adit's graduation year is 2026.

**Q5. Which university is Adit affiliated with?**
His college, MGM College of Engineering and Technology in Kamothe, is affiliated with the University of Mumbai.

**Q6. How can I contact Adit?**
You can reach Adit by email at aditbiramne2@gmail.com or by phone at +91 8850261086.

**Q7. What is Adit's email address?**
Adit's email is aditbiramne2@gmail.com.

**Q8. What is Adit's phone number?**
Adit's mobile number is +91 8850261086.

**Q9. Does Adit have a LinkedIn profile?**
Yes — you can find Adit on LinkedIn at https://linkedin.com/in/adit-biramne.

**Q10. Where can I see Adit's code or projects?**
Adit's GitHub profile is at https://github.com/AditBiramne, where most of his projects are hosted.

**Q11. What field is Adit studying?**
Adit is studying Computer Engineering.

**Q12. What is Adit looking for right now?**
Adit is currently seeking his next role in AI/ML or NLP.

---

## B. PROFESSIONAL SUMMARY & POSITIONING

**Q13. Give me a quick summary of Adit's profile.**
Adit is an AI/ML Engineer and Computer Engineering student with hands-on experience in NLP, sentiment analysis, and end-to-end machine learning pipelines. He has built AI-powered applications including news synthesis and summarization systems, resume parsing tools, and sentiment-driven stock forecasting models.

**Q14. What is Adit passionate about?**
Adit is passionate about turning messy, unstructured information into clear, actionable insights.

**Q15. What kind of engineer is Adit?**
He's an AI/ML engineer with a strong focus on Natural Language Processing and machine learning pipelines.

**Q16. What's Adit's proven track record?**
He has a track record of building AI-powered applications including news synthesis and summarization systems, resume parsing tools, and sentiment-driven stock forecasting models.

**Q17. What core technologies is Adit skilled in?**
He's skilled in Python, PyTorch, TensorFlow, Scikit-learn, and Hugging Face Transformers, along with designing and deploying full-stack ML pipelines from data ingestion through model inference.

**Q18. Can Adit handle a full ML pipeline end to end?**
Yes. He has experience designing and deploying full-stack ML pipelines spanning data ingestion, preprocessing, model inference, and deployment.

**Q19. Why should we hire Adit?**
Adit combines hands-on AI/ML experience (NLP, sentiment analysis, end-to-end pipelines) with real internship impact, a published research paper, and a broad portfolio of deployed projects. He's strong in Python and modern ML frameworks and is focused on producing actionable insights from unstructured data.

**Q20. Is Adit more of a researcher or a builder?**
He's both — he has a published research paper plus a portfolio of deployed, application-focused projects, showing he can take ideas from research through to working systems.

---

## C. INTERNSHIP — INDIAN OIL CORPORATION (IOCL)

**Q21. Where has Adit interned?**
Adit has interned at Indian Oil Corporation Ltd. (IOCL), Prudent Infotech, and Ganishka Technologies.

**Q22. Tell me about Adit's IOCL internship.**
Adit was an AI/ML Intern at Indian Oil Corporation Ltd. (IOCL) from June 2025 to August 2025, based at the Head Office in Bandra, Mumbai. He built a real-time Negative News Article Portal to detect negative media coverage about the company.

**Q23. When did Adit intern at IOCL?**
From June 2025 to August 2025.

**Q24. Where was the IOCL internship based?**
At IOCL's Head Office in Bandra, Mumbai.

**Q25. What did Adit build at IOCL?**
He built a real-time Negative News Article Portal that detects negative media coverage about IOCL using VADER sentiment analysis and BERT models, achieving over 90% sentiment accuracy.

**Q26. What accuracy did the IOCL news portal achieve?**
It achieved 90%+ sentiment accuracy.

**Q27. What was the impact of Adit's IOCL work?**
He reduced the company's dependency on manual media monitoring across departments — a direct operational impact at a large-scale enterprise.

**Q28. What technologies did Adit use at IOCL?**
Python, VADER, BERT, Flask, NLP, and HuggingFace Transformers.

**Q29. Did Adit deploy anything at IOCL?**
Yes — he designed and deployed a full end-to-end AI pipeline covering data ingestion, preprocessing, model inference, and a Flask-based web interface that served insights to executive stakeholders.

**Q30. Who used Adit's IOCL system?**
The pipeline served insights to executive stakeholders at IOCL.

**Q31. Was Adit's IOCL role only AI/ML focused?**
Primarily AI/ML, but per his GitHub profile the internship was also referred to as a Data Science Intern role based in the Networks & SAP Department, giving him hands-on exposure to enterprise infrastructure and ERP systems alongside the AI/ML work.

**Q32. Did Adit get exposure to enterprise systems?**
Yes — alongside the AI/ML work, he gained hands-on experience with enterprise infrastructure and ERP systems in IOCL's Networks & SAP Department.

---

## D. INTERNSHIP — PRUDENT INFOTECH

**Q33. What did Adit do at Prudent Infotech?**
At Prudent Infotech, as an AI Intern, Adit analysed the differences in usage, cost, and other aspects of various LLMs compared to GPT-4.1 for production chatbot use cases.

**Q34. What was Adit's role at Prudent Infotech?**
He worked as an AI Intern.

**Q35. Did Adit work with LLMs at Prudent Infotech?**
Yes — he compared various Large Language Models against GPT-4.1 and analysed requirements for optimizing open-source models in production environments.

**Q36. What was the goal of Adit's Prudent Infotech work?**
To understand cost and usage trade-offs between LLMs and GPT-4.1 for production chatbots, and to optimize running open-source models in production.

**Q37. Does Adit have experience with production chatbot optimization?**
Yes — at Prudent Infotech he analysed requirements for optimizing open-source models in production chatbot use cases.

**Q38. What technologies did Adit use at Prudent Infotech?**
LLMs, GPT-4.1, open-source models, and production chatbot optimization.

---

## E. INTERNSHIP — GANISHKA TECHNOLOGIES

**Q39. Tell me about Adit's Ganishka Technologies internship.**
Adit was an AI/ML Intern at Ganishka Technologies in Mumbai from July 2024 to December 2024. He developed and evaluated classification models and built text-extraction modules that became his Resume Screening System project.

**Q40. How long was the Ganishka Technologies internship?**
It was a 6-month engagement, from July 2024 to December 2024.

**Q41. What models did Adit build at Ganishka Technologies?**
He developed and evaluated classification models including SVM, Decision Trees, and Linear Regression using scikit-learn on real datasets.

**Q42. What did Adit do to improve model performance at Ganishka?**
He optimized preprocessing pipelines to improve model performance.

**Q43. What NLP work did Adit do at Ganishka Technologies?**
He built text-extraction modules using spaCy for Named Entity Recognition (NER), which became the Resume Screening System project.

**Q44. Did Adit work on a team at Ganishka?**
Yes — he worked as part of the product team, managing deadlines, code reviews, and iterative model improvements over the 6-month engagement.

**Q45. What technologies did Adit use at Ganishka Technologies?**
Python, Scikit-learn, spaCy, NER, pdfplumber, and Flask.

**Q46. Which project came out of the Ganishka internship?**
The Resume Screening System (AI-Based Resume Parsing & Extraction Tool) originated from his work at Ganishka Technologies.

---

## F. PROJECTS — OVERVIEW

**Q47. What projects has Adit worked on?**
Adit has worked on the AI-Powered News Synthesizer, a Resume Parsing & Extraction Tool, Twitter Sentiment Analysis for Stock Forecasting, a Walmart Product Recommendation system, a Movie Recommendation System, Housing Price Prediction with AdaBoost, an SVM Email/SMS Spam Classifier, a Naive Bayes Autocorrect System, an Academic Evaluation System, Iris Flower Classification with an ANN, and Wine Quality Prediction with Logistic Regression.

**Q48. How many projects does Adit have?**
His portfolio includes eleven documented projects spanning NLP, recommendation systems, deep learning, and classical machine learning.

**Q49. What's Adit's most notable project?**
The AI-Powered News Synthesizer is among his most notable — it led to a published research paper in IJIRT.

**Q50. Which projects involve NLP?**
The News Synthesizer, Resume Parsing Tool, Twitter Sentiment Analysis, Email/SMS Spam Classifier, and Autocorrect System all involve NLP techniques.

**Q51. Which projects involve deep learning?**
The Twitter Sentiment Analysis (LSTM), Iris Flower Classification (ANN), and the News Synthesizer (BERT/BART) all use deep learning.

**Q52. Does Adit have recommendation system experience?**
Yes — he built both a content-based Walmart Product Recommendation system and a Movie Recommendation System.

---

## G. PROJECT — AI-POWERED NEWS SYNTHESIZER

**Q53. What is the AI-Powered News Synthesizer?**
It's an AI-powered newspaper synthesizer that collects news from multiple reliable sources, synthesizes and summarizes them using AI and NLP, and presents them on an interactive dark-mode web interface with clickable source validation.

**Q54. What motivated the News Synthesizer project?**
Adit was motivated by the "Operation Sindoor" media coverage, where he noticed a surge of fake news and politically twisted narratives, while editorially-reviewed newspapers remained the most reliable source — but manually cross-referencing multiple papers is time-consuming.

**Q55. What problem does the News Synthesizer solve?**
It addresses rampant misinformation and fake news online by synthesizing multiple reliable sources into bias-reduced summaries, saving the time of manually cross-referencing papers.

**Q56. What models power the News Synthesizer?**
It uses BART-like summarization via HuggingFace Transformers along with BERT.

**Q57. What is the tech stack for the News Synthesizer?**
Python, Google Colab, Pandas, NumPy, NLTK, HuggingFace Transformers, BERT, BART, HTML, CSS, and JavaScript.

**Q58. What were the results of the News Synthesizer?**
It delivered bias-reduced, multi-source news summaries through an entirely frontend-based system (no server setup needed), with clickable source tags and AI-generated summaries.

**Q59. Was the News Synthesizer related to his IOCL internship?**
Yes — it was built during the IOCL internship, and he also built a dedicated IOC-specific negative-news filtering module to detect articles portraying the company negatively.

**Q60. Was the News Synthesizer published?**
Yes — it was published in the International Journal of Innovative Research in Technology (IJIRT), ISSN 2349-6002, Vol. 12, Issue 11, April 2026, with an Impact Factor of 8.412.

**Q61. Where can I find the News Synthesizer code?**
On GitHub at https://github.com/AditBiramne/News-Synthesizer.

---

## H. PROJECT — RESUME PARSING & EXTRACTION TOOL

**Q62. What is the Resume Screening System?**
It's a Flask web app that automatically extracts names, emails, phone numbers, and skills from PDF resumes using pdfplumber and spaCy, built to streamline recruitment.

**Q63. What problem does the Resume Parsing tool solve?**
Manual resume screening is slow and error-prone for HR teams and recruiters processing large volumes of applications.

**Q64. What's the tech stack for the Resume Parsing tool?**
Python, Flask, pdfplumber, spaCy, HTML, and CSS.

**Q65. What were the results of the Resume Parsing tool?**
It streamlined resume parsing for recruiters, saving time and reducing manual extraction errors through a user-friendly interface.

**Q66. Where was the Resume Parsing tool built?**
It was originally built during Adit's internship at Ganishka Technologies.

**Q67. Where is the Resume Parsing tool hosted?**
On GitHub at https://github.com/AditBiramne/Resume-Screening-System.

---

## I. PROJECT — TWITTER SENTIMENT ANALYSIS FOR STOCK FORECASTING

**Q68. What is the Twitter Sentiment Analysis for Stock Forecasting project?**
It's an end-to-end pipeline that combines historical stock data with sentiment from stock-related tweets to forecast next-day stock price direction.

**Q69. What problem does the stock forecasting project address?**
Traditional stock prediction models often ignore investor sentiment on social media, missing short-term market-psychology signals.

**Q70. How does the stock forecasting model work?**
It uses VADER adjusted for financial terms, lagged sentiment feature engineering (t-1, t-2, t-3), and an LSTM model built in TensorFlow/Keras to forecast next-day stock price direction.

**Q71. What accuracy did the stock forecasting model achieve?**
It achieved 85% accuracy forecasting next-day stock direction.

**Q72. How was the stock forecasting model evaluated?**
It was evaluated using MAE, RMSE, and MAPE.

**Q73. What's the tech stack for the stock forecasting project?**
Python, Pandas, NLTK (VADER), TensorFlow/Keras, LSTM, NumPy, Matplotlib, and Seaborn.

**Q74. Where can I find the stock forecasting project?**
On GitHub at https://github.com/AditBiramne/-Twitter-Sentiment-Analysis-for-Stock-Market-Forecasting.

---

## J. PROJECT — WALMART PRODUCT RECOMMENDATION

**Q75. What is the Walmart Product Recommendation project?**
It's a content-based recommendation system that uses product descriptions with TF-IDF vectorization and cosine similarity to suggest relevant products.

**Q76. What problem does the Walmart recommender solve?**
Customers struggle to find relevant products in large e-commerce catalogs; personalization improves satisfaction, discovery, and conversion.

**Q77. What dataset did the Walmart recommender use?**
A roughly 5,000-record Walmart product review dataset spanning July to December 2020.

**Q78. What's the tech stack for the Walmart recommender?**
Python, Pandas, NumPy, Scikit-learn, TF-IDF, and Cosine Similarity.

**Q79. Where is the Walmart recommender hosted?**
On GitHub at https://github.com/AditBiramne/Product-Recommendation-for-Walmart-Products.

---

## K. PROJECT — MOVIE RECOMMENDATION SYSTEM

**Q80. What is Adit's Movie Recommendation System?**
It's a Python-based recommender using CountVectorizer and cosine similarity on movie descriptions and genres, with a simple Tkinter GUI for user interaction.

**Q81. What does the Movie Recommendation System output?**
It returns the top-5 most similar movies for a given input title — for example, recommend('Inception').

**Q82. What's the tech stack for the Movie Recommendation System?**
Python, NumPy, Pandas, Scikit-learn, and Tkinter.

**Q83. Where can I find the Movie Recommendation System?**
On GitHub at https://github.com/AditBiramne/Movie-Recommendation-System.

---

## L. PROJECT — HOUSING PRICE PREDICTION (ADABOOST)

**Q84. What is the Housing Price Prediction project?**
It's a machine learning pipeline that converts categorical housing features into numerical form and trains an AdaBoostClassifier to predict house price categories.

**Q85. What features does the Housing Price model use?**
Categorical features like furnishing status, guestroom, mainroad access, basement, hot water heating, air conditioning, and preferred area.

**Q86. What are the future plans for the Housing Price project?**
Adit plans to extend it to an AdaBoostRegressor for continuous price prediction.

**Q87. What's the tech stack for the Housing Price project?**
Python, NumPy, Pandas, Scikit-learn, and AdaBoost.

**Q88. Where is the Housing Price project hosted?**
On GitHub at https://github.com/AditBiramne/Housing-Price-Prediction-using-AdaBoost.

---

## M. PROJECT — SVM EMAIL/SMS SPAM CLASSIFIER

**Q89. What is the Spam Classifier project?**
It's a text classification system using TF-IDF vectorization and a linear-kernel Support Vector Machine to distinguish spam from legitimate (ham) messages.

**Q90. What dataset does the Spam Classifier use?**
The SMS Spam Collection dataset from the UCI Machine Learning Repository.

**Q91. How was the Spam Classifier evaluated?**
Using accuracy, precision, recall, and F1-score metrics.

**Q92. What's the tech stack for the Spam Classifier?**
Python, Pandas, NumPy, Scikit-learn, TF-IDF, and SVM.

**Q93. Where can I find the Spam Classifier?**
On GitHub at https://github.com/AditBiramne/SVM-based-Email-Spam-Classifier.

---

## N. PROJECT — AUTOCORRECT SYSTEM (NAIVE BAYES)

**Q94. What is the Autocorrect System project?**
It's a lightweight autocorrect system using a Naive Bayes approach combined with edit distance, computing posterior probability for candidate words from word-frequency priors and edit-distance-based likelihood.

**Q95. How does the Autocorrect System work, in short?**
It generates ranked correction suggestions for misspelled words — for example, "helo" → "hello" — using a simple unigram corpus, with no external dataset required.

**Q96. What's the tech stack for the Autocorrect System?**
Python, Naive Bayes, Edit Distance, and the Collections (Counter) module.

**Q97. Where is the Autocorrect System hosted?**
On GitHub at https://github.com/AditBiramne/Autocorrect-System-using-Naive-Bayes.

---

## O. PROJECT — ACADEMIC EVALUATION SYSTEM

**Q98. What is the Academic Evaluation System?**
It's a Flask-based web application with separate interfaces for students and administrators to input, view, and manage academic data, including a login page, mark-entry form, and admin dashboard.

**Q99. What problem does the Academic Evaluation System solve?**
Manually evaluating and managing student academic performance is inefficient for institutions.

**Q100. What's the tech stack for the Academic Evaluation System?**
Python, Flask, HTML, CSS, Jinja2, and MySQL/SQLite.

**Q101. Where can I find the Academic Evaluation System?**
On GitHub at https://github.com/AditBiramne/Academic-Evaluation-System.

---

## P. PROJECT — IRIS CLASSIFICATION (ANN) & WINE QUALITY

**Q102. What is the Iris Flower Classification project?**
It's a multi-layer feedforward Artificial Neural Network built with Keras (TensorFlow backend) to classify Iris flowers (Setosa, Versicolor, Virginica) from sepal and petal measurements.

**Q103. How was the Iris ANN trained?**
It used StandardScaler, one-hot encoding via LabelBinarizer, a 70/30 train-test split, and was trained over 120 epochs with the Adam optimizer and categorical cross-entropy loss, tracking accuracy and validation accuracy.

**Q104. Where is the Iris Classification project hosted?**
On GitHub at https://github.com/AditBiramne/Artificial-Neural-Network-Implementation.

**Q105. What is the Wine Quality Prediction project?**
It's an ML pipeline applying Logistic Regression to predict the quality score (3–9) of white wine based on 11 chemical attributes.

**Q106. How was the Wine Quality model set up and evaluated?**
It used an 80/20 train-test split on the UCI white wine dataset (~4,898 samples) and was evaluated with accuracy, a classification report, and a confusion matrix, highlighting the impact of imbalanced classes.

**Q107. Where can I find the Wine Quality project?**
On GitHub at https://github.com/AditBiramne/Wine-Quality-Prediction-Using-Logistic-Regression.

---

## Q. SKILLS

**Q108. What programming languages does Adit know?**
Python is his primary language, and he also works with HTML, CSS, and basic JavaScript.

**Q109. What ML frameworks and libraries does Adit use?**
PyTorch, TensorFlow, Keras, Scikit-learn, spaCy, Pandas, NumPy, Matplotlib, Flask, NLTK (VADER), HuggingFace Transformers, SciPy, OpenCV, BeautifulSoup, Regex, and Seaborn.

**Q110. What AI/ML concepts is Adit familiar with?**
Deep Learning, NLP, Large Language Models, RAG (Retrieval-Augmented Generation), ANN, RNN, LSTM, SVM, KNN, TF-IDF, Cosine Similarity, XGBoost, Boosting & Bagging, Model Evaluation Metrics, and RESTful APIs.

**Q111. What tools and platforms does Adit use?**
Jupyter Notebook, Google Colab, MySQL, VS Code, Microsoft Azure, Power BI, and Tableau.

**Q112. Does Adit know deep learning?**
Yes — he's familiar with Deep Learning, ANN, RNN, and LSTM, and has applied them in projects like the LSTM stock forecaster and the Iris ANN.

**Q113. Does Adit have experience with LLMs?**
Yes — he lists Large Language Models and RAG among his AI/ML concepts and worked directly with LLMs and GPT-4.1 during his Prudent Infotech internship.

**Q114. Does Adit know RAG (Retrieval-Augmented Generation)?**
Yes — RAG is listed among his AI/ML concepts.

**Q115. What data visualization tools does Adit use?**
Matplotlib, Seaborn, Power BI, and Tableau.

**Q116. Does Adit have cloud experience?**
He works with Microsoft Azure and holds the AZ-900: Microsoft Azure Fundamentals certification.

**Q117. Does Adit know web development?**
He works with HTML, CSS, basic JavaScript, and the Flask framework, which he's used to deploy several of his projects.

**Q118. What's Adit's strongest programming language?**
Python is his primary and strongest language.

---

## R. CERTIFICATIONS & ACHIEVEMENTS

**Q119. What certifications does Adit hold?**
He holds Python Programming (Aptech Certified), AIML — Artificial Intelligence & Machine Learning (Aptech Certified), and AZ-900: Microsoft Azure Fundamentals.

**Q120. Does Adit have any published research?**
Yes — his paper "Multi-Source News Synthesizer Using Deep Learning" was published in the International Journal of Innovative Research in Technology (IJIRT), ISSN 2349-6002, Vol. 12, Issue 11, April 2026, with an Impact Factor of 8.412.

**Q121. What's the title of Adit's research paper?**
"Multi-Source News Synthesizer Using Deep Learning."

**Q122. What is the impact factor of the journal Adit published in?**
The IJIRT journal has an Impact Factor of 8.412.

**Q123. Does Adit have any leadership experience?**
Yes — he served as Cultural Co-Head of his college cultural committee and as Event Team Leader for the NSS Unit, both from July 2024 to June 2025.

**Q124. What did Adit do as Cultural Co-Head?**
From July 2024 to June 2025, he co-led the college cultural committee, organizing major fests and intercollegiate events while managing student teams, budgeting, and sponsorships to boost participation and campus engagement.

**Q125. What did Adit do as NSS Event Team Leader?**
From July 2024 to June 2025, he led community service and awareness programs — including donation and cleanliness drives — managing volunteers, logistics, and coordination with faculty and local bodies.

**Q126. What community service has Adit done?**
As an NSS Volunteer (July 2023 to June 2024), he contributed 120+ hours to community service including cleanliness drives, blood donation camps, and awareness campaigns.

**Q127. How many community service hours has Adit contributed?**
Over 120 hours as an NSS Volunteer between July 2023 and June 2024.

**Q128. Does Adit have teamwork and people-management skills?**
Yes — his NSS and cultural committee roles involved managing volunteers, student teams, budgets, sponsorships, and coordination with faculty and local bodies, developing teamwork, empathy, and public engagement skills.

---

## S. GENERAL / RECRUITER-STYLE QUESTIONS

**Q129. What kind of role is Adit best suited for?**
Adit is best suited for AI/ML or NLP roles, where he can apply his experience in sentiment analysis, machine learning pipelines, and language models.

**Q130. Does Adit have real-world industry experience?**
Yes — he's completed three internships (IOCL, Prudent Infotech, and Ganishka Technologies) and deployed real systems used by stakeholders, including a live negative-news portal at IOCL.

**Q131. What's an example of Adit delivering measurable results?**
At IOCL his negative-news portal reached 90%+ sentiment accuracy, and his Twitter sentiment stock forecaster achieved 85% accuracy on next-day direction.

**Q132. Has Adit deployed models in production-like settings?**
Yes — he built and deployed end-to-end pipelines with Flask web interfaces at IOCL and in his Resume Screening and Academic Evaluation projects.

**Q133. What makes Adit stand out from other new graduates?**
A combination of a published, high-impact-factor research paper, three relevant internships, measurable project results, and a broad portfolio spanning NLP, deep learning, recommendation systems, and classical ML.

**Q134. Is Adit available for full-time roles?**
Adit is graduating in 2026 and is currently seeking his next role in AI/ML or NLP.

**Q135. Can Adit work with unstructured data?**
Yes — turning messy, unstructured information into clear, actionable insights is a core focus of his, demonstrated in his news-synthesis and resume-parsing work.

**Q136. Does Adit have experience with sentiment analysis specifically?**
Yes — sentiment analysis runs through his IOCL negative-news portal (VADER + BERT) and his Twitter stock-forecasting project (financial-term-adjusted VADER).

**Q137. How can I get in touch with Adit to discuss an opportunity?**
You can email him at aditbiramne2@gmail.com, call +91 8850261086, or connect on LinkedIn at https://linkedin.com/in/adit-biramne.