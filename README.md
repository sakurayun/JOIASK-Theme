# JOIASK-Theme

您可以自定义前端文件存放位置

```bash
docker run -it -d --restart always \
    -p 1145:1145 \
    -v /path/to/config.json:/work/config/config.json \
    -v /path/to/public:/work/frontend/public \
    --name tio \
    ghcr.io/xinrea/joiask:latest
```    
将 /path/to 修改为你的 /config.json 及 /public/ 目录的存放位置

将前端文件目录改为 public

# 当前的几种样式
## 蓝白
![image](https://user-images.githubusercontent.com/30366696/186399125-d1f7c704-9563-4cdc-bb61-bb9763fe8cb2.png)

## 粉白
![image](https://user-images.githubusercontent.com/30366696/186399247-55d76d83-8413-4332-8f44-d7d2e3ea9811.png)

## 黑白
![image](https://user-images.githubusercontent.com/30366696/186399313-e53911dd-d0e9-4c46-8241-04ecd520c5dd.png)

## 不知道这是啥色（姑且是另一种粉白吧）
![image](https://user-images.githubusercontent.com/30366696/186399460-1785797b-d613-4233-af3e-65d95c63d41a.png)

## 绿白
![image](https://user-images.githubusercontent.com/30366696/186399561-3e420a5d-2624-45b9-8617-fff5e6b2e782.png)

## 另一种底纹的黑白
![image](https://user-images.githubusercontent.com/30366696/186399655-e34c9536-8583-4c42-941a-4305ca3767b4.png)

