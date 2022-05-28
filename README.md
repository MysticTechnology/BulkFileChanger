# BulkFileChanger
This is a simple script that allows you to change or remove characters in the name of all files in a directory and its sub-directories. Example use case: say you have a bunch of files that have "test-" in front of the names of every single file in the directory. You want to change all files with that prefix to "prod-". You can use this script to make the change all in one go.
* Github repo: https://github.com/MysticTechnology/BulkFileChanger
* PyPi: https://pypi.org/project/BulkFileChanger/

## Installation
There are a couple of options to install this app:
* Pip Install - This app is hosted on PyPi and can be installed with the following command:
```
pip3 install BulkFileChanger
```
* Local Install - Alternatively, you can download or git clone the Github repo and install it locally with the following:
```
git clone https://github.com/MysticTechnology/BulkFileChanger.git
cd BulkFileChanger
pip3 install -e .
```
To uninstall this app:
```
pip3 uninstall BulkFileChanger
```
* If you used the local install option, you will also want to delete the ```.egg-info``` file located in the ```src/``` directory of the package. This gets created automatically with ```pip3 install -e .```.

## Usage
After installation, you have a couple ways to run this app.
* Run this app from the terminal with this command:
```
bulkfilechanger
```
* Run this app with the python command ```python3 -m```:
```
python3 -m bulkfilechanger
```
* You can also import the package resources and run them in your own project:
```
from bulkfilechanger import *
bulkfilechanger = BulkFileChanger()
bulkfilechanger.run()
```

## Support and Contributions
Our software is open source and free for public use. If you found any of these repos useful and would like to support this project financially, feel free to donate to our bitcoin address.

Bitcoin Address 1: 1GZQY6hMwszqxCmbC6uGxkyD5HKPhK1Pmf

![alt text](https://github.com/MysticTechnology/BitcoinAddresses/blob/main/btcaddr1.png?raw=true)
