The following repository contains the code for 'Toxicity in Online Conversations' paper.

# How to run

1. Install Docker
2. Download voat_labeled_data_unified.parquet from [this link](https://osf.io/fq5dy/) into the data/Labeled/Voat folder
3. In the repository home, create the container by typing
```
docker-compose up --build -d
```
3. To run the container, type
```
docker-compose up -d
```

The script automatically runs the code to create main figures and table for Voat dataset, which can be found in the figures and data folders, respectively.

To inspect the code by using RStudio, type localhost:8787 on your browser to access the RStudio Server installation in the container.
