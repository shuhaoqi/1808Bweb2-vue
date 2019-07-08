##node 的基础知识
nodejs 后端语言 java/php 等价 单线程/异步，无阻塞 i/o

###node 的几个核心模块

1. http 模块 创建服务器
   新建文件 app.js
2. url 模块 解析 url
   3.path 模块 解析路径 path.join
   path.resolve
3. fs filesystem 文件处理 读写文件用

###node 的启动方式

1. vscode 插件 code runner
2. node + 文件名
3. 服务端代码有改动需要重启

### node 模块的使用 commonjs 规范

moulde.exports 表示导出模块
require 引入模块

搜索 window 常用的 linux 命令
touch 建立文件
mkdir 新建文件夹
cd 进入文件路径
window dir/mac ls 文件目录列表

--6.26 作业：

1. ?name=1&age=2&c=3 => {name:1,age:2,c:3}
   --2.[{"id": 1,"name": "苹果"},{"id": 2,"name": "西瓜"}]
   id 为 1 的这个选项 name 修改成"香蕉"

--6.27 作业
实现数组扁平化（两种方法）
[1,2[3,4[5,6[7,8]]]] =>[1,2,3,4,5,6,7,8]

7.1号作业
首页