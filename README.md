# 1 open your RLSetting => OB\Settings
# 2 => Optn file RLSettings.json
# 3 Clear all data in file
# 4 Copy this code and paste in file => save file => Done 
```
{
  "General": {
    "WaitTime": 100,
    "RequestTimeout": 60,
    "MaxHits": 0,
    "BotsDisplayMode": 1,
    "EnableBotLog": false,
    "SaveLastSource": false,
    "SendToCheckOnAbort": false,
    "WebhookEnabled": false,
    "WebhookURL": "",
    "WebhookUser": "Undefined"
  },
  "Proxies": {
    "ConcurrentUse": false,
    "NeverBan": false,
    "BanLoopEvasion": 100,
    "ShuffleOnStart": true,
    "Reload": true,
    "ReloadSource": 2,
    "ReloadPath": "",
    "ReloadType": 0,
    "ReloadInterval": 0,
    "AlwaysGetClearance": false,
    "GlobalBanKeys": [],
    "GlobalRetryKeys": [],
    "RemoteProxySources": [
      {
        "Id": 1382439405,
        "Active": true,
        "Url": "https://api.proxyscrape.com/v2/?request=getproxies&protocol=socks4&timeout=5000&country=all",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1603632336,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 703276302,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/socks4.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1091836456,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/socks5.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 254862813,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/hookzof/socks5_list/master/proxy.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1776164364,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/zloi-user/hideip.me/main/https.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1246999903,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/zloi-user/hideip.me/main/http.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 498091865,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/zloi-user/hideip.me/main/socks4.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1359711439,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/zloi-user/hideip.me/main/socks5.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 2060479558,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/prxchk/proxy-list/main/socks4.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1376478382,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/prxchk/proxy-list/main/socks5.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1304218632,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/prxchk/proxy-list/main/http.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1243729634,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/http/data.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 689628273,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/socks4/data.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 596340183,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/protocols/socks5/data.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 2095259727,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/casals-ar/proxy-list/main/socks5",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 2023909457,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/casals-ar/proxy-list/main/socks4",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 198518850,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/casals-ar/proxy-list/main/https",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 412489379,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/vakhov/fresh-proxy-list/master/http.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 2113801205,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/vakhov/fresh-proxy-list/master/https.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1039033391,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/vakhov/fresh-proxy-list/master/socks4.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 2114059606,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/vakhov/fresh-proxy-list/master/socks5.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 539144936,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/proxylist-to/proxy-list/main/socks5.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 184920069,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/proxylist-to/proxy-list/main/socks4.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1934265978,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/proxylist-to/proxy-list/main/http.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 20133873,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/lkx1331anon/proxy-list/main/http_worldwide.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 400107640,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/roosterkid/openproxylist/main/HTTPS_RAW.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 509173425,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/roosterkid/openproxylist/main/SOCKS4_RAW.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 553122956,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/roosterkid/openproxylist/main/SOCKS5_RAW.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1455318737,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/sunny9577/proxy-scraper/master/generated/socks5_proxies.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1705193847,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/sunny9577/proxy-scraper/master/generated/http_proxies.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1982661679,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/sunny9577/proxy-scraper/master/generated/socks4_proxies.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 488490902,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/ObcbO/getproxy/master/file/socks5.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 550447741,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/ObcbO/getproxy/master/file/socks4.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 358800197,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/ObcbO/getproxy/master/file/https.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1225313322,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/ObcbO/getproxy/master/file/http.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1174207325,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 744935189,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/socks4.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 911974766,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/socks5.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 173984486,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/TheLime1/Validity/main/proxy_list.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 893309000,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/officialputuid/KangProxy/KangProxy/socks5/socks5.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 297655049,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/officialputuid/KangProxy/KangProxy/http/http.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1240392076,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/officialputuid/KangProxy/KangProxy/https/https.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1952828818,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/officialputuid/KangProxy/KangProxy/socks4/socks4.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1891491967,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/TuanMinPay/live-proxy/master/http.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1119889751,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/TuanMinPay/live-proxy/master/socks4.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1389909549,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/TuanMinPay/live-proxy/master/socks5.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 735606820,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/Anonym0usWork1221/Free-Proxies/main/proxy_files/http_proxies.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 637648389,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/Anonym0usWork1221/Free-Proxies/main/proxy_files/https_proxies.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 849042329,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/Anonym0usWork1221/Free-Proxies/main/proxy_files/socks4_proxies.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 670879656,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/Anonym0usWork1221/Free-Proxies/main/proxy_files/socks5_proxies.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 56818224,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/MuRongPIG/Proxy-Master/main/http.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1750000379,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/MuRongPIG/Proxy-Master/main/socks4.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1479625565,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/MuRongPIG/Proxy-Master/main/socks5.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1412128867,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/ErcinDedeoglu/proxies/main/proxies/http.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1404226771,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/ErcinDedeoglu/proxies/main/proxies/https.txt",
        "Type": 0,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 1064487400,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/ErcinDedeoglu/proxies/main/proxies/socks4.txt",
        "Type": 1,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      },
      {
        "Id": 518356233,
        "Active": true,
        "Url": "https://raw.githubusercontent.com/ErcinDedeoglu/proxies/main/proxies/socks5.txt",
        "Type": 3,
        "Pattern": "([0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+:[0-9]+)",
        "Output": "[1]"
      }
    ]
  },
  "Captchas": {
    "CurrentService": 0,
    "AntiCapToken": "",
    "ImageTypToken": "",
    "DBCUser": "",
    "DBCPass": "",
    "TwoCapToken": "",
    "RuCapToken": "",
    "DCUser": "",
    "DCPass": "",
    "AZCapToken": "",
    "SCToken": "",
    "SRUserId": "",
    "SRToken": "",
    "TrueCapUser": "",
    "TrueCapToken": "",
    "CIOToken": "",
    "CDToken": "",
    "CustomTwoCapToken": "",
    "CustomTwoCapDomain": "example.com",
    "CustomTwoCapPort": 80,
    "BypassBalanceCheck": false,
    "Timeout": 120
  },
  "Selenium": {
    "Browser": 0,
    "Headless": false,
    "FirefoxBinaryLocation": "C:\\Program Files (x86)\\Mozilla Firefox\\firefox.exe",
    "ChromeBinaryLocation": "C:\\Program Files (x86)\\Google\\Chrome\\Application\\chrome.exe",
    "ChromeExtensions": [],
    "DrawMouseMovement": false,
    "PageLoadTimeout": 60
  }
}
```
