===============
berpublicsearch
===============

The aim of this repository is to simplify working work with SEAI's BER Public search dataset

... with the help of the open source `Python` software `prefect`, `dask` and `requests`

... via:

- A `Jupyter Notebook` sandbox environment
- A `berpublicsearch` `Python` library 

------------

Benefits of the sandbox
-----------------------

- It's free
- It's fast ... can be run on the cloud via `Google Collab` 
- It downloads the dataset directly ... so no need to login to the SEAI data portal
- It enables wrangling of large, 'live' data (1GB) 

------------

Benefits of the `berpublicsearch` library
-----------------------------------------

- It can be imported by other projects to automate the downloading of the ber dataset and (optionally) conversion to `parquet`

------------

Installation
------------

To setup the `berpublicsearch` sandbox:

- Google Collab:

    - Click the Google Collab badge & open `sandbox.ipynb`:
    
        .. image:: https://colab.research.google.com/assets/colab-badge.svg
                :target: https://colab.research.google.com/github/codema-dev/berpublicsearch
                
    - Mount your Google Drive to your Google Collab instance & refresh your filetree

        .. image:: images/mount-gdrive.jpg
    
    - Copy the path to your Google Drive data folder and paste it into the appropriate string

        .. image:: images/copy-path.png

    - For more information see `External data: Local Files, Drive, Sheets, and Cloud Storage`__
    
    __ https://colab.research.google.com/notebooks/io.ipynb

- Local:
    - Unzip the dataset
    - Clone this repository locally via :code:`git clone https://github.com/codema-dev/berpublicsearch` 
    - Launch `Jupyter Notebook` and open the relevant sandbox file in the `notebooks` folder 
