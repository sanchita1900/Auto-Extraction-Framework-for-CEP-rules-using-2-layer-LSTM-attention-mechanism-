# Auto-Extraction-Framework-for-CEP-rules-using-2-layer-LSTM-attention-mechanism-

Steps to run the code:
1. Along with main.ipynb file upload rules, rules extraction, dataset provided and images files on drive.
2. Install apache-flink
3. Import all the necessary python libraries and frameworks.
4. import pyflink for generating data streams.
5. Run the code for Decision Tree and Random Tree rule extraction algorithms.

Project Implementation Details:
1. Apache-flink is installed for generating datastreams from given Delhi Climate unlabeled dataset.
2. Our aim is to predict rain by considering parameters like mean temperature and mean humidity.
3. All the necessary python libraries and frameworks are installed.
4. Data is read from dataset using Pandas.
5. Data is preprocessed by dropping all the rows with NaN values.
6. Using LSTM, data is labeled with binary values denoting whether rain will occur or not.
7. On the labeled dataset, datastream generation process is applied using pyflink.
8. On the labeled dataset, apply mean encoding for converting integer values of temperature and humidity to floating values to create a more realistic scenario.
9. Train and fit the model using Decision Tree Classifier and find the predicted values of testing data.
10. Extract rules from the generated decision tree model.
