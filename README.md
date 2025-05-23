### Job Recommender System

### Project Description

The Job Recommender System is an intelligent tool designed to assist job seekers in finding relevant job opportunities based on their interests and job preferences. It leverages Natural Language Processing (NLP) and content-based filtering techniques to recommend jobs that closely match a given job title or description.

### Key Features

- TF-IDF Vectorization: Utilizes the Term Frequency-Inverse Document Frequency (TF-IDF) technique to transform job descriptions into numerical vectors, capturing the importance of words in the context of the entire job dataset.
- Cosine Similarity: Computes the cosine similarity between job descriptions to identify jobs that are most similar to the given input, providing personalized recommendations.
- Web-based Interface: Offers a user-friendly web-based interface powered by Streamlit, allowing users to interact with the recommender system seamlessly.
- Scalable: Designed to handle large job datasets efficiently, making it suitable for various job markets and industries.

### Installation

To run the Job Recommender System locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required packages by running `pip install streamlit pandas scikit-learn joblib`.
3. Download the pre-trained TF-IDF vectorizer and cosine similarity matrix from [here](https://drive.google.com/drive/folders/1-8CP0QCu7oMR5JwVClsPITI1fkTZn42Z?usp=drive_link).
4. Update the file paths in the `app.py` script to point to the downloaded model files.
5. Run the app using `streamlit run app.py`.

### Usage

1. Launch the application using the command mentioned above.
2. Select a job title or a brief description in the provided text input field.
3. Click on the "Get Job Recommendations" button to receive a list of relevant job titles based on your input.
4. Explore the recommended jobs and find potential opportunities that match your interests and skills.

### Contributing

We welcome contributions to enhance the Job Recommender System. If you have any feature suggestions, bug reports, or would like to submit improvements, please follow our guidelines for contributions [here](https://github.com/bechosen-spec/Job-Recommender-System/issues).

### Credits

The Job Recommender System uses the following libraries:

- Streamlit: [Streamlit's GitHub repository](https://github.com/streamlit)
- Pandas: [Pandas' GitHub repository](https://github.com/pandas-dev/pandas)
- scikit-learn: [scikit-learn's GitHub repository](https://github.com/scikit-learn/scikit-learn)



### Screenshots

[streamlit-app-2023-07-25-00-07-79.webm](https://github.com/bechosen-spec/Job-Recommender-System/assets/65294466/d827f18b-bef0-4589-9960-e999f7bf5929)
