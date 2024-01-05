#Installation d'une debian 12 minimal avec openbox
#post install en root
su -
apt install git
git clone https://github.com/jambalak/LINUX.git
cd LINUX
chmod +x debian-openbox
bash debian-openbox
