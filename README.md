# tensorflowAVP
Tensorflow Adversarial Video Prediction 

Requirements

1. Tensorflow
2. Python 3.6
3. Pillow
4. Scipy
5. numpy


1. To process frames run `python process_data` .
2. To run the prediction model `python avg_runner.py -l ./Models/Adversarial/model.ckpt-500000`


The Models would be generated automatically while processing data. 
Generating the model would take a long time. For best results use CUDA accelaration
