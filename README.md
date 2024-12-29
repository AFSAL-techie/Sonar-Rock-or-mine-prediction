🎯 PREDICTION OF ROCK OR MINE USING SONAR DATA
            🔍 BASIC PROCESS:
                         STEP 1: IMPORTING THE REQUIREMENTS
                                  
                                  📊 Numpy: 
                                      Used for creating arrays.
                                  
                                  📋 Pandas: 
                                        Used for creating data frames and data handling.
                                  
                                  🛠️ Sklearn:
                                        train_test_split: Splits the data into training and testing sets.
                                  
                                  🤖 Logistic Regression Model:
                                       Imported from sklearn.linear_model.
                                       Used for classification tasks (e.g., yes/no-type predictions).
                                  
                                  ✅ Accuracy Score:
                                        Imported from sklearn.metrics to evaluate the model's accuracy.

                                  
                        📁 STEP 2: DATA COLLECTION AND PROCESSING 

                        
                              1)📥 Load the dataset into a Pandas data frame.
                              
                              2) 🧐 Use .head() to display the first 5 rows and .tail() to display the last 5 rows of the dataset.
                               Initially, set head = None to view the entire dataset.
                               
                              3) 📐 Check the number of rows and columns using sonar_data.shape.
                              Example: (208, 61) where 208 is the number of rows, and 61 is the number of features.
                              
                              4) 📊 Use .describe() to display the statistical measures of the dataset.
                              
                              5) 📊 Count the occurrences of "Rock" and "Mine" by grouping the data based on these labels and finding their mean values.
                              
                              6) ✂️ Separate the data into features and labels.
        

                      
                          ⚙️ Step 3: Training and Testing the Data

                                 1) 🔄 Train the model using 80% of the data and test it with the remaining 20%.
                                  
                                 2) 🤓 Train the logistic regression model using the training data: model.fit(X_train, Y_train).
                                  
                                 3) 📈 In a graph:
                                        X-axis: Features
                                        Y-axis: Labels
                                        A graph will be plotted to visualize the model's learning.
                                  

                                                        
                         📊 STEP 4: MODEL EVALUATION
                      
                                  ✅ Accuracy score on training data: ~84%
                                  ✅ Accuracy score on testing data: ~76%

                      
                      🛠️ STEP 5: MAKING A PREDICTIVE SYSTEM
                    
                                    💡 Input new data, and the system will predict whether the object is a rock or a mine
