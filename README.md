<<<<<<< HEAD
# careercompass-ai
=======
# CareerCompass AI 🚀

CareerCompass AI is an AI-powered Career Recommender System designed to help users navigate their career path. It analyze skills, recommends jobs using cosine similarity, and provides a roadmap for skill improvement.

## ✨ Features

- **AI Career Roadmap Generator:** Dynamically generated roadmap based on your skills.
- **Skill Gap Analysis:** Identify what skills you need to learn for your dream job.
- **AI-Powered Job Recommendation:** Get job suggestions based on your profile using Cosine Similarity.
- **Resume Analyzer:** Upload your PDF resume and get a match score and improvement tips.
- **Secure Authentication:** User login, registration, and profile management.
- **Admin Dashboard:** Manage jobs and user data.

## 🛠️ Tech Stack

- **Backend:** Python, Flask
- **Database:** SQLAlchemy (SQLite)
- **AI/ML:** Scikit-learn, NumPy (Cosine Similarity)
- **Frontend:** HTML, CSS (Bootstrap)
- **PDF Extraction:** PyPDF2

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- `pip`

### Installation

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd careercompass-ai
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   # Windows
   venv\Scripts\activate
   # macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```bash
   python app.py
   ```

5. **Visit the app:**
   Open `http://127.0.0.1:5000` in your browser.

## 📂 Project Structure

- `app.py`: Main entry point and Flask factory.
- `careercompass/`: Main application package.
  - `routes/`: Blueprint-based route definitions (Auth, Admin, Main).
  - `models/`: Database models (User, Job).
  - `templates/`: HTML templates.
  - `static/`: Static assets (CSS, images).
  - `recommendation_engine.py`: AI logic for recommendations, roadmaps, and resume analysis.
- `instance/`: Local SQLite database (gitignored).

## 📄 License

This project is licensed under the MIT License.
>>>>>>> a103f77 (add README.md)
