
# image 相關指令

## image在 host的位置

```
/var/lib/docker/image/overlay2/imagedb/content
```

## 下載 (pull)

```
docker image pull imge名稱:tag名稱
```

---

## 儲存 (save)
檔名通常為 **imge名稱.tag名稱**.tgz
```
docker image save imge名稱:tag名稱 | gzip > 檔名
```

---

## 讀取 (load)
檔名通常為 **imge名稱.tag名稱**.tgz
```
docker image load < 檔名
```

---

## 刪除 (rm)

```
docker image rm imge名稱:tag名稱
```

---