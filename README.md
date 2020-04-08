## Install and Run

- 安装 gitbook

```shell
npm install gitbook-cli -g
```

- clone 代码至本地运行

```shell
git clone https://github.com/wswdavid/Gitbook_Demo.git
cd Gitbook_Demo
#npm install
#如果需要commit前进行markdownlint则执行这一条
gitbook install
gitbook serve
```

- **commit 前会执行 markdownlint 验证 md 文件的规范**
