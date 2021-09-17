# Portfolio

## Data Science Projects
---


### [Project 1 Overview: Predicting Restaurant Star Ratings Using Machine Learning](https://github.com/shelrx/shelrx_predictingstarratings)

In this project, I produced two stacking model, incorporating the Multinomial Naïve Bayes and Logistic Regression as base classifiers. The models differed by their meta classifiers, where one used a decision tree model and the other used the Gaussian Naïve Bayes model. I chose to train the models on the sparse matrix retrieved from using CountVectoriser on the original text training data. The predictions for each model are stored in a csv file.

Language: Python 3



---


### [Project 2 Overview: Predicting Ride Demand in New York City for TaxiDrivers](https://github.com/MAST30034-2021-S2/mast30034_2021_s2_project_1-shelanahrahman)

In this project I did as my first complete data science project, I suggested a model that predicts the taxi demand given a certain time period and location. I did this by aggregating the combined NYC taxi data and FHVHV data by the median of the features.  Then, I visualised and analysed the geographic and time series data to retrieve any useful trends.  The features are selected through analysing their distribution of features in regards to the trip demand classification and correlation between features.  Lastly, a random forest model was fitted against the final selected features and the hyper parameters were tuned through RandomSearchCV to improve its performance. For more details on the analysis done in this project, refer to the report linked in the read me file. I received a H1 (highest grading) for this project.

Language: Python 3


---
## Artificial Intelligence 

### [Project 3 Overview: Single-Player, Search-based variant of the game RoPaSci360](https://github.com/shelanahrahman/RoPaSci_Project_A)

In this project completed with a partner Ayda Zhao, we implemented the BFS algorithm to find the most efficient solution where the player's token has to defeat the opponent's tokens with the least moves. The single-player variant of RoPaSci360 is a game played on a hexagonal board of 61 hexes, where the player’s token (upper tokens) are all simultaneously moved each turn in order to defeat all the lower tokens on the board. Each token has a symbol of rock, paper or scissors and follows the ruling of the traditional game, “rock, paper, scissors”. The possible moves are slide actions (direct move one hex away from the original hex) and swing actions (a slide action from an adjacent upper-token). When the program is executed, our program reads a JSON-formatted board configuration from a file, calculatea winning sequence of actions, and print out this sequence of actions.


Language: Python 3



---


### [Project 4 Overview:  Original, Simulatanous-Play RoPaSci360 AI](https://github.com/shelanahrahman/RoPaSci_Project_B)

In this project completed with a partner Ayda Zhao, we designed and implemented a program to play the game of RoPaSci 360. Given information about the evolving state of the game, our program aimed to beat the opponent player. We implemented an altered version of the minimax algorithm to select actions throughout the game. In order to consider the simultaneous-play nature of RoPaSci360, our minimax algorithm makes predictions based on the original position of the enemy’s tokens to have knowledge of how to act against the enemies.

Language: Python 3


---
## Projects for Fun

### [Project 5 Overview: Kris Kringle Generator](https://github.com/shelanahrahman/Kris-Kringle-)

This project was completed purely for fun. I created a Kris Kringle Generator that matches participants to a person to give a gift to and then sends an email to participants on this information. This method was created during lockdown where we could not physically pick a name from a box. Hence, this method allowed for complete randomness.

Language: Python 3


---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
