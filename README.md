# CadexGUI

![image](https://i.imgur.com/19HrseK.png)

Cadex is a cryptonote base coin, that carry privacy as its watch word. This is the source for its GUI
# Compilation of CADEX GUI 
* For LINUX 
### Install Dependencies
```
apt-get install -y cmake libboost-dev libboost-date-time-dev libboost-program-options-dev libboost-regex-dev libboost-serialization-dev libboost-system-dev libboost-thread-dev libboost-chrono-dev libboost-filesystem-dev
```

then clone repository, with submodules.
```
sudo git clone --recurse-submodules https://github.com/cadexdev/CaexGUI.git
```
# After that you need to build the wallet
```
sudo mkdir build && cd build && sudo cmake .. && sudo make
```
#Cadex GUI wallet will be in the build directory in the as #CADEX run in terminal or double click #CADEX to open the wallet
run in terminal as 
```
sudo ./CADEX
```

* For Mac 
# Install Dependencies for Mac 
#Install boost
```
brew install boost
```
#Install cmake
```
brew install cmake

```
#Clone the repository including the submodules.
```
sudo git clone --recurse-submodules https://github.com/cadexdev/CadexGUI.git
```


