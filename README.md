# Hoshino_WebManager_template
A template for Hoshino Services Web Manager

**本项目仅为模板，请配合插件(hoshino服务开关网页版 by 倚栏待月)使用**

**This project is only a template, please use it with plugins(hoshino服务开关网页版 by 倚栏待月)**

## 如何使用 How to use 

### 使用HTTPS且使用常规端口（443）反向代理 HTTPS and use reverse proxy with normal port(443)

1. 下载并根据版本重命名并替换文件 Download rename and replace files

2. 重启Hoshino Restart Hoshino

### 使用HTTPS但不使用常规端口（443）反向代理 HTTPS and use reverse proxy with unusual port(Not 443)

1. 下载文件 Download files

2. 在***所有***'{{ public_address }}'后添加':{{ port }}' Add ':{{ port }}' after ***ALL*** '{{ public_address }}' in files

   **SP: view.py中'{public_address}'后添加':{port}' Add ':{port}' after '{public_address}' in view.py**

3. 根据版本重命名并替换文件 Rename and Replace files

4. 重启Hoshino Restart Hoshino

### 使用HTTP但有反向代理 HTTP but use reverse proxy

1. 下载文件 Download files

2. 将***所有***'https'替换为'http' Replace ***ALL*** 'https' with 'http' in files

3. 删去'base.html'中注释所标记内容 Delete the content marked by the comment in 'base.html'

4. 根据版本重命名并替换文件 Rename and Replace files

5. 重启Hoshino Restart Hoshino

### 使用HTTP且没有反向代理或反向代理未使用标准端口（80） HTTP and no reverse proxy or use reverse proxy with unusual port(Not 80)

1. 下载文件 Download files

2. 根据***所有***文件的注释修改 Find ***ALL*** notes and follow the notes

3. 根据版本重命名并替换文件 Rename and Replace files

4. 重启Hoshino Restart Hoshino

### 懒人包

如果你没有对网页管理插件魔改，可以直接使用[release](https://github.com/shkongzhu/Hoshino_WebManager_template/releases)中文件进行替换

If you have not modified the web management plugin, you can directly use the file in the [release](https://github.com/shkongzhu/Hoshino_WebManager_template/releases) to replace it

#### 可能涉及的文件及行数 Possible file locations

| File Name | Line |
| :----: | :----: |
| view.py | 111 |
| base.html | 8 |
| by_group.html | 28 |
| by_service.html | 26 |
| group_services.html | 55 |
| service_groups.html | 95 |

## 展示 Display

![login](/img/login.png)
![group](/img/group.png)
![service](/img/service.png)
![group_services](/img/group_services.png)
![service_groups](/img/service_groups.png)
