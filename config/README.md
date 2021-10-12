```json5
{
    "http_header": {  // Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/94.0.4606.71 Safari/537.36 Edg/94.0.992.38
        "User-Agent": "Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/78.0.3904.108 Safari/537.36",
        "Referer": "https://www.bilibili.com/",
        "Connection": "keep-alive"
    },
    "default_vote": {  // 默认投票
        "mode": 1,  // 选择模式，1为获取案件后有观点就参考观点，没有就投默认，2为获取案件后有观点就参考观点，没有就先暂存案件id跳过，等案件池空了获取不到观点后再倒回去投默认
        "vote": [0, 1, 2],  // 默认投票，0为好，1为普通，2为差，3为无法判断,填多个为随机投票，填一个为固定投票
        "once": true  // true为审满案件后退出，false为获取不到新案件后退出
    },
    "users": [
        {
            "cookieDatas": {  // 账号一
                "SESSDATA": "2f29d089%2C1648726584%2C4d764*a1",
                "bili_jct": "e4d082c44689dcba19897221b98fe420",
                "DedeUserID": "28524403"
            }
        },
        {
            "cookieDatas": {  // 账号二
                "SESSDATA": "xxxxx",
                "bili_jct": "xxxxx",
                "DedeUserID": "xxxxx"
            }
        }
    ]
}
```
