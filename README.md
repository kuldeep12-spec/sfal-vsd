# sfal-vsd

week 0

Yosys

sudo apt-get update

git clone https://github.com/YosysHQ/yosys.git 

cd yosys 

sudo apt install make (If make is not installed please install it) 

sudo apt-get install build-essential clang bison flex \

libreadline-dev gawk tcl-dev libffi-dev git \
graphviz xdot pkg-config python3 libboost-system-dev \
libboost-python-dev libboost-filesystem-dev zlib1g-dev 

make config-gcc 

make 

sudo make install

<img width="797" height="706" alt="Screenshot from 2025-09-20 21-08-03" src="https://github.com/user-attachments/assets/aad464bb-8d93-406c-b24f-504da40c4a94" />

Iverilog

Steps to install iverilog

sudo apt-get update

sudo apt-get install iverilog

<img width="767" height="288" alt="Screenshot from 2025-09-20 21-09-10" src="https://github.com/user-attachments/assets/fb65e15f-f700-45ff-84ae-b4d4189ee1e3" />


gtkwave

Steps to install gtkwave

sudo apt-get update

sudo apt install gtkwave

<img width="662" height="180" alt="Screenshot from 2025-09-20 21-12-02" src="https://github.com/user-attachments/assets/c0b6e240-0ed1-490c-8f97-dd4ea619eecc" />


ngspice

After downloading the tarball from https://sourceforge.net/projects/ngspice/files/ to a local
directory, unpack it using:

$ tar -zxvf ngspice-37.tar.gz

$ cd ngspice-37

$ mkdir release

$ cd release

$ ../configure --with-x --with-readline=yes --disable-debug

$ make

$ sudo make install

<img width="799" height="260" alt="Screenshot from 2025-09-20 21-46-16" src="https://github.com/user-attachments/assets/f132d70d-8521-4e94-bdc0-581eba7246bf" />

magic

$ sudo apt-get install m4

$ sudo apt-get install tcsh

$ sudo apt-get install csh

$ sudo apt-get install libx11-dev

$ sudo apt-get install tcl-dev tk-dev

$ sudo apt-get install libcairo2-dev

$ sudo apt-get install mesa-common-dev libglu1-mesa-dev

$ sudo apt-get install libncurses-dev

git clone https://github.com/RTimothyEdwards/magic

cd magic

./configure

make

make install


<img width="1438" height="850" alt="Screenshot from 2025-09-20 21-50-29" src="https://github.com/user-attachments/assets/45434085-9d3a-4291-ac80-155407aed5e3" />


OpenLANE-

sudo apt-get update

sudo apt-get upgrade

sudo apt install -y build-essential python3 python3-venv python3-pip make git

sudo apt install apt-transport-https ca-certificates curl software-properties-common

curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o
/usr/share/keyrings/docker-archive-keyring.gpg

echo "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg]
https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee
/etc/apt/sources.list.d/docker.list > /dev/null

sudo apt update

sudo apt install docker-ce docker-ce-cli containerd.io

sudo docker run hello-world

sudo groupadd docker

sudo usermod -aG docker $USER

sudo reboot

# After reboot

docker run hello-world


<img width="983" height="503" alt="Screenshot from 2025-09-20 22-02-26" src="https://github.com/user-attachments/assets/b2122654-5b0d-4476-a9e4-6cb3b1b195d9" />



Check dependencies

git --version

docker --version

python3 --version

python3 -m pip --version

make --version

python3 -m venv -h

<img width="1072" height="930" alt="Screenshot from 2025-09-20 22-01-35" src="https://github.com/user-attachments/assets/a066dd76-818e-483c-8fad-e3f30141740e" />


