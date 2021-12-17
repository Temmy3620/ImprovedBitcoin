## このサンプルコードが対象としているセクション　

2.4.3 Edgeノードを作る  
〜  
2.4.4 CoreノードとEdgeノードを接続してみる 


### Tested System:
* OSX 10.12.6
* python 3.8.10


### サーバー１の起動

```bash:
python sample_server1.py 50082 192.168.253.132
```

### サーバー２の起動

```bash:
python sample_server2.py 50090 192.168.253.132 50082 test
```

### クライアント（Edgeノード）の起動

```bash:
python wallet_masterApp.py 50098 192.168.253.132 50082
```

### クライアント（Edgeノード）の起動

```bash:
python wallet_Userapp.py 50093 192.168.253.132 50090
```