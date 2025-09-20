**📊 Project Overview**

I've developed a comprehensive movie recommendation system using collaborative filtering techniques and matrix factorization. The system analyzes user-movie ratings data to provide personalized movie recommendations based on user preferences and behavioral patterns.

---

**🛠️ Technical Implementation**

### Data Processing
- Loaded and merged user ratings data with movie metadata  
- Created user-item matrix with 943 users and 1664 movies  
- Handled missing values by filling with zeros  

### Recommendation Algorithms Implemented

**User-Based Collaborative Filtering**
- Computed cosine similarity between users  
- Generated recommendations based on similar users' preferences  
- Achieved **Precision@10: 0.0506**

**Item-Based Collaborative Filtering**
- Calculated item similarity matrix  
- Recommended movies similar to those users have liked  
- Achieved **Precision@10: 0.0506**

**Matrix Factorization (SVD)**
- Implemented Singular Value Decomposition for latent factor modeling  
- Achieved significantly better performance with **Precision@10: 0.5786**  
- **RMSE: 0.9621**

### Evaluation Metrics
- **Precision@K** to measure recommendation quality  
- **RMSE** for rating prediction accuracy  

---

**📈 Key Results**  
The SVD-based approach outperformed both collaborative filtering methods, demonstrating the power of matrix factorization in capturing latent patterns in user-item interactions.

---

**💡 Skills Demonstrated**
- Data preprocessing and feature engineering  
- Collaborative filtering algorithms  
- Matrix factorization techniques  
- Model evaluation and validation  
- Python, pandas, numpy, scikit-learn, scikit-surprise
