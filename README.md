使用6000端口直连V2ray的方式已失效，因为只要杀死ssh进程GCS服务器就会关闭。目前只能使用putty或者plink搭建临时Socks5隧道来下载国外大文件

Goole Cloud Shell第三方SSH，自我唤醒

wget -O gcs_k.sh https://github.com/Lintao-Zeng/GoogleCloudShell/raw/refs/heads/main/gcs_k.sh && chmod +x gcs_k.sh && ./gcs_k.sh


Goole Cloud Shell第三方SSH，自我唤醒，BBR，6000端口直连V2Ray

wget -O gcs.sh https://github.com/Lintao-Zeng/GoogleCloudShell/raw/refs/heads/main/gcs.sh && chmod +x gcs.sh && ./gcs.sh
