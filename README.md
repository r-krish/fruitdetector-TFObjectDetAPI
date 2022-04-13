# fruitdetector-TFObjectDetAPI

# Fruit Detector 
   This project uses pretrained model [EfficientDet D0 512x512](http://download.tensorflow.org/models/object_detection/tf2/20200711/efficientdet_d0_coco17_tpu-32.tar.gz)
   for custom object detection. The custom model is trained on [Kaggle fruit dataset](https://www.kaggle.com/datasets/mbkinaci/fruit-images-for-object-detection)
   This labelled dataset has images belonging to three classes {_apple_,_banana_,_orange_}.
   
   This model was trained for 15000 steps with base learning_rate of 0.0079 and warmup_learning_rate of 0.001
   
   The loss and accuracy metrics are given below:
   
   
   ![metrics](https://drive.google.com/file/d/1t6Ha5YwOdCvv2QXi9arm5Bp-uPcj8eht/view?usp=sharing)
   <img src="https://drive.google.com/file/d/1t6Ha5YwOdCvv2QXi9arm5Bp-uPcj8eht/view?usp=sharing" width="50%" height="50%">
