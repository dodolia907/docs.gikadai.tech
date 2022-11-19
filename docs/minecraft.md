# Minecraft
## 概要
### Java
IP: minecraft.gikadai.tech  

### BE  
IP: minecraft.gikadai.tech  
Port: 19132  

### Dynmap
Lobby: mclobby.gikadai.tech  
Main: mcmaps.gikadai.tech  


## サーバー内でのルールについて
相手が嫌がる行為、迷惑行為はしない  
相手の所持品を盗まない  
許可なしに相手の建造物や著作物を改造&破壊しない  
Hack を使用しない  
荒さない(サーバー負荷、拠点あらしなど)  
  
これらに当てはまる場合、適切な措置を取る場合があります。  
  
## プラグイン・コマンド
### プラグインとは？
当サーバーではプラグインというものを使用して、Minecraftバニラにはない機能を追加しています。  
そこで、ここではプラグインの使用方法について説明します。  

#### 各種情報の表示  
/tps TPSを表示します。  
/tpsbar 画面上部に常時TPS, MSPT,PINGを表示します。  
/compass 画面上部に南北東西を常時表示します。  
  
TPS: Tick per second の略。1秒間に何Tick処理できているかを示します。20が最高値で、20より低くなればなるほどサーバーが"ラグい"状態になります  
MSPT: サーバーが1Tickを処理するのにかかる時間を示します。TPS 20を維持するためにはMSPTは50以下でなければなりません。  
PING: サーバーとの接続にかかった時間を示します。大きければ大きいほど遅延が大きいことを示します。  


#### チェストロック
チェストの中身の盗難対策を行いたいと思われる方もいるでしょう。その場合はチェストロックを行うことができます。  
/cprivate 自分以外の人が開けられないように設定します。  
/cpublic ほかの人も開けることができますが、壊すことができなくなります。  
/cdonation ほかの人が物を入れることはできますが取り出すことができなくなります。  
/cmodify [名前] 指定した人のチェストの中身の操作を許可します。[]を入力する必要はありません。  
/cpersist 連続で操作ができます。解除するにはもう一度/cpersistと入力します。  


#### トロッコの高速化
レッドストーンブロックの上にパワードレールを置くとエリトラと同じ速度の、通常の4倍の速度まで加速します。  
ただし、曲線区間で脱線しやすくなります。  

一括掘削プラグイン
任意のツールを持ち、スニークしながら(Shiftを押しながら)掘ると、一括掘削できます。  
無効にするには/vm toggle [無効にしたいツール]と入力します。  
また、クライアントにVeinMiner Mod(fabric)を導入すると、Shift以外のキー割り当てを利用することができます。  


#### ホームプラグイン
遠出をして、家に戻るのが大変面倒くさい。そう思うときがあるかもしれません。  
ホームプラグインを使用すれば、どんな場所でも数秒で家に帰ることができます。  
/sethome 現在位置をhomeに登録します。  
/home 登録地点にテレポートします。  


#### エレベータープラグイン
このプラグインを使用すれば、簡単にエレベーターを作成することができます。  