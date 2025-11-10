# Vibe Matcher — AI Fashion Recommendation Prototype

### Overview
**Vibe Matcher** is a lightweight prototype that uses **AI embeddings** to match user-entered *vibes* (like “cozy winter look” or “urban chic”) with fashion products that best fit the mood.  
Instead of traditional keyword matching, it uses **semantic similarity** through **Google Gemini embeddings** to understand the *feeling* behind each query.

This project demonstrates how **AI can personalize fashion discovery** — aligning products with emotional or aesthetic tones.

##  Objectives
- Understand the role of **embeddings** in AI recommendation systems.
- Prototype a **vibe-based product matcher** without training a custom model.
- Evaluate performance based on **semantic similarity** and **query latency**.


## Features
✅ Creates a mini fashion dataset (10 mock products with descriptions and vibe tags).  
✅ Uses **Google Gemini’s `embedding-001`** model to generate text embeddings.  
✅ Finds **top-3 matching products** using **cosine similarity** (`sklearn`).  
✅ Handles multiple vibe queries dynamically.  
✅ Visualizes **query latency** with Matplotlib.  
✅ Outputs results in a clean tabular format (`tabulate`).


##  Tech Stack
| Component | Tool / Library |
|------------|----------------|
| Programming | Python 3.10+ |
| Notebook | Jupyter |
| Embeddings | Google Gemini API (`models/embedding-001`) |
| Data Handling | Pandas |
| Similarity | Scikit-learn (`cosine_similarity`) |
| Visualization | Matplotlib |
| Formatting | Tabulate |


##  Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/vibe-matcher.git
   cd vibe-matcher
