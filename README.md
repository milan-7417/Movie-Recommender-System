# Movie Recommender System

This is a simple content-based movie recommender system built with Python and Streamlit. The application suggests a list of 5 similar movies based on a movie you select from the dropdown menu.

## ## Technologies Used

* *Python*
* *Streamlit* (for the web interface)
* *Pandas* (for data manipulation)
* *Scikit-learn* (for calculating cosine similarity)
* *Requests* (for fetching movie posters from an API)
## ## How to Run This App Locally

Follow these steps to set up and run the project on your own machine.

### ### Prerequisites

* *Python 3.8+* and *pip* installed.

### ### Installation and Setup

1.  *Clone the repository:*
    bash
    git clone [https://github.com/milan-7417/Movie-Recommender-System.git](https://github.com/milan-7417/Movie-Recommender-System.git)
    cd Movie-Recommender-System
    

2.  *Download the Similarity Model File:*
    The similarity.pkl file is too large to be stored on GitHub. You need to download it from the link below and place it in the main Movie-Recommender-System folder.

    *➡ [Download similarity.pkl here]("C:\Users\mrai4\movies recommender system\similarity.pkl") *

3.  *Create and activate a virtual environment:*
    * *Windows (PowerShell):*
        bash
        python -m venv .venv
        .\.venv\Scripts\Activate.ps1
        
    * *macOS / Linux:*
        bash
        python3 -m venv .venv
        source .venv/bin/activate
        

4.  *Install the required Python packages:*
    bash
    pip install -r requirements.txt
    

5.  *Run the Streamlit app:*
    bash
    streamlit run app.py
    
    Your web browser should open with the application running! 🎉

***

