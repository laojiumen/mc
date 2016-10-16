# mc
minecraft

## 服务器端

server地址: https://s3.amazonaws.com/Minecraft.Download/versions/1.9.4/minecraft_server.1.9.4.jar

其中版本号自行修改

启动指令：
```
java -Xmx1024M -Xms512M -jar minecraft_server.jar nogui
```

配置`vim server.properties`：

```
    generator-settings=
    op-permission-level=4                //设置管理员权限级别
    allow-nether=true
    resource-pack-hash=
    level-name=world
    enable-query=false
    allow-flight=false
    announce-player-achievements=true
    server-port=25565                    //设置服务器端口
    max-world-size=29999984
    level-type=DEFAULT
    enable-rcon=false
    level-seed=
    force-gamemode=false
    server-ip=                            //设置服务器ip，必须与本机公网ip相同
    network-compression-threshold=256
    max-build-height=256
    spawn-npcs=true
    white-list=false                    //是否使用白名单
    spawn-animals=true
    hardcore=false                        //是否为极限模式
    snooper-enabled=true
    online-mode=true                    //必须设置为false
    resource-pack=
    pvp=true                            //是否有玩家攻击伤害
    difficulty=1                        //难度 0:和平 1:简单 2:普通 3:困难
    enable-command-block=false            //是否允许命令方块
    gamemode=1                            //模式 0:生存模式 1:创造模式
    player-idle-timeout=0
    max-players=20
    max-tick-time=60000
    spawn-monsters=false   //!!!!!!局域网一定要弄成false
    generate-structures=true
    view-distance=10
    motd=A Minecraft Server                //服务器名称
```

## 客户端版

地址： https://github.com/mclauncher/HMCL/releases 自行下载对应版本

客户端下载后，下载游戏版本要与服务器版本一致。


## 后续看找几个其他专业服务器上去玩玩-。-

