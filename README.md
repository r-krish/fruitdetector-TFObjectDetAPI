# fruitdetector-TFObjectDetAPI

# Fruit Detector 
   This project uses pretrained model [EfficientDet D0 512x512](http://download.tensorflow.org/models/object_detection/tf2/20200711/efficientdet_d0_coco17_tpu-32.tar.gz)
   for custom object detection. The custom model is trained on [Kaggle fruit dataset](https://www.kaggle.com/datasets/mbkinaci/fruit-images-for-object-detection)
   This labelled dataset has images belonging to three classes {_apple_,_banana_,_orange_}.
   
   This model was trained for 15000 steps with base learning_rate of 0.0079 and warmup_learning_rate of 0.001
   
   <p>The loss and accuracy metrics are given below:</p>
   
   <img align="center" src="https://github.com/r-krish/fruitdetector-TFObjectDetAPI/blob/main/extras/metrics-1.png" width="90%" height="90%"/>
   
   <p>The validation images are given below:</p>
   <div align='center'>
   <img src="https://github.com/r-krish/fruitdetector-TFObjectDetAPI/blob/main/extras/val-1.png" width="800px" height="500px"/>
   <img src="https://github.com/r-krish/fruitdetector-TFObjectDetAPI/blob/main/extras/val-2.png" width="700px" height="400px"/>
   <img src="https://github.com/r-krish/fruitdetector-TFObjectDetAPI/blob/main/extras/val-3.png" width="700px" height="400px"/>
   <img src="https://github.com/r-krish/fruitdetector-TFObjectDetAPI/blob/main/extras/val-4.png" width="800px" height="400px"/>
   </div>
 
