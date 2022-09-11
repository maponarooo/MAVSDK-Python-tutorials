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
   

#### Home Point 변경   
export PX4_HOME_LAT=37.210534   
export PX4_HOME_LON=127.105790   
export PX4_HOME_ALT=28.5   
   
export PX4_SIM_SPEED_FACTOR=1   
   
