# wide_deep_POI

1. Install Tensorflow

2. Download this repo\
Download train.data and test.data from the following link and place it inside the data subfolder in this repo\
https://drive.google.com/drive/u/7/folders/1mr5lVOuhZVOIevpWjvMTlFyaIP4kYAh1

3. set the PYTHONPATH to the path to your wide_deep_POI folder\
export PYTHONPATH=path/to/wide_deep_POI/on/your/PC

4. cd into wide_deep subfolder, run python3 wide_deep.py\
Use --wide or --deep for the above command to run wide or deep model only.

5. To view graphs, run the following and view on the browser at 127.0.0.1:6006.\
tensorboard --logdir=/path/to/your/generated/model/subfolder --host=127.0.0.1

