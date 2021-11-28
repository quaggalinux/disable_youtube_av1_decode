# disable_youtube_av1_decode
强迫youtube不发送av1码流，只发送vp9码流 
  
最近油管搞小动作，自己判断用户的带宽，然后自行决定发送给用户是av1还是vp9码流，但是各位童鞋应该感受到av1解码的卡顿酸爽， 反正现在童鞋们都不缺带宽是吧，那有没有方法强迫油管只送vp9的码流过来呢？这个就要看各位童鞋使用的平台及操作系统了。  
  
首先是android手机，可以到https://www.apkmirror.com 搜索包名“com.jio.yt”，在结果里面选择2.5.8版本下载apk，再传输到手机里面安装，它的界面跟操作与手机自带的油管客户端没有什么区别，因为它是印度运营商jio与谷歌协议定制的油管客户端，然后播放油管视频的时候app会自动强迫选择vp9码流

另外是android盒子，这个比较简单暴力，下载https://smartyoutubetv.github.io/ 的smarttube_stable.apk稳定版就可以暴力选择vp9码流。  
  
如果是windows或macOS或linux桌面版操作系统，下载https://www.mozilla.org/en-US/firefox/all/#product-desktop-release 的firefox， 
千万不要到第三方网站下载！！！千万不要到第三方网站下载！！！千万不要到第三方网站下载！！！安装好后，  
  
地址栏输入： about:config  
  
接受风险提示  
  
搜索栏输入： media.av1.enabled  
  
把 true 改成 false  
这时童鞋们上油管，就会发现所有的视频流都被强迫发送vp9的码流过来了。  
如果那天想换回av1解码，把media.av1.enabled项改回true就可以了。  
  
