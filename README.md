全局安装nodemon，因为每次更新stock_server.ts代码需要重启node，nodemon能够帮我们自动重启
gulp tsc:w 能用于编译 ts到build文件下
nodemon build/stock_server.js 用于启动服务