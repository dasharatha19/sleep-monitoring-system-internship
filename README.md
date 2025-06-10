# sleep-monitoring-system-internship
main files.ipynb contains cells of code where it includes convertion of annotation files from widerface format to yolo format for ease of training(for training set),checking the converted yolo format annotation files by placing them original image( to check the convertion effciency), genrating anchor boxes based on wider face dataset using k means clustering that helps for tiny yolo v2 model and convertion of annotation files from widerface format to yolo format for validation datasets.

final_stiff_to.ipynb file contain complete step by step code for custom laoding the dataset,creating batches,defining the tiny yolo v2 architecture(compatible for microcontroller),loss function, validation datasetloader,training loop,validation loop,tesing model performance and real time inference.

deep_final.ipynb file contains the light weight High resolution network for deep pose estimation and face detection,caluculates ear ,mar and blink rate and based on that details we make sleep behaviour classification. 

wider face link-http://shuoyang1213.me/WIDERFACE/

Download 4 files (WIDER_train,WIDER_test,WIDER_val and the annotation file)

WFLW link-https://wywu.github.io/projects/LAB/WFLW.html

Download 2 files (WFLW training and testing image,WFLW Face annotation)

Before running the code try to change the path and run.
