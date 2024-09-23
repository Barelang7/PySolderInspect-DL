# PCB_Inspection_Using_Basler_Camera
## Defected PCB
![PCB defect](Image\PCB_Defect.png)
If there is a defect on the PCB, a red indicator will appear and there will be a notification regarding the defects on the PCB
## Zero Defect PCB
![Zero defect PCB](Image/Zero_Defect_PCB.png)
If there are no defects on the PCB, a red indicator will appear

# How to instalation
#### Note: PCB Inspection software runs on windows 10 and uses python 3.9
Install Basler camera [software](https://www2.baslerweb.com/en/downloads/software-downloads/software-pylon-8-0-0-windows/) suit windows

Install [Edge TPU runtime](https://coral.ai/docs/accelerator/get-started/)

 Install the PyCoral library :
 ```
 python3 -m pip install --extra-index-url https://google-coral.github.io/py-repo/ pycoral~=2.0

```
Intall the pypylon library :
```
pip install pypylon
```
Install the tk library :
```
pip install tk
```
Install the opencv library :
```
pip install opencv-python
```
clone the github repository and run PCB Inspection.exe
