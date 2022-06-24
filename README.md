# DoS_detection_mitigation
6th Semester project work

**Commands to install mininet(In Linux)**
Install Git:
sudo apt-get install git-core
Clone the mininet git repository:
git clone https://github.com/mininet/mininet
Go to the mininet directory:
cd mininet/
Find the various versions of mininet available:
git tag
Select and checkout to a specific version
git checkout -b 2.3.0rc2
cd to util directory inside mininet:
cd utils
Install mininet and its dependency:
./install.sh -a
Confirm installation:
sudo mn --version
