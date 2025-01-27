# 图书馆
你可以通过Ham便捷地使用图书馆预约功能

## 准备使用
在使用图书馆前，你需要准备：
- 图书馆账号
- 腾讯云® 文字识别

### 准备图书馆账号
默认而言，你在开学前几周就已经设置好图书馆账号。图书馆账号的密码默认为你身份证的后6位。如果你忘记了图书馆账号，请及时到图书馆前台挂失。

### 准备腾讯云® 文字识别账号
图书馆座位预约软件提供商增加了验证码。为了完成自动预约等功能，Ham已完成验证码自动识别。

验证码自动识别使用了腾讯云® 文字识别相关技术。为了完成身份认证，在使用图书馆功能前，你**必须**输入你的腾讯云® 文字识别信息。对于每个用户，每个月有1000次的免费识别额度。
而如果你不恶意预约图书馆，一个月下来这额度完全够用。

::: warning 注意
Ham不会也不想获取你的任何信息，包括你的腾讯云®账号。虽然Ham有多种设计防止你的各类敏感数据泄漏，比如账号信息、腾讯云®账号信息等，但你也应该有义务保护自己的账号。
:::


#### 如何开通腾讯云® 文字识别服务？
点击下方链接了解更多

[如何开通腾讯云文字识别](https://cloud.tencent.com/document/product/866/17622)

[获取Secret ID和Secret Key](https://console.cloud.tencent.com/cam/capi)

::: danger 重要提示
如果你未曾使用过腾讯云文字识别服务，**请务必进入控制台填写资料后开通服务！**

如果你没有填任何资料，说明你没有开通成功，那么文字识别服务自然就不可用。
:::

## 看板预约
看板预约，顾名思义你可以看着每个图书馆每个房间每个座位的空余情况，有空位的话直接预约。

看板预约适用的情况：
- 你某一天突然想去图书馆但没有预约
- 你不在乎要预约哪个房间、哪个座位

看板预约位于图书馆功能选项卡的第一个（旧版本为"预约"）。

::: tip 提示
看板预约在预约前不会检查该座位的剩余情况。即在你选择座位后，但该座位被其他同学成功预约时，看板预约并不会帮助你选择附近的座位。
:::

## 快速预约
你可以保存喜爱的座位，然后直接点击预约预约之。

快速预约使用的情况：
- 你经常去图书馆，经常坐在一个固定的位置
- 你需要使用自动化预约功能
- 你突然想去图书馆，想坐在某个房间中

在你曾在Ham预约过座位，或选择"首选座位"后，快速预约选项卡将出现在图书馆的主页上。你也可以点击座位、时间临时更改座位与预约时间。

::: tip 提示
快速预约尽量满足你"首选座位"选择的需求。在你选择的座位预约失败后，Ham会立刻选择附近的座位预约。
:::

## 首选座位
快速预约时的默认座位。

你可以提前选择需要预约的时间、座位、偏好。在你每次进入图书馆页面时，快速预约将自动选择你的设置。

首选座位设置位于"图书馆设置"中。

## 预约状态
当Ham查询到你拥有有效预约时，将会显示在图书馆主页与状态页上。

你可以在预约状态上更改预约时间、或取消预约。

如果你预约了较长时间，入馆后需要在中途离开一段时间（超过图书馆允许的限制），你也可以在离开前更改预约时间，让你在回来图书馆时也能坐到先前的座位上。

## 历史记录
你可以查看你的图书馆预约记录。

## 小组件
你可以将小组件放在桌面上，以提醒你预约的地点、时间，或你临时离开的时间。

你也可以设置小组件的更新时间，但如果更新时间过短，可能会导致图书馆临时封号（一般15分钟为宜）。

## 其它图书馆设置
### 使用验证码预约
Ham与腾讯云进行验证码识别时需要一段时间（虽然肯定比真人识别快）。但如果预约时不需要验证码预约，而你还是使用验证码预约，这将白白浪费你的额度与预约时间。

是否需要使用验证码预约请以图书馆小程序预约为准，请根据实际情况开启或关闭该选项。

### 重置
当图书馆出现异常情况时，请点击"重置"

### 自动化（Android）
自动化设置位于"我的"-"自动化"中。开启后，Ham将会在设定的时间预约"首选座位"。预约时，Ham会根据系统时间判断是否预约明天。

## 必要的权限
### 自动化
- Android: 自启动
### 小组件
- Android: 自启动