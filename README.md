

## Requirements

Ansible 2.8.4 (using the latest versions of Ansible, you may get an error when generating the env file)

Python 3.6.0+

## Usage

Clone repo
```
git clone https://github.com/xvost/UPIS.git
```
Change dir
```
cd ./UPIS
```
Rename data.conf
```
cp ./data.conf.example ./data_ipv6.conf
```
or
```
cp ./data.conf.example ./data_ipv4.conf
```
Edit data.conf
```
editor ./data_ipv6.conf
```
Start script
```
./start_install.py -c ipv6
```

OR

Change dir
```
cd ./UPIS
```
Start script at interactive mode
```
./start_install.py -i ipv6
```

## Known problems

1. Only Debian 8 with 3.* kernel at proxies nodes
2. Do not have interactive mode to ipv4 proxies only config file
3. Do not permit install ipv6 and ipv4 together.
