# Deforestation Detection in Cerrado with Deep Learning and Image Time Series

Jupyter Notebooks for the combination of LSTM and U-Net for the detection of deforestation in Cerrado, using Sentinel or Landsat image time series obtained from Brazil Data Cube.

## Order for execution

The suggested order for the scripts execution is as follows:

+ ./Scripts
    + Download
        + Download Images from BDC.ipynb
    + Create Cubes
        + Clip Files with Shapefile.ipynb
        + Create Data Cube Stacks.ipynb
        + Gap Filling.ipynb
    + LSTM
        + LSTM - Create Samples.ipynb
        + LSTM - Train.ipynb
        + LSTM - Predict.ipynb
    + UNET
        + UNET - Create Stack.ipynb
        + UNET - Create Samples.ipynb
        + UNET - Train.ipynb
        + UNET - Predict.ipynb
    
## Contact

+ Bruno M. Matosak
+ bruno.matosak at inpe.br