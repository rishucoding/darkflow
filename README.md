This model has been forked from: https://github.com/thtrieu/darkflow (Open this link to set the environment)

1. For 'yolo.weights' file, please check this link: https://drive.google.com/drive/folders/0B1tW_VtY7onidEwyQ2FtQVplWEU

2. To test the model on a video file, using gpu : 
	$ python flow --model cfg/yolo.cfg --load bin/yolo.weights --demo cats_dogs.webm --gpu 1.0 --saveVideo

3. The video files for the above model are availabe at this link: https://drive.google.com/open?id=1yUaNdtwdaEb8wQcGLys2B85m7_-nQWhK


My system description
1. Main Memory/RAM : 32GB
2. Processor: Intel® Core™ i7-8700 CPU @ 3.20GHz × 12 
3. Graphics: GeForce GTX 1080 Ti/PCIe/SSE2
4. Hard Disk Space: 366.5 GB
5. OS type: 64bit, ubuntu 16.04LTS


Here is the console log from $ nvideo-smi:
Sun Dec  2 19:43:54 2018
+-----------------------------------------------------------------------------+
| NVIDIA-SMI 396.54                 Driver Version: 396.54                    |
|-------------------------------+----------------------+----------------------+
| GPU  Name        Persistence-M| Bus-Id        Disp.A | Volatile Uncorr. ECC |
| Fan  Temp  Perf  Pwr:Usage/Cap|         Memory-Usage | GPU-Util  Compute M. |
|===============================+======================+======================|
|   0  GeForce GTX 108...  Off  | 00000000:01:00.0  On |                  N/A |
| 27%   33C    P8    11W / 250W |    548MiB / 11175MiB |      0%      Default |
+-------------------------------+----------------------+----------------------+
                                                                               
+-----------------------------------------------------------------------------+
| Processes:                                                       GPU Memory |
|  GPU       PID   Type   Process name                             Usage      |
|=============================================================================|
|    0      1105      G   /usr/lib/xorg/Xorg                           335MiB |
|    0      1774      G   compiz                                       204MiB |
|    0      2486      G   /usr/lib/firefox/firefox                       2MiB |
|    0      2741      G   /usr/lib/firefox/firefox                       2MiB |
 


