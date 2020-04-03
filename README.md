# iptv
做个自己用的直播源，有时间就更新一下。

想做个【目录】→【分目录】，比如：index.m3u 中，代码：

#EXTM3U

#EXTINF:-1,央视频道

channels/cctv.m3u

cctv.m3u的代码：

#EXTM3U

#EXTINF:-1,CCTV1高清

http://www.ww.com/ww/index.m3u8

结果下载index.m3u后，还是源代码，不能引用cctv.m3u，怎么做啊。

To watch IPTV you just need to paste this link https://gijy.github.io/iptv/index.m3u to any player with support M3U-playlists.
