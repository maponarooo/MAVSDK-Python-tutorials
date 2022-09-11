# mavsdk-python-tutorials
MAVSDK Python Tutorials for PX4
https://mavsdk.mavlink.io/main/en/python/quickstart.html

## Python QuickStart
#### Prerequisites
Python 3.6+

#### 설치
$ pip3 install mavsdk
$ pip3 install aioconsole

#### 실행
$ make px4_sitl_default jmavsim
$ apython mavsdk.py


## Regular Installation
pip3 install mavsdk

git clone https://github.com/mavlink/MAVSDK-Python --recursive  
cd MAVSDK-Python  

#### First install the protoc plugin (protoc-gen-mavsdk):   
cd proto/pb_plugins   
pip3 install -r requirements.txt    
    
$ which protoc-gen-mavsdk   

#### install the dependencies of the SDK:   
cd ../..    
pip3 install -r requirements.txt -r requirements-dev.txt    
   
#### Generate the code   
./other/tools/run_protoc.sh   
   
