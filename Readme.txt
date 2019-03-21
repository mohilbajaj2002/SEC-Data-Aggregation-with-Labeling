


 *** Data Aggregation, Date and Event Extraction and Data Labeling for Topic Modeling ***


 This project was a Proof of Concept (POC) validation check for a Singapore based Fintech. The firm wanted to develop systems to extract SEC data available publicly through their online database and then perform NLP (Topic Modeling)/ Machine Learning on top of it to identify high performing stocks.  

To check the valididty of the idea, the projects attempts to perform all the required tasks on 2 stocks, Microsoft and Apple from 2016 to 2018. It starts by aggregating data from the SEC database using BeautifulSoup and then identifies texts which have dates associated with it. Topic modeling would be performed on these texts. But, since machine learning requires labeled data, first principles were used to classify texts and generate labels. Multiple models were tried using equal and unequal weights till decent accuracies were achieved. The advanced model developed could be used to generate labels for the data and once sufficient numbers were achieved, regular machine learning/deep learning models could be developed on top of it.   

The project also looks at extracting fundamental data from tables present in these documents. 

The project contains the following files and folders:

- Data Aggregation, Date and Event Extraction and Data Labeling for Topic Modeling. ipynb: This is the main scripting file that explores the various ideas described above.

- Event Classification (Folder): This is the folder that contains files with dated texts. These files are generated on running the script.    
