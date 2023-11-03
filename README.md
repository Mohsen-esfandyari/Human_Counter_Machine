## About Human_Counter_Machine

Human Counter Machine is a python program designed to count people in an input image. It is based on an Object Detection algorithm (HOG + Linear SVM) to better detect people based on a pre-trained model.
This project uses the OpenCV library for the image processing and detection part.

It is my project for the Artificial Intelligence course in Azad University supervised by Dr. Dami


## Installation

```
git clone https://github.com/Mohsen-esfandyari/Human_Counter_Machine.git
```

## Recommended Python Version:

Human Counter Machine currently supports **Python 3**.

## Dependencies:

Human Counter Machine depends on the `opencv-python`, `imutils`, `numpy` and `argparse` python modules.


These dependencies can be installed using the requirements file:

- Installation on Windows:
```
c:\python39\python.exe -m pip install -r requirements.txt
```
- Installation on Linux
```
sudo pip install -r requirements.txt
```


## Usage

Short Form    | Long Form     | Description
------------- | ------------- | -------------
-i            | --image       | path to image test file directory
-h            | --help        | show the help message and exit

## Examples

* To list all the basic options and switches use -h or --help switch:

  ```python3 Human_Counter_Machine.py -h```
  or
  ```python3 Human_Counter_Machine.py --help```
  
* To set your an input image use -i or --image switch:

   ```python3 Human_Counter_Machine.py -i IMAGE```
  or
  ```python3 Human_Counter_Machine.py --image IMAGE```

