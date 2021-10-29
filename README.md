# StackExchange_DataAnalysis_UsingMR-Hive-Pig
Analyzing Top 200000 posts available in Stack Exchange using Pig, Hive and MapReduce. 
Also, calculating per-user TF-IDF of the top 10 terms for each of the top 10 users.
Implemented the assignment in Google Cloud Platform(GCP) and locally using VirtualBox Ubuntu server.
This repository contains 2 folders Cloud_GCP and Ubuntu_Local. Each folders have subfolders called PIG & HIVE and TF-IDF which contains subfolders for screenshots,results otained and code files.
Please refer the Documentation folder(PIG & HIVE.doc) for Step by Step document on Data Extraction, DataSet Clenaing usig PIG and running queries against cleaned dataset using HIVE.
Please refer the Documentation folder(TFIDF.doc) for Step by Step document on implementation of TFIDF.
Both documents have screenshots and detailed steps and can be used for implementations on Cloud GCP and local ubuntu server.


References:
https://gitlab.computing.dcu.ie/khaira2/ca675_cloud_technologies_assignment1
https://pig.apache.org/docs/r0.17.0/api/org/apache/pig/piggybank/storage/CSVExcelStorage.html
https://geeksforgeeks.org/tf-idf-model-for-page-ranking
