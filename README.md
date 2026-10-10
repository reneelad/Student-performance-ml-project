   
## Objectives

The goal of this project is to analyze factors affecting student performance and build machine learning models to predict math scores .

## Dataset     

The dataset includes:            

* Gender                               
* Race/Ethnicity                 
* Parental level of education                                      
* Lunch type                               
* Test preparation course                    
* Reading, Writing, and Math scores                                
                   
## Workflow                                                                  
     
### 1. Data Exploration          
            
* Checked dataset structure and summary statistics                 
* Identified key patterns             
        
### 2. Data Visualization                             
            
* Analyzed score distributions
* Compared performance across categories                   

### 3. Feature Engineering

* Created a new feature:average score (reading + writing) / 2

### 4. Model Building

* Linear Regression
* Decision Tree Regressor

### 5. Model Evaluation

* Evaluated models using Mean Absolute Error (MAE)
* Compared performance across models

## Results

* Linear Regression MAE: ~4.6
* Decision Tree MAE: ~6.5

Linear Regression performed better on this dataset.

## Key Insights

* Test preparation course improves performance
* Reading and writing scores strongly influence math scores
* Decision Tree shows overfitting (high training score, lower test score)
* Feature engineering did not significantly improve performance

## Conclusion

Linear Regression is more suitable for this dataset. Decision Tree requires tuning to avoid overfitting.

## Future Work

* Apply hyperparameter tuning to reduce overfitting
* Implement Random Forest
* Perform feature importance analysis

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Author

Yug Agrawal


