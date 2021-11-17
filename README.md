# Aircrafts Dataset Generator

Use the notebook generatedataset.ipynb to crawl the site JetPhotos.com and create a dataset of aircraft models containing 255x400 images. 
I have created this implementation during a course of Deep Learning due to students asked me about real data to evaluate their convolutional neural networks.


## Usage

Just get the notebook and execute the function **run()** passing some params: list of aircraft models, list of pages will be downloaded and directory to save the images. 

```py

run(["Embraer+190-400STD", "Airbus+A220-371"], 
    range(1,11), 
    "dataset/train/")

```
Executing the above code should produce something like following:
```
├── dataset
│    ├── train
│    │    ├── Airbus+A220-371  
│    │    │    ├── 83206_1634827144.jpg
│    │    │    ├── 81794_1633744364.jpg
│    │    │    ├── ...
│    │    │
│    │    ├── Embraer+190-400STD |
│    │    │    ├── 91965_1620646685.jpg
│    │    │    ├── 93004_1617558467.jpg
│    │    │    ├── ...
                
```

