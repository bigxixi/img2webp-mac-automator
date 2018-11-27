# 项目已合并到 
# https://github.com/bigxixi/img2webp-and-apng-mac-automator

————以下仅供存档——————  

# img2webp-mac-automator
Mac 下的序列帧转 webp 服务。  
使用了 Google [官方的转换程序](https://developers.google.com/speed/webp/docs/img2webp)，用 Automator 加了个壳。  

<img src="https://raw.githubusercontent.com/bigxixi/ReadMe-Resources/master/webp/shuoming.png" width="50%" />

# 安装  
下载[安装镜像](https://raw.githubusercontent.com/bigxixi/img2webp-mac-automator/master/%E5%AE%89%E8%A3%85%E5%8C%85/%E3%80%8C%E5%BA%8F%E5%88%97%E5%B8%A7%E8%BD%AC%20webp%20%E5%8A%A8%E7%94%BB%E3%80%8D%E6%9C%8D%E5%8A%A1%E5%AE%89%E8%A3%85v1.2.dmg)，根据提示安装。  
# 使用
将序列帧都放进一个文件夹（文件夹里不要有其他文件），对着文件夹右键 —— 服务 —— 序列帧转 webp，根据提示操作。
# 注意事项
 - 文件夹中不要有除了序列帧以外的文件。  
 - 每帧停留时长=1000*(1/fps),取整数，例如  
30帧每秒的动画，每帧停留1000*(1/30)约为33；  
25帧每秒的动画，每帧停留1000*(1/25)=50。  
 - ~~如果文件夹或者序列帧文件名中带有空格会被改名（以下划线替代）~~

