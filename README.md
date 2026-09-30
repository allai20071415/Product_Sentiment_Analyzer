# Product_Sentiment_Analyzer
# Product Sentiment Analyzer

An end-to-end web application for collecting product reviews and analyzing customer sentiment using Natural Language Processing (NLP) and Machine Learning.

The system helps users understand whether product reviews are **Positive, Negative, or Neutral** and provides an organized interface for viewing sentiment analysis results.

## 🚀 Features

* 🛒 Product review collection
* 🔍 Product review scraping
* 🤖 AI/NLP-based sentiment analysis
* 📊 Sentiment result visualization
* 📁 CSV-based review and result storage
* 🔄 Backend API for processing reviews
* 💻 Modern web-based frontend
* 🧪 Testing and verification support
* 📈 Review and sentiment statistics
* 📄 Deployment documentation

## 🏗️ Project Architecture

```text
Product-Sentiment-Analyzer/
│
├── backend/
│   ├── app/
│   ├── requirements.txt
│   └── ...
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── product_review_scraper/
│   ├── scrapers/
│   │   ├── amazon.py
│   │   ├── flipkart.py
│   │   ├── base.py
│   │   └── __init__.py
│   │
│   ├── scraper.py
│   ├── sentiment_analysis.py
│   ├── verify.py
│   ├── test_scraper.py
│   ├── requirements.txt
│   └── README.md
│
├── database/
│
├── sample_data/
│
├── Product_Sentiment_Analyzer_Deployment_Guide.pdf
├── .gitignore
└── README.md
```

## 🛠️ Technologies Used

### Frontend

* React
* JavaScript
* HTML5
* CSS3
* Vite

### Backend

* Python
* Flask
* REST API
* Natural Language Processing

### Data & Machine Learning

* Python
* Pandas
* NumPy
* NLP techniques
* Sentiment Classification
* CSV data processing

### Development Tools

* Git
* GitHub
* VS Code
* Python Virtual Environment
* npm

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Product-Sentiment-Analyzer.git
cd Product-Sentiment-Analyzer
```

### 2. Backend Setup

Navigate to the backend:

```bash
cd backend
```

Create a Python virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

For macOS/Linux:

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create your environment configuration from the example:

```bash
copy .env.example .env
```

For macOS/Linux:

```bash
cp .env.example .env
```

Update the `.env` file with your local configuration.

### 3. Start the Backend

From the `backend` directory:

```bash
python app.py
```

The backend API will start on the configured local port.

## 💻 Frontend Setup

Open a new terminal and navigate to:

```bash
cd frontend
```

Install Node.js dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the URL displayed by Vite in your browser.

## 🕷️ Review Scraper

The project contains a separate review-scraping module.

Navigate to:

```bash
cd product_review_scraper
```

Install its dependencies:

```bash
pip install -r requirements.txt
```

Run the scraper:

```bash
python scraper.py
```

The scraper modules are organized so that additional product sources can be added later.

## 🤖 Sentiment Analysis

After collecting reviews, sentiment analysis can be performed using:

```bash
python sentiment_analysis.py
```

The system processes review text and generates sentiment results.

Typical sentiment categories are:

```text
Positive
Negative
Neutral
```

## 📊 Output

The project can generate structured results such as:

* Product name
* Review text
* Rating
* Review date
* Sentiment
* Sentiment score
* Analysis result

CSV files can be used for further analysis and visualization.

## 🧪 Testing

To run the scraper tests:

```bash
python -m pytest
```

You can also run the verification script:

```bash
python verify.py
```

## 📁 Sample Data

The repository contains sample data to demonstrate the application without requiring the user to immediately collect new reviews.

Sample data may include:

```text
reviews.csv
sentiment_results.csv
```

## 🔐 Security

Do **not** upload sensitive information to GitHub.

Never commit:

```text
.env
API keys
Passwords
Authentication tokens
Private credentials
Session cookies
```

The repository includes a `.gitignore` file to prevent common sensitive and generated files from being committed.

## 🌐 GitHub Deployment

### Initialize Git

From the project root:

```bash
git init
```

Add the project files:

```bash
git add .
```

Create the first commit:

```bash
git commit -m "Initial commit - Product Sentiment Analyzer"
```

Connect your GitHub repository:

```bash
git remote add origin https://github.com/YOUR-USERNAME/Product-Sentiment-Analyzer.git
```

Push the project:

```bash
git branch -M main
git push -u origin main
```

## 📌 Project Objective

The main objective of the Product Sentiment Analyzer is to provide an automated solution for understanding customer opinions from product reviews.

Instead of manually reading hundreds of reviews, users can collect reviews and use automated sentiment analysis to identify overall customer feedback.

## 🔮 Future Enhancements

* Real-time product review analysis
* Support for additional e-commerce platforms
* Multilingual sentiment analysis
* Aspect-based sentiment analysis
* Product comparison
* Advanced analytics dashboard
* Sentiment trends over time
* Review spam detection
* Cloud deployment
* Authentication and user accounts

## 👩‍💻 Author

**Allaishah Inayath**

Artificial Intelligence and Data Science

## 📄 License

This project is intended for educational and academic purposes.

A suitable open-source license such as the MIT License can be added if the project is intended for public reuse.
