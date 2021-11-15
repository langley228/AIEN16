# linux 指令
## 查 ip
```
ip addr show
```

# 以下待整理
```
1. 選項(option)的目的: 改變指令的執行方式

2. 參數的目的: 要改變指令處理的對象

系統軟體安裝路徑 :

1) /bin, /sbin (開機時使用)
2) /usr/bin, /usr/sbin (系統正常運作用)

# 透過 apt install


使用者自行編譯軟體 :


/usr/local/bin, /usr/local/sbin
例如 OpenCV

暫存目錄 :
/proc, /run, /sys, /dev, /tmp

Linux沒有undelete的功能

bzip2 : 2013~ Linux kernel 不再提供 .tar.bz2 格式


tar -tvf
-t: list
-v: verbose，顯示詳細的操作過程
-f: 後面接檔名

tar -xvf
-x: extract

tar -cvf
-c: create
可以搭配壓縮軟體
-z: gzip
-j: bzip2
-J: xz



NAT: Network Address Translate


ping -c4 <internet FQDN>

FQDN: Fully Qualified Domain Name: 例如 www.facebook.com

1) IP是合法的
2) 確定Gatway 正確
3) Internet 有通
4) 名稱解析正確


node ＝＝ python3

npm ＝＝ pip3

node - v

npm -v
```

```
bash :

' : 不解釋特殊符號的意義

> /dev/null

> : 代表output redirection，本來要顯示在螢幕的資料，把它導到其他的地方
/dev/null : 代表空的裝置(黑洞)


yml(yaml) : Python語法的設定檔，習慣縮排是空兩格

yolo5

docker-ce : community edition


$(command) : 取得指令的執行結果



$(( expr )) : 取得算術運算的結果


curl -fsSL https://download.docker.com/linux/ubuntu/gpg | gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg


echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | tee /etc/apt/sources.list.d/docker.list > /dev/null


dockerd : d(daemon)代表服務


所有的container都會分享host的資源

```

```
Docker container不能執行systemd的服務
Docker container沒有圖形介面

Container必須要有一個process執行

[ctrl]+[p], [ctrl]+[q]: detach (暫時離開container)

docker 指令預設只有root可以執行

python官方的pip會安裝在/usr/local/bin

如果是安裝在/usr/bin，那就是ubuntu倉庫的pip(透過apt install python3-pip)



-p 8888:8888 ==> 格式 <host port>:<container port>

-d : detach服務式的container
```

