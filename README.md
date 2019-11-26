# Tensorflow Lite on Raspberry Pi4B

# Requirement
+ Pi4B
+ System Image: Buster
+ python 3+(3.7 recommend)
+ tensorflow lite 1.14.0

# Install
- ```git clone git@github.com:whgreate/pi4b_tensorflow_lite.git ```

- ``` cd pi4b_tensorflow_lite.git ```

- ``` pip install tflite_runtime-1.14.0-cp37-cp37m-linux_armv7l.whl ```

- for numpy: 
``` sudo apt-get install libatlas-base-dev ```

- for pillow: 
``` sudo apt-get install libjpeg-dev ```

- ``` virtualenv ENV ```
- ``` source ENV/bin/activate ```

- ``` pip install -r requirements.txt ```



# run image classification
``` python label_image.py -m mobilenet_v1_1.0_224_quant.tflite -l labels_mobilenet_quant_v1_224.txt -i grace_hopper.bmp ```

# Reference
[Python quickstart](https://www.tensorflow.org/lite/guide/python)

