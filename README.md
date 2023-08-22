# contactPutianHospital

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fehnait%2FcontactPutianHospital&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

## 说明

- 此项目借鉴[callPhoneBoom](https://github.com/olyble/callPhoneBoom)
  ，使用[DrissionPage](http://g1879.gitee.io/drissionpagedocs/)简化浏览器操作流程并对边界情况进行了处理。
- 重写catch.py脚本，获取api更丝滑了，[api列表更新](api.txt)

## 思路

通过在百度上爬取「莆田系医院」这一营销组件的企业的网址, 然后通过成模拟浏览将目标手机号发送给企业，让这些企业给目标联系人打电话。

## Feature

主动帮助坏蛋蛋联系 **莆田系医院** 并留下电话号码。此举深藏功与名，每联系一次都会使你 **功德+1**

1. **main.py**：通过程序模拟浏览莆田系医院网址，自动发送目标手机号给企业 。
2. **scheduler.py**:设置定时任务
3. **catch.py**:批量爬取莆田系医院网址

## 使用教程

1. 克隆或下载你的代码到本地。
2. 创建一个新的虚拟环境（可选）。
3. 在终端或命令提示符下进入项目目录，并激活虚拟环境（如果有）。
4. 运行以下命令来安装依赖项：
   ```
   pip install -r requirements.txt
   ```
5. 查看 **main.py**的注释， 确保配置正确 ，运行 **main.py**

## 免责声明

1. 若使用者滥用本项目,本人 **无需承担** 任何法律责任.
2. 本程序仅供娱乐,源码全部开源,**禁止滥用** 和二次 **贩卖盈利**.  **禁止用于商业用途**.

## 运行截图

![](imgs/img1.png)