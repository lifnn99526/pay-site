---
title: 更新记录
---

## TBD: v3.0.0

### Changes

#### 事件

- 删除了 `SignFailed` 事件
- PayStarting 更改为 PayStarted
- PayStarted 更改为 PayFinish
- RequestReceived 更改为 CallbackReceived
- Yansongda\Pay\Events.php 更改为 Yansongda\Pay\Event.php
- Yansongda\Pay\Events 文件夹 更改为 Yansongda\Pay\Event (即相应的事件类更改)

#### 日志

- Yansongda\Pay\Log.php 更改为 Yansongda\Pay\Logger.php

#### 返回格式

为了方便大家使用，返回格式有所调整，请见 [返回格式](/docs/v3/quick-start/return-format.md)

### Add

- 通过插件机制兼容支付宝所有API
- 通过插件机制兼容微信所有API
