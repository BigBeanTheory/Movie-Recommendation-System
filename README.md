**Movie-Recommendation-System

A Streamlit-based web app that suggests movies using a content-based filtering model, built with Python, Pandas, and Scikit-learn. *Leverages TMDB data to recommend films based on genres, keywords, cast, and crew, with posters fetched via API.*

**Features**

  **Personalized Recommendations**: *Select a movie to get five similar movies based on genres, keywords, cast, and crew.*  
  **Interactive Interface**: *Streamlit app with a dropdown for movie selection, random movie suggestions, and a responsive layout.*  
  **Poster Integration**: *Fetches movie posters from TMDB API for a visually engaging experience.*  
  **Content-Based Filtering**: *Uses cosine similarity on vectorized movie tags (overview, genres, keywords, cast, crew) for accurate suggestions.*  
  **Random Movie Option**: *Suggests a random movie for users seeking inspiration.*

**Tech Stack**

  **Languages**: Python  
  **Libraries**:  
    Streamlit (Web app framework)  
    Pandas (Data processing)  
    Scikit-learn (Vectorization, cosine similarity)  
    Requests (TMDB API calls)  
    NumPy (Numerical operations)  
  **Tools**: Jupyter Notebook (Data preprocessing)  
  **API**: The Movie Database (TMDB)  
  **Environment**: Local or cloud-hosted (e.g., Streamlit Community Cloud)

**Installation**

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/BigBeanTheory/Movie-Recommendation-System.git
   cd Movie-Recommendation-System

2. **Set up a Virtual Environment**
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Download Data Files:**
Ensure movie_list.pkl and similarity.pkl are in the project root. These are generated from project.ipynb or can be downloaded from the repository if provided.
Get TMDB API Key:
Sign up at TMDB and obtain an API key.
The app uses the provided key (8265bd1679663a7ea12ac168da84d2e8) for demo purposes, but replace it with your own for production.
