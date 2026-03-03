# LahoreLens: An AI-Driven Travel Companion Using Topic Modeling

**LahoreLens** is a sophisticated, web-based travel companion that generates recommendations by mining and analyzing public social media data related to Lahore.

## 🚀 Project Structure

This repository is organized as follows:

```
LahoreLens-FYP/
│
├── documentation/        # Project Papers, Reports & API Assessments
├── design/               # Figma Designs & Screenshots
├── src/                  # Source Code
│   ├── data-collection/  # Python Scripts (Scrapers)
│   ├── ai-engine/        # ML Models (NER, Sentiment Analysis)
│   ├── backend/          # Node.js Server (API, Auth)
│   └── frontend/         # React Application
└── datasets/             # Raw & Processed Data
```
## NLP Pipeline Implemented

1. **Data Preprocessing**: Standardized 21,525 records by removing noise and normalizing Roman Urdu text.
2. **Topic Modeling (LDA)**: Classified reviews into themes: Food & Dining, General/Lifestyle, and Social.
3. **Sentiment Analysis**: Leveraged **Hugging Face Multilingual BERT** to classify the mood of comments.
   
## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **AI/ML:** Python (Scikit-learn, NLTK, Transformers)
- **Frontend:** React.js (Planned)

## 📦 Setup Instructions

### Backend
1. Navigate to `src/backend`.
2. Run `npm install` to install dependencies.
3. Create a `.env` file with your MongoDB URI and JWT Secret.
4. Run `npm run dev` to start the server.

## 📄 Documentation
See the `documentation/` folder for the full project proposal and API assessments.
