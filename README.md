# Recommendation Systems

## Overview
This repository contains two distinct recommendation systems built using different approaches: **Content-Based Filtering** and **User-Based Collaborative Filtering**. Recommendation systems are essential tools in various industries, from e-commerce to entertainment, helping to personalize user experiences by suggesting products, movies, books, and other items based on user preferences and behaviors.

### Content-Based Recommendation System
- **Notebook**: `recommendation System Content based.ipynb`
- This model recommends items based on the similarity between the content of the items and the preferences of the user. For example, in a movie recommendation system, the model will recommend movies similar to those that the user has already liked or watched.

### User-Based Collaborative Filtering
- **Notebook**: `Recommendation_System_User_Based.ipynb`
- This approach recommends items by finding similar users (neighbors) to the target user and suggesting items that these similar users have liked. It leverages the wisdom of the crowd to provide personalized recommendations.

## Project Structure
- `recommendation System Content based.ipynb`: Contains the code for building and evaluating a content-based recommendation system.
- `Recommendation_System_User_Based.ipynb`: Contains the code for building and evaluating a user-based collaborative filtering recommendation system.
- `data/`: (Not included) A directory intended for the dataset files used in these notebooks.

## Getting Started
To run these notebooks, you will need:
- Python 3.7 or higher
- Jupyter Notebook
- Required Python packages:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `scipy`
  - `matplotlib`
  - `seaborn`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/RecommendationSystems.git
   cd RecommendationSystems
2. Install the required packages:
pip install -r requirements.txt
3. Download Jupyter-Notebook or open Google Colab:
jupyter notebook
## Usage
Content-Based Recommendation System
1) Open recommendation System Content based.ipynb in Jupyter Notebook or Google Colab.
2) Follow the steps in the notebook to preprocess the data, build the recommendation model, and evaluate its performance.
3) The model will generate recommendations based on the content features of the items.
User-Based Collaborative Filtering
1) Open Recommendation_System_User_Based.ipynb in Jupyter Notebook or Google Colab.
2) Follow the steps in the notebook to preprocess the data, compute user similarities, and generate recommendations.
3) The model will provide recommendations based on the preferences of similar users
## Features
Content-Based Recommendation System:
1) Data Processing: Preprocessing of item features and user interaction data.
2) Modeling: Calculation of item similarities using cosine similarity or other metrics.
3) Recommendation Generation: Recommends items similar to those the user has shown interest in.
   
User-Based Collaborative Filtering:
1) Data Processing: Preprocessing of user-item interaction data.
2) Similarity Calculation: Uses cosine similarity to identify users with similar preferences.
3) Recommendation Generation: Recommends items based on the preferences of similar users.
## Result 
- The content-based model successfully recommends items similar to those the user has liked and making sure a personalized experience based on item attributes.
- The user-based collaborative filtering model provides personalized recommendations by levering the preferences of similar users which effectively recommend useful items.
## Dataset 
- The dataset using in this project is from a capstone dataset from HCMC University of Technology ( Vietnam ). View the attachment in the current respositories for raw data.
## Contributing
We welcome contributions to this project. To contribute:
- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes and commit them (git commit -m 'Add new feature').
- Push to the branch (git push origin feature-branch).
- Create a pull request.
## License
This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/) - see the LICENSE file for details.
## Contact 
For any question or inquiries, please reach out to danhdanhtuan0308@gmail.com.
