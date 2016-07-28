instal python, pip dan protobuf 3
Requirements

- [Python 2.7.x](http://docs.python-guide.org/en/latest/starting/installation/)
- [pip](https://pip.pypa.io/en/stable/installing/)


Protobuf 3 installation


- Windows: Download protobuf 3.0: [here](https://github.com/google/protobuf/releases/download/v3.0.0-beta-4/protoc-3.0.0-beta-4-win32.zip) unzip dan copy `bin/protoc.exe` ke folder bot.





Instal pyaml terlebih dahulu  [installer](http://pyyaml.org/wiki/PyYAML).

Windows 10:
   Buka [this](http://www.lfd.uci.edu/~gohlke/pythonlibs/#pyyaml) page dan download: PyYAML-3.11-cp27-cp27m-win32.whl   
    (jika 64 bit maka muncul' error,
    download the 64 bit version instead: PyYAML-3.11-cp27-cp27m-win_amd64.whl )
```
copy pip ke folder bot

```
setting config.json (user password dan lokasi)
setting release_config.json (untuk auto transfer sesuai cp yg diinginkan)

$ cd ke folder bot  
$ pip install PyYAML-3.11-cp27-cp27m-win32.whl
// (ganti PyYAML-3.11-cp27-cp27m-win32.whl dengan PyYAML-3.11-cp27-cp27m-win_amd64.whl
// untuk 64-bit version)
$ pip install -r requirements.txt  
$ pokecli.py 
