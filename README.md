
#### tars  核心基础服务
解决了官方docker端口不一致


运行需要设置环境变量
            DBIP: 192.168.0.162
            DBPort: 3306
            DBUser: root
            DBPassword: password
            MOUNT_DATA: "true"


####  tarsnode  node 服务
 需要设置环境变量: 
   TarsRegistryIp: 192.168.0.162   #指向 tarsregistry 地址  默认端口17890
    # TarsRegistryPort: 17890  #端口暂时没用到 ,尽量不要使用默认的，万一有漏洞，可能被扫描攻击
    MOUNT_DATA: "true"