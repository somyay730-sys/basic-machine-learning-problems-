Machine Learning & Computer Vision Codebase 🚀Welcome to my repository! This project serves as a comprehensive collection of foundational implementations in both Machine Learning (ML) and Computer Vision (CV). Whether you are learning the mathematical intuitions behind classical algorithms or exploring basic image processing techniques, this codebase provides clean, well-documented, and easy-to-run scripts.📂 Repository Structure├── machine_learning/
│   ├── linear_regression.py
│   ├── logistic_regression.py
│   ├── naive_bayes.py
│   └── kmeans_clustering.py
├── computer_vision/
│   ├── circle_detection.py
│   └── basic_cv_utils.py
└── requirements.txt
🧠 Machine Learning ModuleThis section contains implementations of fundamental supervised and unsupervised machine learning algorithms, built using core libraries like NumPy, Pandas, and Scikit-Learn.Linear Regression (linear_regression.py)Purpose: Predicts continuous target variables using feature weights and bias.Key Concepts: Ordinary Least Squares (OLS), Gradient Descent, Mean Squared Error (MSE), and $R^2$ evaluation metrics.Logistic Regression (logistic_regression.py)Purpose: Performs binary classification tasks by mapping predicted values to probabilities using the Sigmoid function.Key Concepts: Decision boundary visualization, log-loss cost function, and confusion matrix evaluation.Naïve Bayes Classifier (naive_bayes.py)Purpose: Probabilistic classifier based on Bayes' Theorem with strong independence assumptions between features.Key Concepts: Gaussian Naïve Bayes, prior/posterior probabilities, and handling categorical/numerical data.K-Means Clustering (kmeans_clustering.py)Purpose: Unsupervised learning algorithm designed to partition data points into $K$ distinct clusters.Key Concepts: Centroid initialization, Euclidean distance metric, and Elbow Method for optimal $K$ selection.👁️ Computer Vision ModuleThis section includes introductory computer vision and image processing scripts utilizing OpenCV (cv2) and NumPy.Circle Detection (circle_detection.py)Purpose: Detects circular shapes and contours within images or live webcam feeds.Key Concepts: Hough Circle Transform (HoughCircles), Gaussian blurring for noise reduction, and edge gradient analysis.Basic CV Utilities (basic_cv_utils.py)Purpose: Essential image manipulation and feature extraction scripts.Key Concepts: Grayscaling, thresholding, edge detection (Canny), and contour retrieval.⚙️ Installation & SetupClone the repository:git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install dependencies:
Make sure you have Python 3.8+ installed, then run:pip install -r requirements.txt
🚀 Running the CodeNavigate to the respective directory and execute the desired script:# Run Linear Regression
python machine_learning/linear_regression.py

# Run Circle Detection
python computer_vision/circle_detection.py
🤝 Contributions & LicenseContributions, bug reports, and feature requests are always welcome! Feel free to open an issue or submit a pull request.This project is licensed under the MIT License.
