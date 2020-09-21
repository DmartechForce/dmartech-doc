---
description: 在联系人行为事件中可以根据表单提交的历史记录作为筛选条件
---

# 使用表单提交记录作为筛选条件的说明

_**场景：下发了会员注册表单，需要筛选出提交表单的记录中“城市“等于“上海“ 且  “邮箱“ 有值的联系人**_

在**“联系人分群“、实时旅程的“属性判断“、单次/周期旅程的“条件判断“**中的行为事件条件设置如下：

依次选择 表单事件—表单提交 ，“添加事件属性“

1）来源表单—会员注册—城市 等于 “上海“

2）来源表单—会员注册—邮箱 “有值“

两个条件之间的关系为“且“

![](../.gitbook/assets/image%20%28397%29.png)

联系人提交表单案例数据如下：

| 姓名 | 城市 | 邮箱 | 提交时间 |
| :--- | :--- | :--- | :--- |
| Tony | 上海 |  | 2020-06-01 12:00:00 |
| Tony | 北京 | 123@webpowerchina.com | 2020-06-01 11:00:00 |
| Peter | 上海 | peter@ | 2020-06-01 11:00:00 |

可以看到Tony提交了两次数据，两次分别满足“城市“等于“上海“和“邮箱有值“，但并不是同时满足两个条件，因此不会进入筛选结果；Peter提交的一条数据两个条件都满足，因此最后筛选出得联系人是Peter

_**需要注意的是，当用联系人属性筛选时，筛选条件同样为“城市“等于“上海“ 且 “邮箱“有值，此时脱离了表单提交事件这样的前提，筛选依据变成了联系人当前在平台中的最新属性值，因此筛选结果是不同的。Tony和Pter都会被筛选出。**_






