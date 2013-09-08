Was ist YouTube
===============

Youtue 视频链接：  
http://www.youtube.com/watch?v=F22anVqciYI

首先，我们要可以查看一下可以下载的字幕列表：  
http://video.google.com/timedtext?type=list&tlangs=1&v=F22anVqciYI


搜索一下 cantran="true" 发现只有 Deutsch 和 English 是可以用来翻译的，换句话说，只有这两种是原始字幕。

原始字幕下载很简单，只要在上面的列表中找到 lang_code 就好了  
http://video.google.com/timedtext?lang=en&v=F22anVqciYI  
http://video.google.com/timedtext?lang=de&v=F22anVqciYI  
  
那字幕列表中其它语言的字幕怎么下载呢？很简单，指定原始语言和目标语言就可以了：  
http://video.google.com/timedtext?lang=en&tlang=zh-Hans&v=F22anVqciYI


但下载下来的字幕是 xml 格式的，不是我们平常所用的 srt 文件，那怎么办？ 网上有人已经做了各种工具。  
第一种是在线版的，直接用 chrome 或 Firefox 打开上面的字幕链接，再查看 xml 文件的源代码(Ctrl + U), 把源代码复制到[这个网页](http://greatdreamers.sinaapp.com/youtubesubs/raw.html)，点 make，那生成的 srt.txt 文件就会自动下载到本地了。  
第二种是 Java 版的：http://google2srt.sourceforge.net/en/ ，通过这个工具，你只需要把 Youtube 的链接粘进去就可以了。前面的手工找字幕的工作都可以省略了。  

如果你只是想把字幕 xml 文件中的文字提取出来，自己看看，可以用这个工具：http://www.nicertutor.com/xml.cgi

好了，我已经把德语字幕经第一种方式转换成srt格式了，文件名就叫Was_ist_YouTube.srt，大家可以先 Fork 本项目，翻译某些字幕后给我发 pull request，这样我们就可以一起把这个翻译工作快速做完了。
