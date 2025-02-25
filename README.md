🎬 **Movie Recommendation System**


🔗 Repository: parthvasu2004/movie_recommendation_system_p


🚀 Overview


The Movie Recommendation System is a machine learning-based web application that suggests movies based on user preferences. It leverages content-based filtering to recommend similar movies to those a user likes.


🛠️ Features

✔️ Personalized Recommendations based on movie similarities.
✔️ Machine Learning Model using similarity scores.
✔️ Flask Web Application for easy user interaction.
✔️ Interactive UI with a simple movie search feature.
✔️ Live Deployment on Render for public access.


📂 Project Structure

movie_recommendation_system_p/
│── templates/          # HTML templates for the web app  
│── app.py              # Flask web application  
│── movie_list.pkl      # Preprocessed dataset of movies  
│── similarity.pkl      # Precomputed similarity matrix  
│── requirements.txt    # Python dependencies  
│── .gitignore          # Ignored files  
│── README.md           # Project documentation  


⚙️ Installation & Setup


1️⃣ Clone the Repository

git clone https://github.com/parthvasu2004/movie_recommendation_system_p.git
cd movie_recommendation_system_p


2️⃣ Create & Activate Virtual Environment (Optional but Recommended)

python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows


3️⃣ Install Dependencies

pip install -r requirements.txt


4️⃣ Run the Application

python app.py
Visit http://127.0.0.1:5000/ in your browser to access the web app.


🎯 How It Works


1️⃣ Search for a Movie – Enter the name of a movie you like.
2️⃣ Get Recommendations – The system suggests similar movies based on content similarity.
3️⃣ Enjoy Your Next Movie!


🔍 Recommendation Algorithm

Content-Based Filtering: Uses text features (genre, cast, overview, etc.) to compute similarity scores.
Similarity Matrix: A precomputed cosine similarity matrix (similarity.pkl) is used for fast recommendations.


🔗 Live Deployment


The application is deployed on Render. Try it out here: https://movie-recommendation-system-mhp.onrender.com


🤝 Contribution


Contributions are welcome! Feel free to fork this repository, create feature branches, and submit pull requests.


📜 License


This project is licensed under the MIT License – free to use and modify.


📬 Contact
👤 Parth Pandey
📧 parthvasu2004@gmail.com
🔗 [linkedin.com/in/parth-pandey-3442a9256](https://www.linkedin.com/in/parth-pandey-3442a9256/)
