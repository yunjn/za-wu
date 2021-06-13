# 家校家教服务管理系统

## Introduction

数据库课设，三个晚自习写个 der，~~（装糊涂的高手）~~

* 数据库增删改查 -> SQL页面
* 数据库部分数据分析 -> 分析页面
* 表的自适应更新，添加 -> 侧边列表
* 数据库的账号密码登入
* 窗口抖动
* ~~较为美观的 GUI~~

## Development environment

* `VS Code` + `Miniconda` +  `Python3.7`

## Usage

### Installation and operation

```bash
pip install -r requirements.txt
python run.py
```

### Initialization

时间原因，数据库初始化未通过代码实现，**需创建名为TSM的数据库**并执行`sql`文件夹下的各个sql文件。

### Login

<img src=".\static\img\login.png" alt="login" style="zoom:80%;" />

输入数据库的用户名，密码点击登录即可。

### MainWindow

<img src=".\static\img\feng.png" alt="feng" style="zoom: 67%;" />

点击右侧相应按钮进行操作。

<img src=".\static\img\table.png" alt="table" style="zoom:67%;" />

* 数据修改后，分析页面 `右键 -> Reload` 重新载入。
* SQL 页面双击可以输入SQL语句。若与查询相关，相关结果会直接显示在SQL页面。

<img src=".\static\img\sql.png" alt="sql" style="zoom:67%;" />

## ~~TODO~~

* 数据库初始化
* 分析页面增加选项
* SQL页面查询样式
* 窗口抖动提醒运用到全局