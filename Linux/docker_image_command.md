
# image 相關指令

## image在 host的位置

```
/var/lib/docker/image/overlay2/imagedb/content
```

## 下載 (pull)

```
docker image pull image名稱:tag名稱
```

---

## 刪除 (rm)

```
docker image rm image名稱:tag名稱
```

---

## 查詢 (ls)
```
docker image ls
```

---

## 儲存 (save)
檔名通常為 **image名稱.tag名稱**.tgz
```
docker image save image名稱:tag名稱 | gzip > 檔名
```

---

## 讀取 (load)
檔名通常為 **image名稱.tag名稱**.tgz
```
docker image load < 檔名
```

---
