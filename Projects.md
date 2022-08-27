
## Underwriting Model Development
**Primary Goal**: Developed underwriting scoring model to classify auto loan based on survival rate <br/>
**Solution**: Pulled data from MySQL, implemented data cleaning with Python and tested features statistically significant with Kaplan-Meier and COX PH model, applied AFT, RSF (Random Survival Forest) and Neural MTLR Model to divide customers into 5 different types and computed the historical CNL performance, finally selected RSF as final model and deployed it in production <br/>
**Result**: New model boosted 28% loan acceptance and led to 20 million loan amount increase <br/>


## Effective Call Prediction  
**Primary Goal**: Priority daily call to increase call efficiency and reduce cost <br/>
**Solution**: Using Python to extract and clean the data from structure and unstructured database, creating 5 new important features, then applying Model Stacking technique to train the model <br/>
**Result**: Increase call rate effective from 18% to 45%

## Delinquency Risk Prediction
**Primary Goal**: Predict delinquency risk and take accordingly business measure to reduce it
**Solution**: Employed Model Stacking technique to ensemble Logistic Regression, Random Forest and XGBoost as first layer and then aggregated with LightGBM as second layers to develop the final model with Python
**Result**: Reduce delinquency rate from 18% to 15%


## OCR typo and Web crawled text integration detection
**Primary goal**: filtering out bad qualified questions from repositories caused by OCR or web crawl programming bugs
**Solution**: Synthetic labeled data by NLP augmentation techniques like random cropping, random swap, random deletion, shape-near words replacement, OCR system’s error output with ground truth text; Fine-tuned  ALBERT( BERT variant) with self-defined loss(combined classification and sequential prediction output)
**Result**: Achived 78% F1-score  on testing set and helped filter out 5% bad qualified questions from 3 millions questions.

## Build OCR System to Scrape data from PDF and web-based sources 
**Primary Goal**: To conduct cost reduction and efficiency improvement <br/>
**Solution**: Employed OpenCV to detect the column, then used U-NET to detect text block and CRNN neural network model to recognize the text in each text block, after that utilized Bi-LSTM to classify the text and finally transform the document into structure form <br/>
**Result**: Achieved text detected precision 98% and text recognition recall 96% <br/>

## Spam Text Detection and Block in Educational Forum 
**Primary Goal**: To increase the spam block accuracy to 98%+ and save $30,000+ annually <br/>
**Solution**: Expanded NSFW text to 100,000 with Snorkel Framework, then design a Neural Network model with residual and gate inspired by LSTM and Logistic Regression <br/>
**Result**: Achieved 98.5% f1-score and blocked 50,000 spam test/month <br/>

## Insurance Fraud Detection 
**Primary Goal**: To deploy models to a Web UI to predict if a customer is placing a fraudulent insurance claim <br/>
**Solution**: Applied MySQL to converged multiple data source and applied feature engineering to deal with missing <br/>
values, outliers, numeric data scaling, ordinal and category data encoding in PyCharm, then conducted XGBOOSTand SVM with Grid Search to classify non-fraud and fraud. Finally employed FLASK and Docker to deploy models <br/>
**Result**: Input prediction file to Web UI, it will return prediction result with best tuned model <br/>

## Building Energy Consumption Prediction 
**Primary Goal**: To predict building’s energy consumption based on building types and climate parameters <br/>
**Solution**: Applied EDA and feature engineering with Python in Jupyter Notebook. Used Light GBM to predict the building energy consumption <br/>
**Result**: Achieved RMSE with 17.72(the mean of target feature, Energy Use Intensity, is 82.58) <br/>

## Ads pops-up window detection and block 
**Primary goal**: detect NSFW pops-up window screenshots and replace current rule-based detector with neural network models. <br/>
**Solution**: crawled NSFW images from search engine and manually labeled 1w images; employed VGG16 to classify the images, deployed the projects with Docker; review bad cases and update model monthly <br/>
**Result**: achieved 99% F1-score and this novel service become the core high-light functions of the company’s products <br/>

## Project: Applied data analysis in price negotiation
**Primary Goal**: To help sales department to conduct better price negotiation <br/>
**Solution**: Combined client’s past 3+ years quotation record with raw material market index to figure out the logic of quotation, visualized it by PowerBI <br/>
**Result**: Avoid unnecessary price down when market price went down and saved $300,000+ profit annually <br/>
