# webvideo-downloader

![](https://img.shields.io/badge/platform-win%20%7C%20linux%20%7C%20osx-brightgreen) ![](https://img.shields.io/badge/python-%3E=%203.5.0-orange)

ð è§é¢ä¸è½½å¨ï¼ç¨äºä¸è½½ç½ç«ä¸­å¯ä»¥å¨çº¿æ­æ¾çè§é¢ã

---

## ç®å½

- [æ¯æçç½ç«](#æ¯æçç½ç«)
- [åè½ç¹æ§](#åè½ç¹æ§)
- [å¿«éå¼å§](#å¿«éå¼å§)
  - [å®è£](#å®è£)
  - [è¿è¡](#è¿è¡)
- [æ´æ°æ¥å¿](#æ´æ°æ¥å¿)

## æ¯æçç½ç«

| ç«ç¹                                | URL                                                    | æ®éç»è´¨ | VIPä¸å± |
| ------------------------------------- | ------------------------------------------------------ | -------- | ------- |
| åå©åå©ï¼åP/å¤Pï¼                   | [https://www.bilibili.com/](https://www.bilibili.com/) | â        | â       |
| ç±å¥èº     | [https://www.iqiyi.com/](https://www.iqiyi.com/)                       | â        | â       |
| è¾è®¯è§é¢         | [https://v.qq.com/](https://v.qq.com/)                          | â        | â       |
| èæTV       | [https://www.mgtv.com/](https://www.mgtv.com/)                        | â        | â       |
| WeTV             | [https://wetv.vip/](https://wetv.vip/)                              | â        | â |
| ç±å¥èºå½éç«   | [https://www.iq.com/](https://www.iq.com/)                    | â        | â       |

æ­¤å¤ï¼å¯éç [CommonHlsDownloader](https://github.com/jaysonlong/webvideo-downloader/raw/master/violentmonkey/CommonHlsDownloader.user.js) èæ¬æ¯æç»å¤§é¨ååºäº HLS æµå¼è§é¢çç½ç«ï¼å¦ [LPLå®ç½](https://lpl.qq.com/) ç­ã

## åè½ç¹æ§

#### *ä¸è½½ç¹æ§*

- è·¨å¹³å°æ¯æï¼Windows/Linux/Macï¼
- å¤çº¿ç¨ä¸è½½ï¼åæä»¶åæ®µ/å¤æä»¶å¹¶è¡ï¼
- å­å¹ä¸è½½åéæï¼éæå­å¹çè§é¢éä½¿ç¨æ¯æå­å¹çæ­æ¾å¨æ­æ¾ï¼å¦ `PotPlayer`ï¼`VLC Player` ç­ï¼

#### *å³äº VIP*

æ¬é¡¹ç®æ¯æ**1080pèåç»è´¨ãVIPä¸äº«ãVIPç¹æ­ãä»è´¹è§é¢**çä¸è½½ï¼åææ¯ä½ æ¯VIP/ç¨äºå¸/ä»äºè´¹ã

> **What you can watch determined what you can download.**
>
> ä½ åªè½ä¸è½½ä½ æä½ çè´¦å·å¯ä»¥å¨çº¿è§ççè§é¢ï¼æ¬é¡¹ç®æ²¡æVIPç ´è§£åè½ã


## å¿«éå¼å§

### *å®è£*

##### ä¾èµç¨åº

æ¬é¡¹ç®åºäº[Python](https://www.python.org/)ã[FFmpeg](https://ffmpeg.org/) åæµè§å¨æ©å± [Violentmonkey](https://violentmonkey.github.io/)/[Tampermonkey](https://www.tampermonkey.net/) å¼åï¼

- [Python](https://www.python.org/) (3.5 æä»¥ä¸)
- [FFmpeg](https://ffmpeg.org/) (Windows ç³»ç»æ éå®è£ï¼å·²åç½®å°ä»åºä¸­)
- [Violentmonkey](https://violentmonkey.github.io/) /  [Tampermonkey](https://www.tampermonkey.net/) (äºéä¸)

##### è·åé¡¹ç®

ç´æ¥ä¸è½½åç¼©åï¼æä½¿ç¨ git cloneï¼

```
git clone https://github.com/jaysonlong/webvideo-downloader.git
```

##### å®è£é¡¹ç®

æµè§å¨å®è£ä»¥ä¸åºäº Violentmonkey/Tampermonkey çèæ¬ãç´æ¥ç¹å»ä»¥ä¸é¾æ¥å³å¯å®è£ï¼

- [WebVideoDownloader èæ¬](https://github.com/jaysonlong/webvideo-downloader/raw/master/violentmonkey/WebVideoDownloader.user.js)

- [CommonHlsDownloader èæ¬](https://github.com/jaysonlong/webvideo-downloader/raw/master/violentmonkey/CommonHlsDownloader.user.js)ï¼å¯éãéç¨ HLS ä¸è½½èæ¬ï¼ä½ç¨äº**ææ**ä½¿ç¨ HLS çç½ç«ï¼

å®è£ python ä¾èµåï¼

```
cd webvideo-downloader/downloader
pip install -r requirements.txt
```

ï¼å¯éï¼æµè§å¨å®è£å¹¿åæ¦æªå¨ï¼
- [AdGuard å¹¿åæ¦æªå¨](https://adguard.com/)

> å¯¹äºæäºç½ç«ï¼è§é¢å­å¨å¹¿åæ¶ï¼æµè§å¨æä»¶èæ¬ä¼å»¶è¿å°å¹¿åå³å°ç»ææ¶æè½æåå°è§é¢é¾æ¥ï¼å®è£æ¦æªå¨å¯ä¸ç¨ç­å¾å¹¿åæ­æ¾å®æ¯

### *è¿è¡*

> æ¬é¡¹ç®åä¸ºä¸¤é¨åï¼**Violentmonkey** ç®å½ä¸ç javascript èæ¬ç¨äºå¨æµè§å¨ä¸­æåè§é¢é¾æ¥ï¼**Downloader** ç®å½ä¸ç python èæ¬ç¨äºä¸è½½ãåå¹¶è§é¢ã

é¦åæ§è¡ python èæ¬ï¼

```
python daemon.py
```

ç¶åè®¿é®è§é¢ç½ç«å¹¶ç¹å»æä¸ªè§é¢ï¼ç½é¡µä¼èªå¨å¼¹åºä¸è½½æé®ï¼ç¹å»æé®å³å¯ä¸è½½ã

ç¤ºä¾é¾æ¥ï¼https://www.bilibili.com/video/BV1c741157Wb

![bilibili](img/bilibili.gif)

ä¸è½½è¿åº¦å¯å¨ python èæ¬çå½ä»¤çªå£æ¥çï¼

```
$ python daemon.py
Listening on port 18888 for clients...

Receive: {
    "fileName": "çå°é»ä¹¦ä¼è¢«å¤ç½å",
    "linksurl": "http://xxx",
    "type": "link"
}

Handle: "çå°é»ä¹¦ä¼è¢«å¤ç½å"

å¹éå°1æ®µé³é¢ï¼1æ®µè§é¢ï¼å¼å§ä¸è½½
-- dispatcher/downloadDash
æ­£å¨ä¸è½½ E:\Workspace\Github\webvideo-downloader\temp\çå°é»ä¹¦ä¼è¢«å¤ç½å.audio.m4s
å8æ®µ, å¹¶è¡8çº¿ç¨ä¸è½½
è¿åº¦: [########################################] 100%    0.9/0.9MB  450KB/s 0s
æ­£å¨ä¸è½½ E:\Workspace\Github\webvideo-downloader\temp\çå°é»ä¹¦ä¼è¢«å¤ç½å.video.m4s
å8æ®µ, å¹¶è¡8çº¿ç¨ä¸è½½
è¿åº¦: [########################################] 100%  11.2/11.2MB  5.2MB/s 2s
æ­£å¨åå¹¶è§é¢
Finish.
```

> ä¸è½½ç®å½é»è®¤ä¸ºé¡¹ç®æ ¹ç®å½ä¸ç videos æä»¶å¤¹ï¼å¯å¨ downloader/config.py ä¸­éç½®ã

python èæ¬å¯éå½ä»¤è¡åæ°ï¼

```
$ python daemon.py -h
usage: daemon.py [-h] [-t:h N] [-t:f N] [-f N] [-p PORT] [-c] [-s] [-d] [-i]

optional arguments:
  -h, --help     show this help message and exit
  -t:h N         the thread count of hls download, default 8
  -t:f N         the thread count of fragments download, default 8
  -f N           the fragments count of each file, default 0 using the thread count
  -p PORT        the port that the backend server listens on, default 18888
  -c, --correct  correct the timestamp of hls video, merge fragments using binnary mode
  -s             if set, will save the temp files
  -d             debug mode, log more info and save the temp files (ignore -s)
  -i             interactive mode, get url and file name from the command line
```



## æ´æ°æ¥å¿

### [v2.0] - 2020-11-09

#### æ°å¢

- æ¯æè¾è®¯è§é¢é¿åæ®µä¸è½½ï¼ç±ç¨æ·ä¸ä¼ çè§é¢ï¼
- æ¯æç±å¥èºå½éç« VIP ä¸è½½ãWeTV æ å­å¹ä¸è½½
- å¢å  debug æ¨¡å¼

#### åæ´

- åå¹¶å®æ¤æ¨¡å¼åäº¤äºæ¨¡å¼ä¸ºä¸ä¸ª python èæ¬
- å¨ç±å¥èºå½éç«ï¼iq.comï¼ä¸­ç¦ç¨ WebAssembly æ©å±ï¼é²æ­¢å­å¹å å¯

### [v1.6] - 2020-09-12

#### æ°å¢

- æ¯æç±å¥èºå½éç«è§é¢ä¸è½½
- æ¯æå¤ä¸ªå­å¹æä»¶éæå°è§é¢ä¸­

### [v1.5] - 2020-09-01

#### æ°å¢

- æ¯æ WeTVï¼æå¥èå°ç£ç«è§é¢ä¸è½½
- æ¯æé¨åç½ç«å­å¹æä»¶éæå°è§é¢ä¸­
- ä¸è½½æä»¶å®æ´æ§æ£æ¥

#### åæ´

- MP4 æä»¶ moov box åç½®ï¼ä¾¿äºç½ç»ä¼ è¾

### [v1.4] - 2020-06-30

#### åæ´

- å®æ¤æ¨¡å¼è¿è¡æ¶ç«¯å£å¤ç¨ï¼å¶çå¬æ¨¡å¼åæ¶æ¯æ HTTP Server å WebSocket
- æ´åç´èæ¬å¯èªå®ä¹è¿ç¨è°ç¨æ¨¡å¼ï¼HTTP æ WebSocketï¼

### [v1.3] - 2020-06-27

#### åæ´

- æ´åç´èæ¬éæ & çé¢éå

### [v1.2] - 2020-06-18

#### æ°å¢

- æ¯æç±å¥èº MPD æ ¼å¼æä»¶è§£æ
- æ¯æ MSE è§é¢æµéè¿ WebSocketå¯¼åºï¼å®éªæ§ï¼
- æ°å¢ä¸¤ä¸ªæ´åç´èæ¬ï¼éç¨ hls ä¸è½½èæ¬å MSE è§é¢æµå¯¼åºèæ¬ï¼å®éªæ§ï¼
- å½ä»¤è¡åæ°æ¯æ

#### åæ´

- å®æ¤æ¨¡å¼è¿è¡æ¶ççå¬æ¨¡å¼ç± HTTP Server æ´æ¹ä¸º WebSocket 
- åå©åå©å¤Pä¸è½½èæ¬åå¹¶å°éç¨ä¸è½½èæ¬ä¸­

### [v1.1] - 2020-05-29

#### æ°å¢

- æ¯æåºäº HTTP Server ä»¥å®æ¤æ¨¡å¼è¿è¡ï¼æµè§å¨ç¹å»é¾æ¥ç´æ¥è°ç¨åå°ä¸è½½

#### åæ´

- åå¹¶4ä¸ªç½ç«èæ¬ä¸ºåä¸ªï¼ä¾¿äºå®è£åç®¡ç

### [v1.0] - 2020-05-26

#### æ°å¢

- æ¯æåå©åå©ãç±å¥èºãè¾è®¯è§é¢ãèæTVè§é¢ä¸è½½ï¼æå¨å¤å¶é¾æ¥ç²è´´ï¼
  
[v2.0]: https://github.com/jaysonlong/webvideo-downloader/compare/v1.6...v2.0
[v1.6]: https://github.com/jaysonlong/webvideo-downloader/compare/v1.5...v1.6
[v1.5]: https://github.com/jaysonlong/webvideo-downloader/compare/v1.4...v1.5
[v1.4]: https://github.com/jaysonlong/webvideo-downloader/compare/v1.3...v1.4
[v1.3]: https://github.com/jaysonlong/webvideo-downloader/compare/v1.2...v1.3
[v1.2]: https://github.com/jaysonlong/webvideo-downloader/compare/v1.1...v1.2
[v1.1]: https://github.com/jaysonlong/webvideo-downloader/compare/v1.0...v1.1
[v1.0]: https://github.com/jaysonlong/webvideo-downloader/releases/tag/v1.0
