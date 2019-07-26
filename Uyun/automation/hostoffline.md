# Q:host offline

# A:缓存的key过期了，需要手动删除
## Linux
1. 停止本地操作模块
2. 去机器上的agent/modules/local-automation目录下，删除var/pki下所有文件
3. 在所属操作网关机器上执行如下命令
    - cd /opt/uyun-ant/agent/modules/remote-automation
    - ./auto delete-key 'x.x.x.x'
4. 启动本地操作模块

## Windows
1. 停止本地操作模块
2. 去机器上的agent/modules/local-automation目录下，删除var/pki下所有文件
3. 在所属操作网关机器上执行如下命令
    - cd /opt/uyun-ant/agent/modules/remote-automation
    - ./auto delete-key 'x.x.x.x'
4. 启动本地操作模块