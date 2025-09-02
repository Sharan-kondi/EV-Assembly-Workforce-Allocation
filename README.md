### EV Assembly Workforce Allocation: An AI-Powered Task Allocation System 🤖

### **Project Overview**

**TaskXpert** is a a machine learning-based system engineered to optimize workforce allocation on an Electric Vehicle (EV) battery assembly line. It uses a predictive model to forecast a worker's performance rating and intelligently recommend the most suitable task for them. This project serves as a comprehensive demonstration of how AI can be leveraged to enhance operational efficiency and productivity in a manufacturing environment.

-----

### **🚀 Features**

  * **Predictive Analytics**: Utilizes a robust `XGBoost` model to predict a worker's future performance rating based on their skills, experience, and certifications.
  * **Intelligent Task Recommendation**: Recommends the optimal task from the assembly line that best matches a worker's profile, ensuring maximum productivity and a higher performance rating.
  * **Full-Stack Application**: A complete web application built with Python's Flask framework, providing a clean and intuitive user interface for managers to input worker details and view results.
  * **Educational Resources**: Includes a dedicated page with videos about the EV assembly and battery manufacturing process to provide context and background information.
  * **Efficient Deployment**: The trained machine learning models and preprocessing objects are saved using `joblib` to facilitate fast and seamless deployment in the web application.

-----

### **🛠️ Technologies Used**

  * **Backend Framework**: Flask (Python)
  * **Machine Learning**: `XGBoost`, `scikit-learn`
  * **Data Handling**: `pandas`, `joblib`
  * **Frontend**: HTML, CSS, JavaScript, Bootstrap
  * **Environment Variables**: `python-dotenv`
  * **Data Visualization**: `matplotlib`, `seaborn` (for model evaluation)

-----

### **⚙️ Setup and Installation**

Follow these steps to get the EV Workforce Allocation application up and running on your local machine.

#### **Prerequisites**

  * Python 3.x
  * pip (Python package installer)

#### **Dataset Information 📚**

This project uses synthetic datasets to simulate worker and task allocation on an EV assembly line. The original datasets are available for download from this Google Drive link:

#### **1. Install Dependencies 📦**

It is highly recommended to use a virtual environment to avoid conflicts.

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On macOS/Linux
source venv/bin/activate
# On Windows
.\venv\Scripts\activate

# Install the required Python packages
pip install Flask pandas scikit-learn xgboost joblib
```

#### **2. Run the Application ▶️**

Once you have the dependencies installed, you can launch the Flask application from the project's root directory.

```bash
python app.py
```

The application will start, and you can access it by opening your web browser and navigating to `http://127.0.0.1:5000/`.

-----

### **💬 Usage**

  * **Explore the Home Page**: Navigate to the home page to learn about the EV assembly and battery manufacturing processes.
  * **Watch Videos**: Click on the "Watch Videos" button to access educational content related to EV battery production.
  * **Access the Allocator**: Go to the "Task Allocator" page to input worker details.
  * **Input Worker Data**: Fill out the form with the worker's skill category, skill level, years of experience, shift availability, certifications, and current task assigned.
  * **Get Recommendations**: Click the "Recommended" button to receive a predicted performance rating and a task recommendation for the worker.

-----

### **⚠️ Disclaimer**

This application is provided for informational and demonstration purposes only. The predictions and recommendations are based on a synthetic dataset and should not be used as a substitute for professional operational management or decision-making.
