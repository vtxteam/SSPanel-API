# SSPanel-API

## 使用方法
### 打Patch
1、项目使用git管理，在根目录下，执行 `git apply xxx.patch`  
2、项目未使用git管理，在根目录下，执行 `patch -p1 < xxx.patch`

### 还原Patch
1、项目使用git管理，在根目录下，执行 `git apply -R xxx.patch`  
2、项目未使用git管理，在根目录下，重新执行 `patch -p1 < xxx.patch`

> xxx.patch 参考文件具体命名，如： **malio.202307240234.patch**
