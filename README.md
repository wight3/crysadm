# Crysadm+ 云端监控
![image](https://github.com/hauntek/crysadm/raw/master/static/img/preview.png)
添加DaoCloud支持

# 运行环境
建议 Python 3.4.2 及 Redis 2.8 以上

# 项目配置
1.安装项目依赖扩展
- 终端执行命令 `pip install redis, requests, flask`

2.配置项目启动参数
- 使用支持UTF-8编码编辑器修改 config.py 配置 redis server

crysadm.py 启动web服务
- 默认启动为单线程模式，如多并发请使用多线程模式启动
- 多线程模式启动命令: `./crysadm.py runserver --threaded`

crysadm_helper.py 启动后台服务

4.启动web服务后访问 /install 生成管理员账号
