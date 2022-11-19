# VPS
## 提供について
仮想マシンまたはLinuxコンテナで提供しています。仮想マシンかLinuxコンテナかは選択可能です。OSも好きなものを指定することが可能です。
一度管理者に連絡してください。

## スペック
サーバーは豊橋8号または豊橋9号での提供となります。

豊橋8号 NEC Express5800/R110f-1E
CPU: 第4世代 Intel Xeon E3-1220v3 4コア4スレッド
GPU: Matrox Electronics MGA G200e
メモリ: 16GB (DDR3 ECC/Unbuffered 4GB x4)

豊橋9号 Hitachi HA8000/RS220-h
CPU: 第3世代 Intel Xeon E5-2630v2 6コア12スレッド 2ソケット 合計12コア24スレッド
GPU: Matrox Electronics MGA G200e
メモリ: 72GB (DDR3 ECC/Registered 4GB x2 + 16GB x4)

## SSH接続
SSHにはCloudflaredを利用します。  

以下よりインストールしてください。  
https://github.com/cloudflare/cloudflared/releases  
  
.ssh内のconfigファイルに以下のように記述してください。  
  
``` ~/.ssh/config
Host hogehoge (任意の名前)  
HostName ssh.hogehoge.com (指定されたホスト名)  
ProxyCommand cloudflared access ssh --hostname %h  
User hogehoge (指定されたユーザー名)  
```