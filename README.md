apt update && apt upgrade
apt install git -y
git clone https://github.com/hickin-hack/Cut-X
cd Cut-X
chmod +x *
bash setup.sh
python Cut-X.py
