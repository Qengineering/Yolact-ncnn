# Yolact-ncnn on Raspberry Pi 64 bits
![output image]( https://qengineering.eu/images/Yolact_result_zebra.png )

## Yolact with the ncnn framework.
The frame rate is about 3.5 sec per image<br/>
Paper: https://openaccess.thecvf.com/content_ICCV_2019/papers/Bolya_YOLACT_Real-Time_Instance_Segmentation_ICCV_2019_paper.pdf <br/>
Size: 550x550 <br/><br/>
Special made for a bare Raspberry Pi see https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html <br/>
## Dependencies.
To run the application, you have to:
- A raspberry Pi 4 with a 64-bit operating system. It can be the Raspberry 64-bit OS, or Ubuntu 18.04 / 20.04. (https://qengineering.eu/install-raspberry-64-os.html) <br/>
- The Tencent ncnn framework installed. (https://qengineering.eu/install-ncnn-on-raspberry-pi-4.html) <br/>
- OpenCV 64 bit installed. (https://qengineering.eu/install-opencv-4.3-on-raspberry-64-os.html) <br/>
- Code::Blocks installed.
## Running the app.
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/Yolact-ncnn/archive/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
dog.jpg <br/>
elephant.jpeg <br/>
girafe.jpeg <br/>
mumbai.jpg <br/>
onyx.jpeg <br/>
result_elephant.png <br/>
result_zebra.png <br/>
Yolact.cpb <br/>
yolact.cpp <br/>
yolact.bin  (download this file from: https://drive.google.com/file/d/1vu3GGOEWh-jmedM-cvoqzhGzaZaOQB9k )<br/>
yolact.param <br/>
