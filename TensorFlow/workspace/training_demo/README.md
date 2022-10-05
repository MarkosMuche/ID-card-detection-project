

installing tensorflow-object-detection api

https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html


python TensorFlow/scripts/preprocessing/generate_tfrecord.py -x TensorFlow/workspace/training_demo/images/train/ -l TensorFlow/workspace/training_demo/annotations/label_map.pbtxt -o TensorFlow/workspace/training_demo/annotations/train.record

python TensorFlow/scripts/preprocessing/generate_tfrecord.py -x TensorFlow/workspace/training_demo/images/test/ -l TensorFlow/workspace/training_demo/annotations/label_map.pbtxt -o TensorFlow/workspace/training_demo/annotations/test.record
