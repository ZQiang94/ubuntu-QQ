# ubuntu-QQ
ubuntu15.10 install QQ
1.安装wine，可以通过Ubuntu软件中心搜索wine，安装

2.安装完成以后，下载wine-qqintl压缩包（这是国际版，ubuntu目前只能安装国际版QQ，而且是12年的版本）
  2.1下载地址 http://www.ubuntukylin.com/applications/showimg.php?lang=cn&id=23
  2.2为了防止以后数据包丢失，将压缩文件放在了github上
  
3.下载完以后，提取出来到指定位置。提取出来一共是三个文件
  fonts-wqy-microhei_0.2.0-beta-2_all.deb ttf-wqy-microhei_0.2.0-beta-2_all.deb wine-qqintl_0.1.3-2_i386.deb
  上面三个deb文件

4.命令行安装这三个文件
  sudo dpkg -i fonts-wqy-microhei_0.2.0-beta-2_all.deb ttf-wqy-microhei_0.2.0-beta-2_all.deb wine-qqintl_0.1.3-2_i386.deb 
  
5.如果安装过程出现问题，需要安装依赖
  sudo apt-get install -f

6.重复执行第四步

7.创建快捷方式
  7.1  安装完成的快捷键都在/usr/share/applications这个位置，进入这个目录找到相应快捷方式，然后右键复制到桌面就行了。
  
  
