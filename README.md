# Fusion Storage Proxy/Agent

混合存储代理

# 愿景

## 统一存储的服务接口（打✔的为优先考虑实现）

+ Local Disk / System ✔
+ HDFS ✔
+ WebDAV
+ FTP
+ FTP-SSL
+ SFTP
+ Windows Azure Blob Storage azure
+ ackblaze B2 Cloud Storage
+ Google Cloud Storage
+ Amazon S3及兼容服务（不分线上线下）✔
+ Swift (OpenStack Object Storage)
+ Rackspace Cloud Files
+ DRACOON
+ Dropbox
+ Google Drive
+ NFS
+ Microsoft OneDrive
+ Microsoft SharePoint
+ 私有存储系统 ✔

## 要实现的基础功能

+ 集成统一的用户验证、权限验证
+ 同时支持数据传输代理和原始直接传输
+ 支持数据去重（秒传）
+ 适配所有的断点续传（上传、下载）
+ ……


# 技术选型及架构

# 进度

# 部分功能参考

+ duck（橡皮鸭子）
+ rsync
