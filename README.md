# tpconf_bin_xml.py

Simple command line utility to convert TP-Link modem/router backup config files from binary to XML and back:
- conf.bin ➡ decrypt, md5hash and uncompress ➡ conf.xml
- conf.xml ➡ compress, md5hash and encrypt ➡ conf.bin

*Should work for TP-Link models: TD-W8970, TD-W8980, TD-W9970, TD-W9980 (thanks d3dave), Archer VR900, C2, C20 and C60 (d3dave).*<br>
*May or may not work with other TP-Link modem/routers, newer firmwares.*

## Install Termux Commands


pkg update -y

pkg install git -y

pkg install python -y

pip install pycryptodome

git clone https://github.com/W8SOJIB/W8Tplink-AdminPannelHack

ls
chmod +x w8tpconf_bin_xml.py

cd w8tpconf_bin_xml

Termux Storage
(Permission Allow)

python w8tpconf_bin_xml.py /storage/emulated/0/conf.bin 1.xml 

ls

cat 1.xml

Facebook Page
https://www.facebook.com/w8team

My Facebook
https://www.facebook.com/W8Vai/
