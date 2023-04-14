# sspsign
SSP机场通用签到，支持青龙，支持多网站多账号批量签到
## 使用方式
`ql repo https://ghproxy.com/https://github.com/wdvipa/sspsign/raw/main/ssp.py`
## 青龙变量
| 参数 | 说明                     |  格式  |
| ---- | -----------------------  |  -------  |
| ssp  | 机场的名字，网址，账号密码 |  `机场名字\|机场的网址(https:www.xxxx...)\|第一个账号,密码;第二个账号,密码;... 多机场用回车隔开 例:名字\|https://yyy.com\|jjjj@qq.com,password;jjjj@gmail,password`  |
| ssp_fs  | 推送的平台 |  多个平台使用&隔开 支持push,kt,stb,qm,tel  |
| ssp_push  | Pushplus的推送token |  token  |
| ssp_ktkey  | 酷推的key |  key  |
| 暂不支持  | 暂不支持 |  暂不支持  |

参考仓库:https://github.com/GeorgeLxw/sspauto
