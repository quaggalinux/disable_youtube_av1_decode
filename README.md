# disable_youtube_av1_decode
强迫youtube不发送av1码流，只发送vp9码流 
  
最近油管搞小动作，自己判断用户的带宽，然后自行决定发送给用户是av1还是vp9码流，但是各位童鞋应该感受到av1解码的卡顿酸爽， 反正现在童鞋们都不缺带宽是吧，那有没有方法强迫油管只送vp9的码流过来呢？这个就要看各位童鞋使用的平台及操作系统了。  
  
首先是android盒子，手机，还有模拟器如bluestack，那这个就比较简单暴力了，下载https://github.com/yuliskov/SmartTubeNext/releases 的STubeNext_ststable_v13.47_r.apk稳定版就可以暴力选择vp9码流，这个apk兼容armv7，armv8，x86全平台。   
  
如果是windows或macOS或linux桌面版操作系统，下载https://www.mozilla.org/en-US/firefox/all/#product-desktop-release 的firefox， 
千万不要到第三方网站下载！！！千万不要到第三方网站下载！！！千万不要到第三方网站下载！！！安装好后，  
  
地址栏输入： about:config  
  
接受风险提示  
  
搜索栏输入： media.av1.enabled  
  
把 true 改成 false  
这时童鞋们上油管，就会发现所有的视频流都被强迫发送vp9的码流过来了。  
如果那天想换回av1解码，把media.av1.enabled项改回true就可以了。  
  
