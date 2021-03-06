## ð Vulmap - Web vulnerability scanning and verification tools
<a href="https://github.com/zhzyker/vulmap"><img alt="Release" src="https://img.shields.io/badge/python-3.8+-blueviolet"></a>
<a href="https://github.com/zhzyker/vulmap"><img alt="Release" src="https://img.shields.io/badge/Version-vulmap 0.8-yellow"></a>
<a href="https://github.com/zhzyker/vulmap"><img alt="Release" src="https://img.shields.io/badge/LICENSE-GPL-ff69b4"></a>
![GitHub Repo stars](https://img.shields.io/github/stars/zhzyker/vulmap?color=gree)
![GitHub forks](https://img.shields.io/github/forks/zhzyker/vulmap)

 
[[Click here for the English Version]](https://github.com/zhzyker/vulmap/blob/main/readme.us-en.md)  
> Vulmap æ¯ä¸æ¬¾ web æ¼æ´æ«æåéªè¯å·¥å·, å¯å¯¹ webapps è¿è¡æ¼æ´æ«æ, å¹¶ä¸å·å¤æ¼æ´å©ç¨åè½, ç®åæ¯æç webapps åæ¬ activemq, flink, shiro, solr, struts2, tomcat, unomi, drupal, elasticsearch, fastjson, jenkins, nexus, weblogic, jboss, spring, thinkphp

> Vulmap å°æ¼æ´æ«æä¸éªè¯ï¼æ¼æ´å©ç¨ï¼ç»åå°äºä¸èµ·, åå¤§ç¨åº¦ä¾¿äºæµè¯äººåå¨åç°æ¼æ´ååæ¶è¿è¡ä¸ä¸æ­¥æä½, å·¥å·è¿½æ±äºäºé«æãä¾¿æ·  
é«æ: éæ­¥å¼åä¸­æ¢æ¢å¼å¥äºæ¹éæ«æãFofaãShodan æ¹éæ«æ, ä¸æ¯æå¤çº¿ç¨é»è®¤å¼å¯åç¨, ä»¥æå¿«çéåº¦æ«æå¤§éèµäº§  
ä¾¿æ·: åç°æ¼æ´å³å¯å©ç¨, å¤§éèµäº§æ«æå¯å¤æ ¼å¼è¾åºç»æ

> Vulmap 0.8 çæ¬å¼å§æ¯æå¯¹ [dismap](https://github.com/zhzyker/dismap) è¯å«ç»ææä»¶ç´æ¥è¿è¡æ¼æ´æ«æ `-f output.txt`


## ð Installation
æä½ç³»ç»ä¸­å¿é¡»æ python3, æ¨è python3.8 æèæ´é«çæ¬
```bash
# git æåå¾ release è·ååç 
git clone https://github.com/zhzyker/vulmap.git
# å®è£æéç python ä¾èµ
pip3 install -r requirements.txt
# Linux & MacOS & Windows
python3 vulmap.py -u http://example.com
```
éç½® Fofa Api && Shodan Api && Ceye  

ä½¿ç¨ Fofa or Shodan éè¦ä¿®æ¹ vulmap.py ä¸­çéç½®ä¿¡æ¯ï¼  

* Fofa info: https://fofa.so/user/users/info  
```bash
# æxxxxxxxxxxæ¿æ¢æfofaçé®ç®±
globals.set_value("fofa_email", "xxxxxxxxxx")  
# æxxxxxxxxxxæ¿æ¢æfofaçkey
globals.set_value("fofa_key", "xxxxxxxxxx")  
```
* Shodan key: https://account.shodan.io  
```bash
# æxxxxxxxxxxæ¿æ¢æèªå·±shodançkey
globals.set_value("shodan_key", "xxxxxxxxxx")  
```
* Ceye info: http://ceye.io  
```bash
# æxxxxxxxxxxæ¿æ¢ä¸ºèªå·±çåå
globals.set_value("ceye_domain","xxxxxxxxxx")  
# æxxxxxxxxxxæ¿æ¢èªå·±ceyeçtoken
globals.set_value("ceye_token", "xxxxxxxxxx")  
```

## ð Licenses
å¨åæåè®®[LICENSE](https://github.com/zhzyker/vulmap/blob/main/LICENSE)ä¸­è¿½å ä»¥ä¸åè´£å£°æãè¥ä¸åæåè®®å²çªåä»¥åè´£å£°æä¸ºåã  

æ¬å·¥å·ç¦æ­¢è¿è¡æªææåä¸ç¨éï¼ç¦æ­¢äºæ¬¡å¼ååè¿è¡æªææåä¸ç¨éã  

æ¬å·¥å·ä»é¢ååæ³ææçä¼ä¸å®å¨å»ºè®¾è¡ä¸ºï¼å¨ä½¿ç¨æ¬å·¥å·è¿è¡æ£æµæ¶ï¼æ¨åºç¡®ä¿è¯¥è¡ä¸ºç¬¦åå½å°çæ³å¾æ³è§ï¼å¹¶ä¸å·²ç»åå¾äºè¶³å¤çææã  

å¦æ¨å¨ä½¿ç¨æ¬å·¥å·çè¿ç¨ä¸­å­å¨ä»»ä½éæ³è¡ä¸ºï¼æ¨éèªè¡æ¿æç¸åºåæï¼æä»¬å°ä¸æ¿æä»»ä½æ³å¾åè¿å¸¦è´£ä»»ã 

å¨ä½¿ç¨æ¬å·¥å·åï¼è¯·æ¨å¡å¿å®¡æéè¯»ãååçè§£åæ¡æ¬¾åå®¹ï¼éå¶ãåè´£æ¡æ¬¾æèå¶ä»æ¶åæ¨éå¤§æççæ¡æ¬¾å¯è½ä¼ä»¥å ç²ãå ä¸åçº¿ç­å½¢å¼æç¤ºæ¨éç¹æ³¨æã é¤éæ¨å·²ååéè¯»ãå®å¨çè§£å¹¶æ¥åæ¬åè®®æææ¡æ¬¾ï¼å¦åï¼è¯·æ¨ä¸è¦ä½¿ç¨æ¬å·¥å·ãæ¨çä½¿ç¨è¡ä¸ºæèæ¨ä»¥å¶ä»ä»»ä½æç¤ºæèé»ç¤ºæ¹å¼è¡¨ç¤ºæ¥åæ¬åè®®çï¼å³è§ä¸ºæ¨å·²éè¯»å¹¶åææ¬åè®®ççº¦æã  


## ðº Video demo
> YouTube:  https://www.youtube.com/watch?v=g4czwS1Snc4  
> Bilibili: https://www.bilibili.com/video/BV1Fy4y1v7rd  
> Gif: ![https://github.com/zhzyker/vulmap/blob/main/images/vulmap-0.5-demo-gif.gif](https://github.com/zhzyker/vulmap/blob/main/images/vulmap-0.5-demo-gif.gif)


## ð Discussion
* Vulmap Bug åé¦ææ°åè½å»ºè®®[ç¹æ](https://github.com/zhzyker/vulmap/issues)
* Twitter: https://twitter.com/zhzyker
* WeChat: ~~æ«ç å¥ç¾¤è~~ï¼ç¾¤èæ»¡200äºï¼æ«ç åå ç¾¤äº    
<p>
    <img alt="QR-code" src="https://github.com/zhzyker/zhzyker/blob/main/my-wechat.jpg" width="20%" height="20%" style="max-width:100%;">
</p>

## ð§ Options
``` 
å¯éåæ°:
  -h, --help            æ¾ç¤ºæ­¤å¸®å©æ¶æ¯å¹¶éåº
  -u URL, --url URL     ç®æ  URL (e.g. -u "http://example.com")
  -f FILE, --file FILE  éæ©ä¸ä¸ªç®æ åè¡¨æä»¶,æ¯ä¸ªurlå¿é¡»ç¨è¡æ¥åºå (e.g. -f "/home/user/list.txt")
  --fofa keyword        ä½¿ç¨ fofa api æ¹éæ«æ (e.g. --fofa "app=Apache-Shiro")
  --shodan keyword      ä½¿ç¨ shodan api æ¹éæ«æ (e.g. --shodan "Shiro")
  -m MODE, --mode MODE  æ¨¡å¼æ¯æ"poc"å"exp",å¯ä»¥çç¥æ­¤éé¡¹,é»è®¤è¿å¥"poc"æ¨¡å¼
  -a APP [APP ...]      æå® webappsï¼e.g. "weblogic"ï¼ä¸æå®åèªå¨æçº¹è¯å«
  -c CMD, --cmd CMD     èªå®ä¹è¿ç¨å½ä»¤æ§è¡æ§è¡çå½ä»¤,é»è®¤æ¯echoéæºmd5
  -v VULN, --vuln VULN  å©ç¨æ¼æ´,éè¦æå®æ¼æ´ç¼å· (e.g. -v "CVE-2019-2729")
  -t NUM, --thread NUM  æ«æçº¿ç¨æ°é,é»è®¤10çº¿ç¨
  --dnslog server       dnslog æå¡å¨ (hyuga,dnslog,ceye) é»è®¤èªå¨è½®è¯¢
  --output-text file    æ«æç»æè¾åºå° txt æä»¶ (e.g. "result.txt")
  --output-json file    æ«æç»æè¾åºå° json æä»¶ (e.g. "result.json")
  --proxy-socks SOCKS   ä½¿ç¨ socks ä»£ç (e.g. --proxy-socks 127.0.0.1:1080)
  --proxy-http HTTP     ä½¿ç¨ http ä»£ç (e.g. --proxy-http 127.0.0.1:8080)
  --user-agent UA       åè®¸èªå®ä¹ User-Agent
  --fofa-size SIZE      fofa api è°ç¨èµäº§æ°éï¼é»è®¤100ï¼å¯ç¨(1-10000)
  --delay DELAY         å»¶æ¶æ¶é´,æ¯éå¤ä¹åéä¸æ¬¡,é»è®¤ 0s
  --timeout TIMEOUT     è¶æ¶æ¶é´,é»è®¤ 5s
  --list                æ¾ç¤ºæ¯æçæ¼æ´åè¡¨
  --debug               exp æ¨¡å¼æ¾ç¤º request å responses, poc æ¨¡å¼æ¾ç¤ºæ«ææ¼æ´åè¡¨
  --check               ç®æ å­æ´»æ£æµ (on and off), é»è®¤æ¯ on
```

## ð¾ Examples
```bash
# æµè¯æææ¼æ´ poc ä¸æå® -a all å°é»è®¤å¼å¯æçº¹è¯å«
python3 vulmap.py -u http://example.com

# æ£æ¥ç«ç¹æ¯å¦å­å¨ struts2 æ¼æ´
python3 vulmap.py -u http://example.com -a struts2

# å¯¹ http://example.com:7001 è¿è¡ WebLogic ç CVE-2019-2729 æ¼æ´å©ç¨
python3 vulmap.py -u http://example.com:7001 -v CVE-2019-2729
python3 vulmap.py -u http://example.com:7001 -m exp -v CVE-2019-2729

# æ¹éæ«æ list.txt ä¸­ç url
python3 vulmap.py -f list.txt

# æ«æç»æå¯¼åºå° result.json
python3 vulmap.py -u http://example.com:7001 --output-json result.json

# è°ç¨ fofa api æ¹éæ«æ
python3 vulmap.py --fofa app=Apache-Shiro
```

## ðµ Vulnerabilitys List
<details>
<summary>æ¯æçæ¼æ´åè¡¨ [ç¹å»å±å¼] </summary>  
 
```
 +-------------------+------------------+-----+-----+-------------------------------------------------------------+
 | Target type       | Vuln Name        | Poc | Exp | Impact Version && Vulnerability description                 |
 +-------------------+------------------+-----+-----+-------------------------------------------------------------+
 | Apache ActiveMQ   | CVE-2015-5254    |  Y  |  N  | < 5.13.0, deserialization remote code execution             |
 | Apache ActiveMQ   | CVE-2016-3088    |  Y  |  Y  | < 5.14.0, http put&move upload webshell                     |
 | Apache Druid      | CVE-2021-25646   |  Y  |  Y  | < 0.20.1, apache druid console remote code execution        |
 | Apache Flink      | CVE-2020-17518   |  Y  |  N  | < 1.11.3 or < 1.12.0, upload path traversal                 |
 | Apache Flink      | CVE-2020-17519   |  Y  |  Y  | 1.5.1 - 1.11.2, 'jobmanager/logs' path traversal            |
 | Apache OFBiz      | CVE-2021-26295   |  Y  |  N  | < 17.12.06, rmi deserializes arbitrary code execution       |
 | Apache OFBiz      | CVE-2021-29200   |  Y  |  N  | < 17.12.07, rmi deserializes arbitrary code execution       |
 | Apache OFBiz      | CVE-2021-30128   |  Y  |  Y  | < 17.12.07, deserialize remote command execution            | 
 | Apache Shiro      | CVE-2016-4437    |  Y  |  Y  | <= 1.2.4, shiro-550, rememberme deserialization rce         |
 | Apache Solr       | CVE-2017-12629   |  Y  |  Y  | < 7.1.0, runexecutablelistener rce & xxe, only rce is here  |
 | Apache Solr       | CVE-2019-0193    |  Y  |  N  | < 8.2.0, dataimporthandler module remote code execution     |
 | Apache Solr       | CVE-2019-17558   |  Y  |  Y  | 5.0.0 - 8.3.1, velocity response writer rce                 |
 | Apache Solr       | time-2021-0318   |  Y  |  Y  | all, apache solr arbitrary file reading                     |
 | Apache Solr       | CVE-2021-27905   |  Y  |  N  | 7.0.0-7.7.3, 8.0.0-8.8.1, replication handler ssrf          |
 | Apache Struts2    | S2-005           |  Y  |  Y  | 2.0.0 - 2.1.8.1, cve-2010-1870 parameters interceptor rce   |
 | Apache Struts2    | S2-008           |  Y  |  Y  | 2.0.0 - 2.3.17, debugging interceptor rce                   |
 | Apache Struts2    | S2-009           |  Y  |  Y  | 2.1.0 - 2.3.1.1, cve-2011-3923 ognl interpreter rce         |
 | Apache Struts2    | S2-013           |  Y  |  Y  | 2.0.0 - 2.3.14.1, cve-2013-1966 ognl interpreter rce        |
 | Apache Struts2    | S2-015           |  Y  |  Y  | 2.0.0 - 2.3.14.2, cve-2013-2134 ognl interpreter rce        |
 | Apache Struts2    | S2-016           |  Y  |  Y  | 2.0.0 - 2.3.15, cve-2013-2251 ognl interpreter rce          |
 | Apache Struts2    | S2-029           |  Y  |  Y  | 2.0.0 - 2.3.24.1, ognl interpreter rce                      |
 | Apache Struts2    | S2-032           |  Y  |  Y  | 2.3.20-28, cve-2016-3081 rce can be performed via method    |
 | Apache Struts2    | S2-045           |  Y  |  Y  | 2.3.5-31, 2.5.0-10, cve-2017-5638 jakarta multipart rce     |
 | Apache Struts2    | S2-046           |  Y  |  Y  | 2.3.5-31, 2.5.0-10, cve-2017-5638 jakarta multipart rce     |
 | Apache Struts2    | S2-048           |  Y  |  Y  | 2.3.x, cve-2017-9791 struts2-struts1-plugin rce             |
 | Apache Struts2    | S2-052           |  Y  |  Y  | 2.1.2 - 2.3.33, 2.5 - 2.5.12 cve-2017-9805 rest plugin rce  |
 | Apache Struts2    | S2-057           |  Y  |  Y  | 2.0.4 - 2.3.34, 2.5.0-2.5.16, cve-2018-11776 namespace rce  |
 | Apache Struts2    | S2-059           |  Y  |  Y  | 2.0.0 - 2.5.20, cve-2019-0230 ognl interpreter rce          |
 | Apache Struts2    | S2-061           |  Y  |  Y  | 2.0.0-2.5.25, cve-2020-17530 ognl interpreter rce           |
 | Apache Struts2    | S2-devMode       |  Y  |  Y  | 2.1.0 - 2.5.1, devmode remote code execution                |
 | Apache Tomcat     | Examples File    |  Y  |  N  | all version, /examples/servlets/servlet                     |
 | Apache Tomcat     | CVE-2017-12615   |  Y  |  Y  | 7.0.0 - 7.0.81, put method any files upload                 |
 | Apache Tomcat     | CVE-2020-1938    |  Y  |  Y  | 6, 7 < 7.0.100, 8 < 8.5.51, 9 < 9.0.31 arbitrary file read  |
 | Apache Unomi      | CVE-2020-13942   |  Y  |  Y  | < 1.5.2, apache unomi remote code execution                 |
 | CoreMail          | time-2021-0414   |  Y  |  N  | Coremail configuration information disclosure vulnerability |
 | Drupal            | CVE-2018-7600    |  Y  |  Y  | 6.x, 7.x, 8.x, drupalgeddon2 remote code execution          |
 | Drupal            | CVE-2018-7602    |  Y  |  Y  | < 7.59, < 8.5.3 (except 8.4.8) drupalgeddon2 rce            |
 | Drupal            | CVE-2019-6340    |  Y  |  Y  | < 8.6.10, drupal core restful remote code execution         |
 | Ecology           | time-2021-0515   |  Y  |  Y  | <= 9.0, e-cology oa workflowservicexml rce                  |
 | Elasticsearch     | CVE-2014-3120    |  Y  |  Y  | < 1.2, elasticsearch remote code execution                  |
 | Elasticsearch     | CVE-2015-1427    |  Y  |  Y  | < 1.3.7, < 1.4.3, elasticsearch remote code execution       |
 | Exchange          | CVE-2021-26855   |  Y  |  N  | 2010 2013 2016 2019, microsoft exchange server ssrf         |
 | Exchange          | CVE-2021-27065   |  Y  |  Y  | 2010 2013 2016 2019, exchange arbitrary file write          |
 | Eyou Email        | CNVD-2021-26422  |  Y  |  Y  | eyou email system has remote command execution              |
 | F5 BIG-IP         | CVE-2020-5902    |  Y  |  Y  | < 11.6.x, f5 big-ip remote code execution                   |
 | F5 BIG-IP         | CVE-2021-22986   |  Y  |  Y  | < 16.0.1, f5 big-ip remote code execution                   |
 | Fastjson          | VER-1224-1       |  Y  |  Y  | <= 1.2.24 fastjson parse object remote code execution       |
 | Fastjson          | VER-1224-2       |  Y  |  Y  | <= 1.2.24 fastjson parse object remote code execution       |
 | Fastjson          | VER-1224-3       |  Y  |  Y  | <= 1.2.24 fastjson parse object remote code execution       |
 | Fastjson          | VER-1247         |  Y  |  Y  | <= 1.2.47 fastjson autotype remote code execution           |
 | Fsatjson          | VER-1262         |  Y  |  Y  | <= 1.2.62 fastjson autotype remote code execution           |
 | Jenkins           | CVE-2017-1000353 |  Y  |  N  | <= 2.56, LTS <= 2.46.1, jenkins-ci remote code execution    |
 | Jenkins           | CVE-2018-1000861 |  Y  |  Y  | <= 2.153, LTS <= 2.138.3, remote code execution             |
 | Laravel           | CVE-2018-15133   |  N  |  Y  | 5.5.x <= 5.5.40, 5.6.x <= 5.6.29, laravel get app_key rce   |
 | Laravel           | CVE-2021-3129    |  Y  |  N  | ignition <= 2.5.1, laravel debug mode remote code execution |
 | Nexus OSS/Pro     | CVE-2019-7238    |  Y  |  Y  | 3.6.2 - 3.14.0, remote code execution vulnerability         |
 | Nexus OSS/Pro     | CVE-2020-10199   |  Y  |  Y  | 3.x <= 3.21.1, remote code execution vulnerability          |
 | Node.JS           | CVE-2021-21315   |  Y  |  N  | systeminformation < 5.3.1, node.js command injection        |
 | Oracle Weblogic   | CVE-2014-4210    |  Y  |  N  | 10.0.2 - 10.3.6, weblogic ssrf vulnerability                |
 | Oracle Weblogic   | CVE-2016-0638    |  Y  |  N  | 10.3.6.0, 12.2.1-3, t3 deserialization rce                  |
 | Oracle Weblogic   | CVE-2017-3506    |  Y  |  Y  | 10.3.6.0, 12.1.3.0, 12.2.1.0-2, weblogic wls-wsat rce       |
 | Oracle Weblogic   | CVE-2017-10271   |  Y  |  Y  | 10.3.6.0, 12.1.3.0, 12.2.1.1-2, weblogic wls-wsat rce       |
 | Oracle Weblogic   | CVE-2018-2894    |  Y  |  Y  | 12.1.3.0, 12.2.1.2-3, deserialization any file upload       |
 | Oracle Weblogic   | CVE-2018-3191    |  Y  |  N  | 10.3.6.0, 12.1.3.0, 12.2.1.3, t3 deserialization rce        |
 | Oracle Weblogic   | CVE-2019-2725    |  Y  |  Y  | 10.3.6.0, 12.1.3.0, weblogic wls9-async deserialization rce |
 | Oracle Weblogic   | CVE-2019-2890    |  Y  |  N  | 10.3.6.0, 12.1.3.0, 12.2.1.3, t3 deserialization rce        |
 | Oracle Weblogic   | CVE-2019-2729    |  Y  |  Y  | 10.3.6.0, 12.1.3.0, 12.2.1.3 wls9-async deserialization rce |
 | Oracle Weblogic   | CVE-2020-2551    |  Y  |  N  | 10.3.6.0, 12.1.3.0, 12.2.1.3-4, wlscore deserialization rce |
 | Oracle Weblogic   | CVE-2020-2555    |  Y  |  Y  | 3.7.1.17, 12.1.3.0.0, 12.2.1.3-4.0, t3 deserialization rce  |
 | Oracle Weblogic   | CVE-2020-2883    |  Y  |  Y  | 10.3.6.0, 12.1.3.0, 12.2.1.3-4, iiop t3 deserialization rce |
 | Oracle Weblogic   | CVE-2020-14882   |  Y  |  Y  | 10.3.6.0, 12.1.3.0, 12.2.1.3-4, 14.1.1.0, console rce       |
 | Oracle Weblogic   | CVE-2020-2109    |  Y  |  Y  | 10.3.6.0, 12.1.3.0, 12.2.1.3-4, 14.1.1.0, unauthorized jndi |
 | QiAnXin           | time-2021-0410   |  Y  |  Y  | qianxin ns-ngfw netkang next generation firewall front rce  |
 | RedHat JBoss      | CVE-2010-0738    |  Y  |  Y  | 4.2.0 - 4.3.0, jmx-console deserialization any files upload |
 | RedHat JBoss      | CVE-2010-1428    |  Y  |  Y  | 4.2.0 - 4.3.0, web-console deserialization any files upload |
 | RedHat JBoss      | CVE-2015-7501    |  Y  |  Y  | 5.x, 6.x, jmxinvokerservlet deserialization any file upload |
 | RuiJie            | time_2021_0424   |  Y  |  N  | get account password, background rce                        |
 | Saltstack         | CVE-2021-25282   |  Y  |  Y  | < 3002.5, saltStack arbitrary file writing vulnerability    |
 | Spring Data       | CVE-2018-1273    |  Y  |  Y  | 1.13 - 1.13.10, 2.0 - 2.0.5, spring data commons rce        |
 | Spring Cloud      | CVE-2019-3799    |  Y  |  Y  | 2.1.0-2.1.1, 2.0.0-2.0.3, 1.4.0-1.4.5, directory traversal  |
 | Spring Cloud      | CVE-2020-5410    |  Y  |  Y  | < 2.2.3, < 2.1.9, directory traversal vulnerability         |
 | ThinkPHP          | CVE-2019-9082    |  Y  |  Y  | < 3.2.4, thinkphp rememberme deserialization rce            |
 | ThinkPHP          | CVE-2018-20062   |  Y  |  Y  | <= 5.0.23, 5.1.31, thinkphp rememberme deserialization rce  |
 | Vmware vCenter    | time-2020-1013   |  Y  |  N  | <= 6.5u1, vmware vcenter arbitrary file reading (not cve)   |
 | Vmware vCenter    | CVE-2021-21972   |  Y  |  Y  | 7.0 < 7.0U1c, 6.7 < 6.7U3l, 6.5 < 6.5U3n, any file upload   |
 | VMware vRealize   | CVE-2021-21975   |  Y  |  N  | <= 8.3.0, vmware vrealize operations manager api ssrf       |
 +-------------------+------------------+-----+-----+-------------------------------------------------------------+
```
</details>

## ð Docker

```shell
docker build -t vulmap/vulmap .
docker run --rm -ti vulmap/vulmap  python vulmap.py -u https://www.example.com
```
