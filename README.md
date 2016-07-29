instal python, pip dan protobuf 3
Requirements

1. - [Python 2.7.x](http://docs.python-guide.org/en/latest/starting/installation/)
2. - [pip](https://pip.pypa.io/en/stable/installing/)


Protobuf 3 installation


3. - Windows: Download protobuf 3.0: [disini](https://github.com/google/protobuf/releases/download/v3.0.0-beta-4/protoc-3.0.0-beta-4-win32.zip) unzip dan copy `bin/protoc.exe` ke folder bot.


4.Instal pyaml terlebih dahulu  [installer](http://pyyaml.org/wiki/PyYAML).

	untuk Windows 10:
		   Buka [disini](http://www.lfd.uci.edu/~gohlke/pythonlibs/#pyyaml) dan download: PyYAML-3.11-cp27-cp27m-win32.whl   
		    (jika 64 bit maka muncul' error,
		    download the 64 bit version instead: PyYAML-3.11-cp27-cp27m-win_amd64.whl )

5. masuk kedalam folder download yaml lalu ketik:
```
> pip install PyYAML-3.11-cp27-cp27m-win32.whl
// if you needed to download the 64-bit version)
// (replace PyYAML-3.11-cp27-cp27m-win32.whl with PyYAML-3.11-cp27-cp27m-win_amd64.whl

```
6. download bot nya [disini](https://github.com/bhagas/BOT_VALOR_SMG/archive/master.zip)
7. masuk kedalam folder download
8. setting config.json (user password dan lokasi)
9. setting release_config.json (untuk auto transfer sesuai cp yg diinginkan)

```
> pip install -r requirements.txt  

```
10. untuk menjalankan ketik: 
```
 
> pokecli.py 
```