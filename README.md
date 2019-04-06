# Ant_Forest  

![AF_Pic](https://github.com/SuperMonster003/Ant_Forest/blob/master/Github_Material/AF_Pic_361%C3%97103.png?raw=true)
###### 蚂蚁森林能量收取工具 (基于Auto.js)

******
### 小私房话
******
:sweat_smile:  
定时任务什么的新功能先放一放了  
:smirk:  
还是图形配置界面更重要  
正在全力写图形界面

******
### 使用说明
******
1. 下载"Ant_Forest_Project"目录  
2. 将目录中的全部文件 (或目录本身) 放置于手机存储    
3. 使用"Auto.js"运行"Ant_Forest.js"文件  
4. 欢迎使用并反馈
> 安卓系统版本不低于 `7.0` / `Android Nougat` / `Android N`  
"Auto.js"已测试版本 `4.1.0 Alpha5` `4.1.1 alpha2` `Pro 7.0.0-3` (其他版本暂未测试)  
手机存储目录推荐"Auto.js"默认可识别目录 (如 `/sdcard/Scripts/` 或 `/sdcard/脚本/` )  

******
### 功能简介
******
* 收取好友能量
* 帮收好友能量 (可开关)  
* 收取自己能量  
** 指定时间范围内不间断监测自己的能量  
** ~~脚本辅助优化时间间隔~~  
* 能量收取结果统计/展示 (floaty/toast方式)
* 自动解锁屏幕  
** 可通过配置向导页面实现解锁密码录入  
* 定时执行任务  
** ~~使用配置向导设置Auto.js定时任务~~    
** 也可结合 `Xposed Edge Pro` 或 `Tasker` 实现定时任务  
* 多任务~~智能~~排队  
* 多语言支持 (简体中文 ~~繁体中文~~ ~~英语~~)  
** ~~根据系统语言自动切换语言 (可开关)~~
* 黑名单机制  
** 能量保护罩好友自动加入黑名单/自动解除    
** 黑名单详细信息提示 (控制台)  
** ~~用户自行增删黑名单好友 (手动输入/列表选取)~~  
* 信息加密存储  
** 自动生成"密文映射"字典文件  
** 使用密文存储账户信息/解锁密码等敏感信息  
* ~~账户智能切换~~  
** ~~防止其他账户 (如支付宝小号) 意外收取 (需录入主账户信息)~~      
** ~~主账户收取完毕可自动切换回之前登录的账户 (如果有此账户信息)~~  
* 适应恶劣条件  
** 脚本在恶劣条件下仍可正常运行或识别异常 (网络条件较差/~~意外来电~~/~~支付宝异常退出~~/支付宝更新弹窗/~~广告弹窗~~等)  
* ~~配置向导~~  
* ###### 其他功能详见[使用说明书](https://github.com/SuperMonster003/Ant_Forest/blob/master/Ant_Forest_Project/Documents/Ant_Forest_User_Manual.md)


******
### 版本历史
******
# v1.4.6
###### 2019/04/06
* `优化` 图形配置页面数据与控件关联性
* `优化` 图形配置页面本地数据存取逻辑

# v1.4.5
###### 2019/04/05
* `新增` 图形配置页面重置功能
* `新增` 图形配置页面数据实时更新
* `优化` 图形配置页面列表项功能增强模块化
* `优化` 图形配置页面退出/保存逻辑

# v1.4.4
###### 2019/04/04
* `新增` 图形配置页面保存按钮功能联动
* `新增` 数据样本不足导致统计结果异常的错误提示
* `修复` KeyCode()不可用问题

# v1.4.3
###### 2019/04/03
* `优化` 图形配置页面列表项功能模块化

# v1.4.2
###### 2019/04/03
* `修复` 图形配置页面滑动效果闪烁问题

# v1.4.1
###### 2019/04/02
* `新增` 图形配置页面主页View框架
* `新增` 图形配置页面子页面进出滑动效果
* `新增` 图形配置页面退出保存提示

# v1.4.0
###### 2019/04/02
* `新增` 图形配置页面 (骨架)

# v1.3.8
###### 2019/04/01
* `修复` 本地文件创建失败的问题

# v1.3.7
###### 2019/04/01
* `新增` `Auto.js Pro` 版本兼容
* `修复` 解锁配置向导在 `4.1.1 alpha2` 的兼容问题  
 
# v1.3.6
###### 2019/03/30
* `修复` floaty结果显示hint区域溢出问题

# v1.3.5
###### 2019/03/29
* `新增` floaty方式显示收取结果 (可与toast方式切换选择)
* `修复` floaty显示问题及其他异常处理
* `修复` 截图权限申请容易高失败率问题
* `优化` 帮收能量球检测准确性

# v1.3.4
###### 2019/03/28
* `修复` 收取能量统计失败的错误消息处理

# v1.3.3
###### 2019/03/27
* `新增` 自己能量球数等于6时的收取处理
* `修复` 帮收球和收取球同时存在时可能出现收取失效的问题
* `修复` 帮收能量球遗留数据清空滞缓问题
* `优化` 智能返回功能的APP退出逻辑

# v1.3.2
###### 2019/03/26
* `新增` 自己能量球数等于6时的收取处理
* `优化` 语言切换控制台信息显示
* `优化` 截图权限申请的异常处理

# v1.3.1
###### 2019/03/25
* `新增` 截图权限申请工具函数
* `修复` 保护罩颜色识别区域分辨率适配问题
* `灵感` 可设置低亮度运行并在运行结束后恢复状态

# v1.3.0
###### 2019/03/25
* `新增` 脚本运行超时配置项 (单次最大运行时间)
* `修复` 解锁功能配置向导toast消息遮挡问题 (替换为content显示方式)
* `修复` 黑名单自动管理功能的时间标记滞留问题
* `修复` 帮收能量单位为"kg"时的数据统计异常
* `优化` 解锁功能配置向导增加密码示例
* `优化` 密文模块的方法参数调整
* `优化` 新的能量收取逻辑下提升帮收效率
* `优化` 智能返回机制 (前台拉起优先于强制关闭)
* `优化` 增加进入好友森林后没有能量球可收取/帮收时的控制台消息

# v1.2.1
###### 2019/03/24
* `优化` 优化保护罩检测/能量收取逻辑
* `修复` 解锁功能配置向导第一步返回键失效

# v1.2.0
###### 2019/03/24
* `新增` 能量罩好友黑名单自动管理功能
* `新增` 解锁配置向导
* `新增` 使用自定义本地存储模块模拟Storage模块 (不受卸载APP/清除数据影响)
* `修复` 解锁模块通用化
* `优化` 整合控制台详细信息开关
* `优化` 能量罩检测效率

# v1.1.2
###### 2019/03/21
* `优化` 优化帮收好友能量逻辑 提升收取效率/准确率/稳定性
* `优化` 提升定位"查找更多好友"按钮稳定性并增加异常处理
* `灵感` 使用[JSEncrypt](https://github.com/travist/jsencrypt)结合或替代原有加密方式
* `灵感` 个人能量球总数为6时 收取后可能出现新的能量球
* `灵感` 好友能量球总数为6时 帮收后再次进入他/她的森林 可能有新的能量球
* `灵感` 功能模块分离

# v1.1.1
###### 2019/03/20 
* `修复` 模块/脚本文件的依赖关系
* `修复` 密文工具功能失效
* `优化` 全面调整代码结构

# v1.1.0
###### 2019/03/19 - 脚本可用性暂未测试 
* `新增` 自动检测/生成/引用本地"密文映射"文件
* `移除` 指定账户智能切换功能 (暂时关闭)
* `修复` 收取完毕返回好友列表时 当前屏幕信息没有及时处理即开始滑屏
* `灵感` 账户智能切换 (账户录入 已录入账户的选择/信息更新) 
* `灵感` 使用密文解析工具时若发现"密文映射"文件异常 及时报错 

# v1.0.0
###### 2019/03/19 - 此版本依赖设备本地密文映射文件 因此暂不可用
* `新增` 自动收取好友能量 (基于Auto.js控件/颜色识别)
* `新增` 自动帮收好友能量
* `新增` 可在指定时间范围内不间断检测自己的能量 (感谢 [e1399579](https://github.com/e1399579/autojs))
* `新增` 自动解锁屏幕 (感谢 [e1399579](https://github.com/e1399579/autojs))
* `新增` 脚本排队机制 (感谢 [e1399579](https://github.com/e1399579/autojs))
* `新增` 脚本运行结束后智能关屏 (感谢 [e1399579](https://github.com/e1399579/autojs))
* `新增` 脚本运行结束后智能保留/结束APP进程
* `新增` 自动切换APP语言 (目前暂时统一切换为简体中文)
* `新增` 若当前用户不是指定账户 (主账户) 则自动切换为主账户 (需录入账户信息)
* `新增` 可显示/关闭能量罩的剩余时间 (因黑名单系统未完成 暂未投入使用)
* `新增` 可显示/关闭收取/帮收好友能量的详细信息
* `新增` 可分别显示收取自己能量的总数与收取好友能量的总数
* `新增` 将Auto.js的日志保存在指定的文件中 (Auto.js v4.1.0版本以上)
* `优化` 精简部分无用的方法
* `优化` 脚本部分参数可供用户自行配置 (目前只可在脚本文件中配置)
* `优化` 部分参数值可以自动修正/修复 
* `优化` 恶劣条件下 (不稳定的互联网连接等) 的脚本稳定性 
* `优化` 收取能量时 先保证能量收取成功 然后立即返回 (稳定性/高效率) 
* `优化` 帮收能量时 若能量帮收成功 立即返回 (高效率) 
* `优化` 线程循环展开列表 节约滑动好友列表时"加载中"的时间 (高效率) 
* `优化` 线程监视好友列表底部 一旦进入屏幕 立即停止列表滑动 (高效率) 
* `优化` 优化好友列表滑动的稳定性 
* `灵感` ~~能量罩用户黑名单功能实现 (目前只是空壳)~~ v2.0.0
* `灵感` 脚本使用说明文档 (包含使用细节和注意事项)
* `灵感` ~~自动生成并引用本地"密文映射"字典~~ v1.1.0
* `灵感` ~~本地"密文映射"加解密工具~~ v1.1.0
* `灵感` 主要方法的JSDoc注释
* `灵感` 可用于配置脚本的UI界面 (高交互性)
* `灵感` ~~帮收好友能量增加精准性及效率~~ v1.1.2
* `灵感` 登录主账户之前记录当前用户信息 脚本结束后恢复登录 (需录入账户信息)
* `灵感` ~~额外文件的生成/存取不受机型限制~~ v2.0.0
* `灵感` 语言智能切换且可供用户配置
* `灵感` ~~使用Floaty方式替代Toast消息显示~~ v1.3.5
* `灵感` 好友数量小于10的异常处理
* `灵感` shell强制结束APP的替代方案 (避免经常出现的几秒钟黑屏)
