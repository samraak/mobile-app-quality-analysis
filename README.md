**Mobile App Quality Analysis & Recommendation Framework**

Welcome to my Final Year Project!
This repository contains a web-based framework I built to help developers and researchers analyze user reviews of mobile applications.

We all use apps daily — from WhatsApp to YouTube — and people leave tons of reviews. But those reviews are scattered and unstructured, making it hard for developers to quickly see what users like or dislike.

That’s where my project comes in 

 **Live Demo / Website:** [Mobile App Quality Analysis Framework](http://palevioletred-okapi-453801.hostingersite.com/)


 **What this project does**

Reads thousands of app reviews

Uses AI (BERT + BiGRU) to detect sentiments (positive, negative, neutral)

Groups feedback into topics (performance, usability, bugs, design, etc.)

Displays results in a simple, interactive dashboard

Helps developers spot issues early and improve their apps

In short → It turns messy reviews into actionable insights 

** Technologies Used**

Frontend: React + TailwindCSS (clean and responsive UI)

Backend: FastAPI (lightweight and fast)

Machine Learning / NLP: BERT, BiGRU, LDA

Python Tools: Pandas, NumPy, Scikit-learn

Visualization: Recharts (frontend) + Matplotlib (backend)

**Why I built this**

This project was developed as part of my Bachelor’s Final Year Project in Software Engineering .

Main motivation:

Developers spend hours reading reviews manually 

Existing tools don’t always show quality-related insights

By combining AI + Software Quality Models, review analysis becomes smarter and faster

**How to run it**
1️⃣ Clone this repo:
git clone https://github.com/samraak/mobile-app-quality-analysis.git
cd mobile-app-quality-analysis

2️⃣ Install backend dependencies:
pip install -r requirements.txt

3️⃣ Start backend (FastAPI):
uvicorn main:app --reload

4️⃣ Start frontend (React):
cd frontend
npm install
npm start

**Feature**s you’ll see

Sentiment distribution → how many reviews are positive vs negative

Topic clusters → what people are talking about most

Quality attributes → performance, UI, security, etc.

Actionable recommendations → what developers should improve

**Acknowledgements**

This project was completed under the guidance of my professors and supported by research papers in software quality analysis and NLP.

**Author**

Samra Azhar
Bachelor of Science in Software Engineering
Passionate about AI, NLP, and building solutions that help people.
