# 立ち上げ方法
```
docker build -t . erd
```

# 使用方法
ファイル名.erという形式のファイルを作成し、その中身に内容を記載。

その後、下記コマンドを実行し、その内容をpdfで書き出す
```
docker run -i erd < sample.er > sample.pdf
```

拡張子erのファイル名の記載方法については下記を参照。
https://github.com/BurntSushi/erd
