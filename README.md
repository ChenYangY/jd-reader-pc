#### 介绍

### 支持功能
    1. 登录(扫码登录)
        // 获取二维码
        https://qr.m.jd.com/show?appid=133&size=147&t=${Date.now()}

        set-cookie:
            wlfstk_smdl
            QRCodeKey

        
        // 检查二维码状态
        https://qr.m.jd.com/check?callback=json&appid=133&token=3m2p91b5liape3tac3aancgt2lxhq3zt&_=${Date.now()}
        
            token 为 wlfstk_smdl 的值
            需要在header 中填写 Referer 信息， Referer = https://passport.jd.com/, 不填将请求异常
        
        
    2. 书架
    3. 阅读
