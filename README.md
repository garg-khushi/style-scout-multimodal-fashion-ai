# StyleScout — Multimodal Fashion Discovery Platform (Group BTP Project)

StyleScout is an AI-driven fashion discovery platform designed to help users **find, explore, and visualize styles** using multimodal search and aesthetic understanding.

> **Important (Attribution):** This repository represents a **group BTP project** developed collaboratively.  
> This copy is maintained on my GitHub to showcase the project and my contributions clearly and transparently.

---

## ✨ What StyleScout Does

StyleScout helps users:
- Discover similar fashion items using **text** (e.g., “pastel co-ord set for summer”)
- Search using **images** (upload an outfit and find similar aesthetics)
- Explore aesthetics/vibes through curated discovery flows
- Visualize results in a clean web UI

---

## 🧩 Project Structure

stylescout/  
├── backend/ # Python server (API + ML inference)  
├── ml/ # Model training, embedding, and indexing scripts  
├── scraper/ # Data collection and preprocessing  
└── style-scout-aesthetics/ # Frontend UI (React)

---

## 🛠️ Tech Stack

### Backend
- Python  
- FastAPI / Flask *(depending on current implementation)*  
- PyTorch / TensorFlow *(depending on model pipeline)*  
- Vector search / embeddings *(CLIP + FAISS, if configured)*  

### Frontend
- React  
- Node.js (npm)

### Database / Storage
- PostgreSQL / SQLite *(if configured)*  
- Object storage for images *(optional; depends on deployment)*  

> If your repo uses a specific DB/storage, update this section to match your actual setup.

---

## 🚀 Getting Started

### ✅ Prerequisites
- Python 3.9+ recommended  
- Node.js 16+ recommended  
- `pip` and `npm` installed  

---

## 1) Backend Setup

```bash
cd backend

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the server
python main.py
