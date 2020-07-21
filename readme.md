Pratik Parekh
Tannu Singh
Srishti Tiwary


Amzaon Web Service
EMR Notebook

Python: Version 3.6

How to Run:

Step1: Set up EMR Notebook Cluster
Step2: Upload the submitted notebook and dataset in the your S3 bucket under folder 'Notebook/YOUR_NOTEBOOK_ID'
Step3: open the Notebook cluster and open jupyter lab and 
Step4: open the sumbitted notebook and change the kernel to "Pyspark" and change path to your s3 bucket in spark.read_csv function to read the dataset.
step5: Change the location of input file to the location were input file is stored in S3.
Step6: Run all cell of Notebook.