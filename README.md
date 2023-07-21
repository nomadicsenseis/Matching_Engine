# Matching_Engine
In this code I implement a pretrained SBERT model, alongside a classical tf-idf algorithm (BM25), on an information retrieval task. I play around with the architectures, and I compare the results using classical Information retrieval metrics. I also parallelize the computations building an Apache Beam pipeline.

I provide a notebook with the best performing architecture. It has a well documented modular version that has not been implemented into production (if for any reason it does not work, please refer to the experimental version). 

The code can be runned through colab (connecting it to the GCP in the usual manner the project name and the user credentials). It can be runned with the instance provided by Colab. In case of wanting an authomatization, the cell can be copy and pasted onto a Cloud Funtion, and later be runned with minor changes.
