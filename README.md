# 督导工作台演示

最新交互原型，使用模拟数据。

## 在线演示

点击下方链接即可直接体验，无需下载 HTML 或手动修改网址。

| 原型 | 在线体验 | 源文件 |
| --- | --- | --- |
| 原型1.1 · 督导工作台 | [打开工作台](https://tarynquan-del.github.io/supervisor-workbench-demo/) | [index.html](index.html) |
| 巡店待办配置后台 | [打开配置后台](https://tarynquan-del.github.io/supervisor-workbench-demo/admin.html) | [admin.html](admin.html) |
| 报销流程分支 · 多票据报销 | [打开报销演示](https://tarynquan-del.github.io/supervisor-workbench-demo/reimbursement.html) | [reimbursement.html](reimbursement.html) |

报销演示入口：打开报销演示 → 新建报销 → 填写业务说明并添加票据（也可选择示例票据）→ 确认并开始识别 → 报销单草稿。

## 演示说明

- 工作台：index.html
- 巡店待办配置：admin.html
- 报销流程分支：[reimbursement.html](reimbursement.html)，支持多票据上传与追加识别、草稿编辑、基础资料查询、金额自动计算、费用明细左滑删除、分组计数、审批与撤回，以及审批完成后自动模拟付款。
- 固定一次完整语音录入演示门店：Tecno Store Centro

记录与配置保存在各自浏览器中，互不共享。照片、语音识别、定位、票据识别均为演示流程。

列表按待处理、处理中、已审批、已支付分组；提交、审批和付款均为模拟流程，不会发起真实支付。

发布：Settings → Pages → Deploy from a branch → main / (root) → Save。
