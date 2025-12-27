使用6000端口直连V2ray的方式已失效，因为只要杀死ssh进程GCS服务器就会关闭。目前只能使用putty或者plink搭建临时Socks5隧道来下载国外大文件

google-cloud-sdk使用管理员身份安装后会生成新的安装目录(我的是在D:\Program Files\google-cloud-sdk)，原本的google-cloud-sdk只是相当于安装包，google-cloud-sdk下的bin目录需要添加到环境变量

google-cloud-sdk\bin\sdk下的putty需要替换成破解版的才能获取到ip地址，google-cloud-sdk安装完成后需要将puttySocks文件夹和plinkSocks文件夹复制到google-cloud-sdk\bin\sdk目录下

Goole Cloud Shell第三方SSH，自我唤醒

wget -O gcs_k.sh https://github.com/Lintao-Zeng/GoogleCloudShell/raw/refs/heads/main/gcs_k.sh && chmod +x gcs_k.sh && ./gcs_k.sh


Goole Cloud Shell第三方SSH，自我唤醒，BBR，6000端口直连V2Ray

wget -O gcs.sh https://github.com/Lintao-Zeng/GoogleCloudShell/raw/refs/heads/main/gcs.sh && chmod +x gcs.sh && ./gcs.sh
