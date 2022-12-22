# CS433-Project2
This is our repo for the 2nd project done in CS433 class. 

Because of the restrictions and terms of service of the Twitter data, the original data is not included in the repo. 

However, all the intermediary data are present and are organized as follows: 

1) Processed: Contains CSV files of the processed data, organized by language. 

2) Results: Contains results accumulated across the development of the algorithms, all in TXT file format. 

3) Vectors: Contains all the vector representations in different features spaces (see paper) used in the project, organized by language.  

The code based is organized as follows: 

1) The clean_notebook is a single Jupyter notebook that processes all the data and run all the classical machine learning (see Paper) algorithms. 

2) Notebook_transformer is a single Jupyter notebook that runs all the transformer-based models. It was developed and used in the Google Colab environment to make use of NVIDIA k80 GPU, and we strongly recommend using it in this capacity (see Appendix A for run times of models in the submitted paper). The notebook simply needs is a CSV file (e.g: Processed/English/csv_processed.csv file) that should be uploaded at the root of the Colab environment (change the dir_path variable accordingly). 

For all and any other questions not address, please feel free to reach out to vincent [dot] dandenault [at] epfl [dot] ch. 
