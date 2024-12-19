# Saciva University Recommendation System

## Project Title: Saciva University Recommendation System

### Project Description

The Saciva University Recommendation System is an innovative platform designed to assist international students in selecting U.S. universities that align with their academic, personal, and financial profiles. This project leverages data-driven methodologies to simplify the complex process of university selection, ensuring students are matched with institutions that suit their unique needs and preferences. By addressing the multifaceted challenges faced by international students, the system aims to enhance their academic journey and overall experience in the United States.

### Project Overview, Objectives, and Goals

**Overview:** Saciva is a comprehensive tool that provides personalized university recommendations for international students. It combines multiple criteria, such as academic standing, field of study, financial status, and lifestyle preferences, to suggest institutions that best fit the student’s profile.

**Objectives:**
- Develop a recommendation system using clustering and nearest-neighbor methodologies.
- Improve decision-making for students by offering insights into academic, geographic, and cultural factors of universities.
- Simplify the university search process to reduce the stress associated with moving to a new country for education.

**Our Goal:** Create an intuitive and user-friendly recommendation engine. Address gaps in current solutions by incorporating factors such as offered classes, cost of living, safety, and networking opportunities in university profiles. Foster community building among international students by aligning preferences with university characteristics.

### Methodology

**Data Collection:** Data was collected from diverse sources to create comprehensive university and student profiles. Factors included rankings, tuition fees, offered classes, and location, among others.

**Preprocessing:** The data was normalized and standardized to ensure uniformity across features. Missing values were imputed, and categorical variables were encoded appropriately.

**Modeling:**
- **Clustering:** Used K-means clustering to group universities based on their profiles.
- **Nearest Neighbor:** Implemented the K-Nearest Neighbors (KNN) algorithm to find the best matches for students based on an input profile.

**Tools:** The system was developed using Python with libraries like scikit-learn, pandas, and numpy for data manipulation and modeling.

**Implementation:** The system receives a student profile as input, vectorizes it, and computes the closest matches using a trained KNN model. Recommendations are ranked based on proximity in the feature space.

### Results and Key Findings

- The recommendation engine successfully provided personalized university suggestions, reflecting accurate matches to student preferences.
- The clustering method revealed distinct groupings of universities based on similar attributes, which enhanced the recommendation quality.
- Preliminary evaluations demonstrated strong alignment between suggested universities and test profiles, with significant potential for improving decision-making.

**Performance Metrics:**
With an unsupervised clustering model and no initial student preference data, it is difficult to test the model's empirical accuracy. However, we have found that running values on what might be believed to represent a student make sense with the recommendations.

**Insights:**
- Students might want to consider factors like affordability and safety, which are often overlooked in traditional selection methods.
- Customizing recommendations based on non-academic preferences can increase user satisfaction if this model is used in the future.
- Having more time on this project, we might have employed surveying methods or tried testing other models to get some idea of accuracy.

**Visualizations:**
- **Clustering Outputs:** Graphical representation of university clusters to illustrate groupings.
- **Distance Analysis:** Line charts depicting proximity scores for recommended universities.

### Potential Next Steps

- **Enhance Model Accuracy:** Integrate supervised learning based on real-world input and student preferences.
- **Expand Dataset:** Incorporate data from international universities to broaden the system's reach.
- **Real-Time Interaction:** Enable students to tweak input preferences dynamically and view updated recommendations.
- **Deployment:** Develop a web or mobile app for real-world use, focusing on seamless UI/UX.
- **Community Features:** Add options for students to connect with peers and alumni of recommended universities.

### Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Contributing](#contributing)
4. [License](#license)
5. [Acknowledgments](#acknowledgments)

### Installation

In the Google Drive account where you would like to run the notebook, place the datasets under a folder called `datasets` in the root directory. Then, download either the notebook without "Modeling" in the name if you would like to tweak the final dataset or analyze our data preparation. Otherwise, download the "Modeling" notebook and adjust the `student_input` variables to experiment with it.

Download the sample datasets here or linked above at the top of this README.

### Usage

1. Load the dataset and model using the `Saciva_University_Recommendation_System_2B_Modeling.ipynb`.
2. Adjust the student input vector in the notebook to test recommendations.
3. Execute the KNN model to receive the top 5-10 university matches.

### Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a pull request for review.

### License

This project is licensed under the Apache License. See the LICENSE file for details.

### Credits and Acknowledgments

Special thanks to the Saciva team, especially Abhishikth, Break Through Tech AI program mentors, including our TA Muskan, and others who may have provided valuable insights and support.

