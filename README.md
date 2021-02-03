# Dense and K-Connected common subgraph

## experiment part

1. GCN improvement from label propagation

    - datasets are available https://drive.google.com/drive/folders/1yb_BV5KRYjG9P5bQrt2NUDqvEROnfAep?usp=sharing
    
    - LP and MLP results are generated with lp.ipynb
    
    - GCN results are generated with vanilla GCN. Code under GCN-TF2.0 folder modified from https://github.com/cshjin/GCN-TF2.0.
    
    - Training, validation, testing ratio is 0.6, 0.2, 0.2. Experiment run five times on each dataset and the average 
    accuracy is calculated. Random seeds are set from 0 to 4 for reproduction purpose.
      
    - common subgraph extraction together with result plots are in kconn_mindeg.ipynb.
    
2. Are Twitter graphs homophilous?

    - dataset is from https://github.com/twittermancer/The_Twitter_Mancer_Project
    
    - run the code in twitter_dense_k.ipynb
   
3. Enron Email "mailto" and "cc" network

   - dataset https://www.cs.cmu.edu/~./enron/
   
   - run code in enron_new.ipynb for preprocessing and extracting common subgraph.