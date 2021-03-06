### A Note on Contributions

Whenever we have team projects, there are always concerns on unequal contributions from members of a project team. In the ideal world, we are all here to put in our best efforts and learn together. Even in that ideal world, we have different skill sets and preparations, and we will still contribute differently to a project. 

Therefore, you are required to post a *contribution statement* in the root README.md of your GitHub repo. Please beware that your GitHub repo will become public and remain public after the due date of the projects. 

Post your title, team members, project abstract and a contribution statement in the README.md file.  This is a common practice for research scientific journals. 

Below is an example. If no contribution statement is provided, we will insert a default statement that goes "**All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement**. "

---
Sample project README statement.

Project 3 

Team members: Yue Liang, Yunuo Ma, Wannian Lou, Linh Nguyen, Lingjia Zhang

Summary: In this project, we built several models including autoencoder, GBDT, SVM, Weighted SVM, KNN, Random Forest, XGBoost, ResNet50 and Densely Connected Neural Network based on a set of 3,000 facial images (imbalanced with a class ratio of about 4: 1, classified as 0 and 1 respectively) with 2 different types of emotions: compound emotions(classified as 0) versus simple (basic) emotions(classified as 1). Data preprocessing including dealing with imbalanced data (oversampling or generating new data for the class with smaller number of original samples) and images cropping are implemented with different methods for different models. Model evaluation and selection on imbalanced data are implemented. Based on the performance of our models, the best advance model is Densely Connected Neural Network with 0.90 testing accuracy and 0.98 testing AUC, which trained within 3 minutes. Our result is significantly improved comparing to Gradient Boosting Machine(GBM) baseline model with training time around 15 minutes, 0.82 testing accuracy and 0.81 testing AUC.

[Contribution Statement] 

Elise Nguyen: Ran GBM using original data set, tuned parameters/ performed cross validation, and trained GBM using best parameters to yield baseline; Trained and tested GBM on Balanced data set to see improvement; Tuned parameters/ performed cross validation, and trained other models, including standard SVM on balanced data set, weighted SVM on original data set, and KNN on balanced data set; Formatted file with Markdowns and headers to prep for Main file’s formatting; Wrote installation instructions for Tensorflow; Helped edit Powerpoint presentation formatting and content and helped write some speaker notes

Lingjia Zhang: carried out the training using Random Forest and XGBoost and tuned parameters after processing the imbalanced dataset by SMOTE.

Yue Liang: Preprocessed the imbalanced dataset to create a balanced dataset for the team; Built the advanced model - Densely Connected Neural Network, trained and tested it on the balanced dataset; Built the Autoencoder Model and ran it on the balanced dataset; Built the Logistics Regression, GBDT, GBDT+Logistics Regression; Tuned the parameters of those models using cross validation; Trained and tested them on balanced dataset; Combined the baseline model and the advanced model into the main file and built the prediction codes; Formatted the main files and the notebooks to give more detailed instruction on running the files; Put all models’ metrics together for comparison; Helped edit Powerpoint presentation content and formats.

Yunuo Ma: Built and Implemented ResNet50 model including images cropping, dealing with imbalanced data (oversampling using SMOTE), Normalizing image vectors and convert training and testing labels, trained and tested ResNet50 on balanced dataset; Provided detailed information about model performance and intermediate processing steps. Wrote part of packages installations; Helped plot advanced model; Helped edit Powerpoint presentation content and formats; Formatted and composed README file.

Wannian Lou: Organized all the algorithm and write them into the main file(GBM&DNN) with Yue Liang, made the Powerpoint and cooperate with other teammates. 
