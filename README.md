# LanzouAPI

## 说明
1. 支持检测文件是否被取消

2. 支持带密码的文件分享链接但不支持分享的文件夹

3. 支持生成直链或直接下载

4. 增加ios应用在线安装

5. 解析最终直链

## 使用方法

url:蓝奏云外链链接

type:是否直接下载 值：down

pwd:外链密码

### 直接下载：

无密码：/api.php?url=https://www.lanzous.com/i1aesgj&type=download

有密码：/api.php?url=https://www.lanzous.com/i19pnjc&type=download&pwd=1pud


### 输出直链：

无密码：/api.php?url=https://www.lanzous.com/i1aesgj

有密码：/api.php?url=https://www.lanzous.com/i19pnjc&pwd=1pud

