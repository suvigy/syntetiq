## Challange0

Since I'm coming from the R world for classical machine learning and I used h2o now I applied h2o instead of sklearn for python

### Dependencies

For python you need the followings. If you have anaconda installed you just have to issue the following commands.

```
conda install -c h2oai h2o=3.16.0.2
conda install matplotlib
conda install pandas
```

Note that h2o will need also **java 7-8** installed. On h2o.init() it will start a server in the background. 

### Configuraiton

In the configuration section set the ```data_path``` to the data.tsv

### Running

Run the notebook

## Challenge1

### Dependencies

For python you need the followings. If you have anaconda installed you just have to issue the following commands.
```
conda install matplotlib
conda install tensorflow
conda install keras
conda install scikit-learn
conda install pillow
```

### Configuration

Please unzip the images to a folder the notebook can read. Set the ```data_path``` to the folder with the images.
Please also set ```tensorboard_logs``` to a dir in which tensorflow can write the logs.

### Running

Run the notebook

