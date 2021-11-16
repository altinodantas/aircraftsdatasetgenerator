# Aircrafts Dataset Generator

Use this notebook to crawl the site JetPhotos and create a dataset on aircraft models. 

I have created this implementation during a course of Deep Learning due students ask me about real data to evaluate their convolutional neural networks.


## Usage

Just get the notebook and execute the function **run()** passing some params: list of aircraft models, list of pages will be downloaded and diretory to save the images.

```py

run(["Embraer+190-200IGW", "Embraer+190-400STD", "Airbus+A220-371"], range(1,11), "dataset/train/")

```
