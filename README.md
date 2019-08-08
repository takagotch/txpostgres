### txpostgres
---
https://github.com/wulczer/txpostgres

```py
conn = txpostgres.Connection(detector=DeadConnectionDetector())
d = conn.connect('dbnmae=test')
d.addErrback(conn.datector.checkForDeadConnection)


```

```sh
tar xjf txpostgres-x.x.x.xtar.bz2
cd txpostgres-x.x.x
trial test
sudo python setup.py install
pip intall txposgres
```

```
```


