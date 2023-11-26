# sspsign
SSP机场通用签到，支持青龙，支持多网站多账号批量签到
## 使用方式
`ql repo https://ghproxy.com/https://github.com/wdvipa/sspsign/raw/main/ssp.py`
如需直接运行或不用环境变量吧文件开头的cs变量改为2即可
青龙最新版本订阅请填写下面内容（没写的别乱填）
|数据|内容|
|----|----|
|名称|多机场签到|
|链接|`https://ghproxy.com/https://github.com/wdvipa/sspsign.git`|
|定时类型|crontab|
|定时规则|	2 2 28 * *|
|白名单|ssp.py|
## 更新内容
增加失败重试功能，修复editXY详情显示，可能部分网站还不行改首字母大小写即可,新增适配Metron主题的详情显示，增加测试变量，增加直接修改数据变量方便直接运行
## 青龙变量
| 参数 | 说明                     |  格式  |
| ---- | -----------------------  |  -------  |
| ssp  | 机场的名字，网址，账号密码 |  `机场名字\|机场的网址(https:www.xxxx...)\|第一个账号,密码;第二个账号,密码;... 多机场用回车隔开 例:名字\|https://yyy.com\|jjjj@qq.com,password;jjjj@gmail,password`  |
| ssp_fs  | 推送的平台 |  多个平台使用&隔开 支持push,kt,stb,qm,tel  |
| ssp_push  | Pushplus的推送token |  token  |
| ssp_ktkey  | 酷推的key |  key  |
| 暂不支持  | 暂不支持 |  暂不支持  |

参考仓库:https://github.com/GeorgeLxw/sspauto
