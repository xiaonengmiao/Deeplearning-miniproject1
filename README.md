# Deep Learning: Towards Deeper Understanding 

## Mini-Project 1. Identification of Raphael’s paintings from the forgeries

## Setup

It is recommended to use [`virtualenv`](http://docs.python-guide.org/en/latest/dev/virtualenvs/) to for the project. If you choose to use it, run the following (make sure you correctly installed `virtualenv`: `$pip install virtualenv`)

```bash
virtualenv -p python3 .env       # Create a virtual environment (python3)
source .env/bin/activate         # Activate the virtual environment
pip install -r requirements.txt  # Install dependencies
# Work on the project for a while ...
deactivate                       # Exit the virtual environment
```

## Download Data

The following data, provided by Prof. Yang WANG from HKUST,

[https://drive.google.com/folderview?id=0B-yDtwSjhaSCZ2FqN3AxQ3NJNTA&usp=sharing](https://drive.google.com/drive/folders/0B-yDtwSjhaSCZ2FqN3AxQ3NJNTA)

contains a 28 digital paintings of Raphael or forgeries.

Download the data and unzip it into data folder:

```bash
unzip data.zip -d data
```

## Start IPython

After you have the data, you should start the IPython notebook server from the miniproject1 directory, with the `jupyter notebook` command. You can now play around with the code.
