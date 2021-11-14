
# container 相關指令


## 啟動 (run) 
- 互動式輸入 (-it) 
- 背景執行 (-d)
- port對應 (-p hostPort:containerPort)
- container名稱 (--name container名稱)

```
docker container run -it -d -p hostPort:containerPort --name container名稱 image名稱:tag名稱
```

---

## 開側門 (exec) 
- 互動式輸入 (-it) 

```
docker container exec -it 啟動中的container名稱 /bin/bash
```

---

## 停止 (stop)

```
docker container stop container名稱
```

---

## 啟動 (start)

```
docker container start container名稱
```

---

## 刪除 (rm)

```
docker container rm container名稱
```

---

## 查詢啟動中 (ls)
```
docker container ls
```

## 查詢全部 (ls -a)
```
docker container ls -a
```

---

## 複製檔案到 container (cp)
```
docker container cp host路徑或檔名 container路徑或檔名
```

---
