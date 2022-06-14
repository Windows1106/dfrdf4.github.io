##dfrdf4.github.io


### OPENSUSE leap 15.3 解码器安装方法

添加软件源
> zypper ar -cfp 90 https://mirrors.ustc.edu.cn/packman/suse/openSUSE_Leap_15.3 packman  
安装
sudo zypper refresh  
sudo zypper dist-upgrade --from packman --allow-vendor-change  
sudo zypper install --from packman ffmpeg gstreamer-plugins-{good,bad,ugly,libav} libavcodec-full   
