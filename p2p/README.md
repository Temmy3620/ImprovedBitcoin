## このサンプルコードが対象としているセクション　

第５章　すべての機能を結合し動かしてみよう


### Tested System:
* OSX 10.12.6
* python 3.8.10


### サーバー１の起動

```bash:
python sample_server1.py 50082 192.168.253.132
```

### サーバー２の起動

```bash:
python sample_server2.py 50090 192.168.253.132 test
```

### WalletAの起動

```bash:
python wallet_app.py 50098 192.168.253.132 50082
```


### WalletBの起動

```bash:
python wallet_app.py 50093 192.168.253.132 50090
```
