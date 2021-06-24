# AVA_Project
traffic violation detection

- based on opensource Yolov3  GitHub      : https://github.com/pythonlessons/TensorFlow-2.x-YOLOv3

- Prequisite:
Docker image nvcr.io/nvidia/tensorflow:20.12-tf2-py3 is used in the docker file and for more details, please refer to 
https://ngc.nvidia.com/catalog/containers/nvidia:tensorflow/tags


to build docker image using Dockerfile defined in this repo:
docker build . -t <image_name>:<image_tag>

to run the docket image
docker run --gpus all -it --rm -p 8888:8888 -v <path_to_repo>:/workspace/project <image_name>:<image_tag>


- to run:
python file to run AVA_TrafficViolationDetection.py
store input video in Test_input

Github: https://github.com/ThiTranWork/AVA_Project

