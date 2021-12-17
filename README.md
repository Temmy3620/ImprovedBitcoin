## SampleCode改良した

samplebitcoin改良版


### Tested System:
* OSX 10.12.6
* python 3.8.10


### サーバー１の起動

```bash:
python sample_server1.py 50082 xxx.xxx.xxx.xxx
```

### サーバー２の起動

```bash:
python sample_server2.py 50090 xxx.xxx.xxx.xxx 50082 test
```

### クライアント（Edgeノード）の起動

```bash:
python wallet_masterApp.py 50098 xxx.xxx.xxx.xxx 50082
```

### クライアント（Edgeノード）の起動

```bash:
python wallet_Userapp.py 50093 xxx.xxx.xxx.xxx 50090
```
