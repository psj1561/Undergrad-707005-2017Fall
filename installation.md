
## Windows 사용자
### Anaconda 설치
다음 파일을 다운로드.
```
https://repo.continuum.io/archive/Anaconda3-4.4.0-Windows-x86_64.exe
```
or 느린 경우
```
https://d.pr/WLcUs8
```
* 필요에 따라 환경변수에 path 등록

### pycharm 설치
* 다음 파일을 다운로드.
```
https://download.jetbrains.com/python/pycharm-community-2017.1.4.exe
```
or 느린 경우
```
https://d.pr/FhSUkq
```

### tensorflow 설치 (virtualenv)
```
> pip install virtualenv
> virtualenv tensorflow
> tensorflow\Scripts\activate
> pip install --upgrade tensorflow
```

### tensorflow 테스트
$ python
Python 2.7.10 (default, Feb  7 2017, 00:08:15)
[GCC 4.2.1 Compatible Apple LLVM 8.0.0 (clang-800.0.34)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import tensorflow as tf

## Mac 사용자
### Anaconda 설치
* Python 3.6 version
```
https://repo.continuum.io/archive/Anaconda3-4.4.0-MacOSX-x86_64.pkg
```

* Python 2.7 version
```
https://repo.continuum.io/archive/Anaconda2-4.4.0-MacOSX-x86_64.pkg
```

### pycharm 설치
* 다음 파일을 다운로드.
```
https://download-cf.jetbrains.com/python/pycharm-community-2017.1.4.dmg
```

### tensorflow 설치 (virtualenv)


* PIP
```
$ sudo easy_install pip
```

* Virtualenv
```
$ sudo pip install virtualenv
$ virtualenv --system-site-packages ~/tensorflow
```

* TensorFlow
```
$ source ~/tensorflow/bin/activate
$ pip install --upgrade tensorflow
```


* TensorFlow 테스트
```
$ python
Python 2.7.10 (default, Feb  7 2017, 00:08:15)
[GCC 4.2.1 Compatible Apple LLVM 8.0.0 (clang-800.0.34)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import tensorflow as tf

```
