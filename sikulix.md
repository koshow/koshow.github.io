# SikuliXでJDKを切り替えて使う方法
SiluliXはJDK8以上で動作する。
しかし、使いたい環境に既に古いバージョンのJDKがインストールされていることがある。
その場合に新しいJDKを上書きしてしまうと古いソフトが動作しなくなることがある。
そのため、古いバージョンも維持したまま、SiluliX用に新しいJDKを設定する方法を紹介する。

## 手順

### sikuliXをダウンロードする

ここからダウンロードする。

https://raiman.github.io/SikuliX1/downloads.html


### JDKをインストーラを使わずにインストールする

http://jdk.java.net/

からJDKをダウンロードして、Zipを解凍する。解凍したフォルダを、Cドライブの直下などに移動させる。
JDKはOpenJDKで良い。Ver14は動作しない。Ver11だと動作した。

### sikulixのIDEを起動する

OpenJDKの場合、パスが通っていないので、コマンドラインから直接起動する（または、自分でパスを通す）。

`C:\Users>C:\java\jdk-11\bin\java.exe -jar C:\sikulix\sikulixide-2.0.4.jar`

これだけ
