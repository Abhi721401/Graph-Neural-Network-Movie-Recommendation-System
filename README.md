# Graph-Neural-Network-Movie-Recommendation-System
A Graph Neural Network–based movie recommendation system built on the MovieLens-100K dataset. User–movie interactions are modeled as a bipartite graph and recommendations are generated via link prediction using learned node embeddings. Includes evaluation and an interactive Gradio demo.

🎥 **Demo Video:**  
[Click here to watch the demo](Gradio-demo-video.mp4)


This project implements a Graph Neural Network (GNN)–based movie recommendation system using the MovieLens-100K dataset.
User–movie interactions are modeled as a bipartite graph, where users and movies are nodes and ratings represent edges. A Graph Convolutional Network (GCN) is trained to learn latent node embeddings, and recommendations are generated via link prediction.

The project includes:

Graph construction and visualization of user–movie interactions

GNN training for recommendation using message passing

Interactive Gradio app for real-time recommendations 

This approach goes beyond traditional collaborative filtering by leveraging graph structure and neighborhood information to produce more informative recommendations.
