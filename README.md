# PySolderInspect DL
## Solder Defect Detection Application on Printed Circuit Board (PCB) Based on Deep Learning

PySolderInspect DL is a Deep Learning-based application designed to automatically detect solder defects on Printed Circuit Boards (PCBs). The app uses a special camera and supporting hardware to capture images of the PCB, then analyzes the solder results to detect any damage or defects, such as opens, short circuits, or excessive solder thickness. With a user-friendly interface, users can perform inspections efficiently, reducing time and potential errors in manual checking. This application is expected to help improve the quality of electronics production by maintaining high visual inspection standards.

## Example Detection on Reject Sample
![PCB defect](Image/PCB_Defect.png)

## Example Detection on Good Sample
![Zero defect PCB](Image/Zero_Defect_PCB.png)

# How to Install
#### Note: PCB Inspection software runs on Windows 10 and uses Python 3.9
Install Basler camera [software](https://www2.baslerweb.com/en/downloads/software-downloads/software-pylon-8-0-0-windows/) suit windows

Install [Edge TPU runtime](https://coral.ai/docs/accelerator/get-started/)

Install the PyCoral
```
python3 -m pip install --extra-index-url https://google-coral.github.io/py-repo/ pycoral~=2.0
```
Install the PyPylon, Tkinter, and OpenCV
```
pip install pypylon tk opencv-python
```

Install the opencv library :
```
pip install opencv-python
```
clone the github repository and run PCB Inspection.exe
