### 说明
收集一些免费、国内(不会走代理)用于请求本机IPv4的接口，过滤掉一些会走代理、显示代理服务器IP的API。

#### 收集中...

|                                             站点/API                                             | 请求方法 |                    返回内容                    | 返回格式 | 可用 |
| :-----------------------------------------------------------------------------------------: | :------: | ---------------------------------------------- | :------: | ---- |
|                         [IPcn](https://ip.cn/api/index?ip=&type=0)                          |   GET    | IP地址、国省市、运营商                           |   JSON   | ❌  |
|             [哔哩哔哩1](https://api.live.bilibili.com/client/v1/Ip/getInfoNew)              |   GET    | IP地址、国省市、运营商、经纬度                    |   JSON   | ✔️   |
|       [哔哩哔哩2](https://api.live.bilibili.com/ip_service/v1/ip_service/get_ip_addr)       |   GET    | IP地址、国省市、运营商、经纬度                    |   JSON   | ✔️   |
|                          [QQ](https://r.inews.qq.com/api/ip2city)                           |   GET    | IP地址、国省、行政区划代码等                     |   JSON   | ✔️   |
|                     [又拍云](https://pubstatic.b0.upaiyun.com/?_upnode)                     |   GET    | IP地址、洲国省市、运营商等                       |   JSON   | ✔️   |
|                             [ITDOG](https://ipv4_ct.itdog.cn/)                              |   GET    | IP地址、国省市、运营商等                         |   JSON   | ✔️   |
|               [百度](https://qifu-api.baidubce.com/ip/local/geo/v1/district)                |   GET    | IP地址、洲国省市区、运营商、行政区划代码、经纬度等 |   JSON   | ✔️   |
|                             [IPIP](https://myip.ipip.net/json)                              |   GET    | IP地址、国省市、运营商                           |   JSON   | ✔️   |
|                    [纯真网络](https://www.cz88.net/api/cz88/ip/geo?ip=)                     |   GET    | IP地址、国省市区、运营商、行政区划代码、经纬度等   |   JSON   | ✔️   |
|                            [IP查询](https://2025.ipchaxun.com/)                             |   GET    | IP地址、国省市区、运营商、行政区划代码等          |   JSON   | ✔️   |
|            [中国科学技术大学测速网站](https://test.ustc.edu.cn/backend/getIP.php)            |   GET    | IP地址                                         |   JSON   | ✔️   |
| [在线工具大全](https://openapi.lddgo.net/base/gtool/api/v1/GetIp)<sup>手动复制打开</sup>     |   GET    | IP地址                                         |   JSON   | ✔️   |
|                  [IP数据云](https://app.ipdatacloud.com/v1/ip_self_search)                  |   POST   | IP地址、洲国省市、经纬度                         |   JSON   | ✔️   |
|               [南京大学测速站](https://test.nju.edu.cn/backend/getIP.php)                    |   GET    | IP地址                                         |   JSON   | ✔️   |
|                 [东北大学网络测速站](https://speed.neu.edu.cn/getIP.php)                     |   GET    | IP地址                                         |   HTML   | ❌   |
|                      [ipify](https://api.ipify.org/?format=json)                           |   GET    | IP地址                                         |   JSON   | ✔️   |
