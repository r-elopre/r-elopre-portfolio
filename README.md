# Ri M. Elopre  
**Freelance Full-Stack Developer (Django) | Data Scientist**  
[GitHub](https://github.com/r-elopre) | [Email](mailto:elopreri528@gmail.com) | [Phone](tel:+639952013913) +639952013913 |
Rodriguez, Rizal  

---

## Summary  
Dynamic and results-driven Full-Stack Developer and Data Scientist with extensive experience in building secure, high-performance web applications and robust data preprocessing pipelines. Proficient in Python, Django, JavaScript, and data science tools like Pandas and Scikit-learn. Demonstrated expertise in developing a full-stack social media platform and preprocessing complex datasets like Titanic and Healthcare for machine learning. Passionate about delivering optimized, scalable solutions with a focus on security, performance, and user experience.

---

## Professional Experience  

### Freelance Web Developer  
**Self-Employed / Personal Projects** — *April 2022 – Present*  
- Developed a **full-stack social media web application** with real-time messaging, post creation (image/video uploads), user profiles (follow/unfollow), likes, comments, and a global feed, all mobile-responsive and performance-optimized.  
  - **Security Tests Passed**:  
    - ✅ **Cross-Site Scripting (XSS)**: Sanitized user-generated content using a reusable `escapeHTML()` function across all interactive views, preventing stored and reflected XSS.  
      📹 [Watch Test](https://youtu.be/jEscr0JXbuc?si=y0sEYaLsQSvYr-9K)  
    - ✅ **Cross-Site Request Forgery (CSRF)**: Protected forms and JavaScript requests using Django’s CSRF middleware with token injection for secure POST actions.  
      📹 [Watch Test](https://youtu.be/Jh_YLm9DIZs?si=b5Wsg9fTRG4e-ulo)  
    - ✅ **Authentication & Session Management**: Implemented password hashing with Django’s `make_password()`, 20-minute session expiration, brute-force prevention via rate limiting, and secure cookies (Secure, HttpOnly).  
      📹 [Watch Test](https://youtu.be/GBs8rEWTVQ8?si=w12NQJJ4kikWT2CO)  
  - **Performance Tests Passed**:  
    - ✅ **Client-Side Media Optimization**: Reduced image file sizes by up to 80% using Compressor.js, enhancing upload speed and performance.  
    - ✅ **Caching Strategy**: Utilized Django’s caching framework for posts, comments, and user data to reduce load times.  
      📹 [Watch Test](https://youtu.be/DV2VaTyp-XY?si=Yh0rFk50WXSFENsR)  
    - ✅ **Efficient Database Queries**: Eliminated N+1 issues with batch fetching, implemented offset-based pagination, and used selective field fetching to optimize performance.  
      📹 [Watch Test](https://youtu.be/-luhtWYskP8?si=HOieIin6wZVyuEQ4)  
    - ✅ **Non-Blocking JavaScript Architecture**: Employed modular, deferred scripts (`chat.js`, `post.js`), lazy execution, and efficient polling for minimal resource usage.  
      📹 [Watch Test](https://youtu.be/ZsFa0-ix1vs?si=C-a4Z2dvTMSu3Av-)  
    - **GitHub**: [chatGF](https://github.com/r-elopre/chatGF)  
    - **Additional Details**: [Social Media Explanation](https://docs.google.com/document/d/1k1aAXfTE2I7JELJDP0ywRUAfVlsU6Guk2VFa7cES3gY/edit?tab=t.0)

### Data Scientist  
**Self-Employed / Personal Projects** — *April 2022 – Present*  
- Designed and implemented comprehensive data preprocessing pipelines for the **Titanic** and **Healthcare** datasets, transforming raw data into machine-learning-ready formats.  
  - **Titanic Data Cleaning Pipeline**:  
    - Built a 6-script Python pipeline (`diagnose.py`, `clean.py`, `EDA.py`, `process_data.py`, `encode_data.py`, `scale_data.py`) to clean, explore, and preprocess the Titanic dataset (891 rows, 12 columns).  
    - Handled missing values (`Age`, `Embarked`, `Cabin`), standardized categorical data, and scaled numeric features using `StandardScaler`.  
    - Generated EDA visualizations (histograms, bar plots, correlation heatmaps) to uncover survival patterns.  
    - **Output**: `train_scaled.csv` with encoded categorical variables and standardized numeric features, ready for modeling.  
    - **GitHub**: [Titanic Data Cleaning](https://github.com/r-elopre/titanic-data-cleaning)

    ### 🔹 Models Trained on Cleaned Data:
    1. [Logistic Regression Model](https://github.com/r-elopre/Titanic-Logistic-Regression-Model) — baseline binary classification to predict survival.
      
  - **Healthcare Data Cleaning Pipeline**:  
    - Preprocessed a dataset (1000 rows, 10 columns) with 159–384 missing values per column.  
    - Handled missing values (`Age` with median, `Condition` with "Unknown", `Cholesterol` with mean), standardized date formats, and split `Blood Pressure` into Systolic/Diastolic.  
    - Performed EDA to identify age clusters (25, 35, 60, 70) and cholesterol distributions (160–220 mg/dL).  
    - Applied one-hot encoding to categorical features (`Gender`, `Medication`) and scaled numeric features for ML compatibility.  
    - **Output**: `healthcare_scaled.csv`, fully numeric and scaled for modeling.  
    - **GitHub**: [Healthcare Data Cleaning](https://github.com/r-elopre/healthcare-data-cleaning)  

### Machine Learning Engineer  
**Self-Employed / Personal Projects** — *April 2022 – Present*  
- Developed and evaluated a **Titanic Logistic Regression Model** to predict passenger survival using the preprocessed `train_scaled.csv` dataset (891 rows, 18 columns).  
  - Implemented a Python script (`titanic_model_logreg.py`) to load data, perform train-test split (80% train, 20% test), train a logistic regression model, and evaluate performance.  
  - Achieved ~82% accuracy, with precision (83% for Not Survived, 80% for Survived), recall (87% for Not Survived, 76% for Survived), and F1-scores (85% for Not Survived, 78% for Survived).  
  - Generated a confusion matrix heatmap (`confusion_matrix.png`) using Seaborn to visualize true/false positives and negatives.  
  - Saved test predictions with `PassengerId` to `titanic_logreg_predictions.csv` for further analysis.  
  - **GitHub**: [Titanic Logistic Regression Model](https://github.com/r-elopre/Titanic-Logistic-Regression-Model)  

---

## Skills  
- **Programming**: Python, JavaScript, HTML, CSS  
- **Frameworks & Libraries**: Django, Pandas, Scikit-learn, Seaborn, Matplotlib, Compressor.js  
- **Tools**: Git, GitHub, Jupyter Notebook, VS Code  
- **Web Development**: Full-stack development, RESTful APIs, real-time messaging, responsive design  
- **Data Science**: Data cleaning, preprocessing, EDA, feature engineering, categorical encoding, feature scaling  
- **Machine Learning**: Logistic regression, model training, evaluation metrics, confusion matrix visualization  
- **Security**: XSS prevention, CSRF protection, secure authentication, session management  
- **Performance Optimization**: Caching, efficient database queries, non-blocking JavaScript, media compression  

---

## Education  
**Self-Taught Developer & Data Scientist & Computer Science Student**  
- Completed online courses in Python, Django, JavaScript, and Data Science (Coursera, Udemy).  
- Built real-world projects to apply skills in web development, data preprocessing, and machine learning.  

---

## Projects  
- **ChatGF Social Media Platform** ([GitHub](https://github.com/r-elopre/chatGF)):  
  A secure, high-performance, full-stack web app with real-time messaging, post creation, and user interaction features, rigorously tested for security and performance.  
- **Titanic Data Cleaning Pipeline** ([GitHub](https://github.com/r-elopre/titanic-data-cleaning)):  
  A modular Python pipeline for cleaning and preprocessing the Titanic dataset, producing a machine-learning-ready dataset with visualizations.  
- **Titanic Logistic Regression Model** ([GitHub](https://github.com/r-elopre/Titanic-Logistic-Regression-Model)):  
  A project that trains a logistic regression model to predict passenger survival on the Titanic using the preprocessed `train_scaled.csv` dataset. Achieved ~82% accuracy, with evaluation metrics and a confusion matrix heatmap saved as `confusion_matrix.png`. Predictions were saved to `titanic_logreg_predictions.csv`.  
- **Healthcare Data Cleaning Pipeline** ([GitHub](https://github.com/r-elopre/healthcare-data-cleaning)):  
  A robust pipeline for cleaning and preprocessing healthcare data, addressing missing values, inconsistencies, and preparing data for ML.  

---

## Contact  
For inquiries, please reach out via [email](mailto:elopreri528@gmail.com). elopreri528@gmail.com