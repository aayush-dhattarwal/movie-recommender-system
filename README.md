# movie-recommender-system
This movie recommender system is a collaborative filtering-based system that utilizes cosine similarity scores to recommend movies. It is built using the TMDB 5000 Movie dataset and is accessible through a Streamlit framework. The app provides personalized recommendations based on user ratings and reviews, as well as similarities between other users' viewing habits.

# Dataset
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

# Screenshots
![chrome_0FxzEVs1r6](https://user-images.githubusercontent.com/29508011/227937814-bd42cf32-e8b5-4332-94e0-ab73911e46a8.png)
![chrome_PDylhw0Vck](https://user-images.githubusercontent.com/29508011/227937823-cf9ba8e0-8bcf-4098-94ae-f2e3c54f2147.png)
![chrome_lEkEWOutHa](https://user-images.githubusercontent.com/29508011/227951924-5b54579f-2edf-4c04-871e-dd06df7416b0.png)
![chrome_y7scznF4dk](https://user-images.githubusercontent.com/29508011/227937855-72f48f53-7873-492e-a536-39829590a125.png)

# Tech Stack
•	Front-End: Streamlit

•	Back-End: Streamlit

•	IDE: Jupyter Notebook, Pycharm

# How to run this app
1) Clone this repository

2) Create a virtual environment by using this series of commands:

 ----> pip install virtualenv > virtualenv myenv > myenv\Scripts\activate (for windows)

 ----> pip install virtualenv > virtualenv virtualenv_name > source virtualenv_name/bin/activate (for linux)

3) Copy all files from the cloned repo to newly created virtual environment folder.

4) Install all the packages by using the following command: pip install -r requirements.txt
 
5) Now for the final step. Run the app using this command: streamlit run app.py
