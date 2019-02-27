
# fabric_image

下载地址 https://pan.baidu.com/s/1SgX1zlTO-ko0MyxTWhA6-w

IBM Hyperledger fabric的镜像
我知道你们都恨安装那一堆东西，npm,nodejs,还有无穷无尽的依赖们，所以我封了一个这个，拿去用吧
基于Playground,具体步骤请参考https://hyperledger.github.io/composer/latest/installing/installing-index

ubuntu-16.04.4,已安装playground
账号:fabric
密码：123456

加载到VMWare,
使用命令
    cd ~/fabric-tools
    ./startFabric.sh
    ./createPeerAdminCard.sh
然后
    composer-playground
就可以用你的本机浏览器进行访问了。
