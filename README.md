# Movie Recommender System 🎬🔍

This is a **Flask-based web application** that recommends movies based on a user's input. The application uses movie data from **TMDb (The Movie Database)** and provides a list of recommended movies similar to the one the user searched for.

## 🚀 Features
- Search for movies by title.
- Get recommendations for similar movies.
- View details like the movie poster, overview, genres, rating, and more.
- Explore the cast of the movie.

## 🔧 Requirements
Make sure you have **Python 3.x** installed on your system.

### **Python Packages**
You can install the required Python packages using the `requirements.txt` file.

```bash
pip install -r requirements.txt
```

### **Key Dependencies**
- **Flask**: Web framework used to run the application.
- **gunicorn**: A WSGI HTTP server (typically used for production, optional if not using Heroku).
- **numpy**: Used for numerical operations.
- **pandas**: Used for data manipulation.
- **requests**: For making HTTP requests to the TMDb API.
- **tmdbv3api**: A Python wrapper for The Movie Database API.

## 🏃‍♂️ How to Run

1. **Navigate Anaconda Navigator** and launch **VS Code**.
2. **Open the Project**: Open your project folder in VS Code.
3. **Open `main.py`**: Click on `main.py` to open it in the editor.
4. **Run the File**:
   - You can use the **"Run"** button at the top-right corner of the VS Code window, or
   - Navigate to the **top menu**, click **Terminal**, then **New Terminal**.

   To run a Flask deployment test, run the following command:
   
   ```bash
   python main.py
   ```

5. **Application Starts**: When you run `main.py`, VS Code will execute the file, and your Flask application should start up normally, allowing you to access it at `http://127.0.0.1:5000/` in your browser.

6. **Navigate to `http://127.0.0.1:5000/`** in your browser to use the website.
