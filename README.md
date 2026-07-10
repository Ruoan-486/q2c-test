# q2c-test

QCE2ChatLab 开发测试版 · v1.5.0-dev

## 本次测试内容

### 头像修复
- 新增本地头像文件兜底（读取 QCE avatarPath）
- 修复 MIME 类型检测（支持 webp/gif/jpeg/png）
- Base64 清洗换行/空格

### 名称修复
- 群聊：群名片（cardName）> 昵称 > ID
- 私聊：好友备注（remark）> 昵称 > ID
- 消除名称漂移（统一从 uid_to_name 映射取）
- 统一用户ID体系（uin 优先，再兜底 uid）

详见 [QCE2ChatLab 主仓库](https://github.com/Ruoan-486/QCE2Chatlab)

## 反馈
发现 Bug 请提 Issue，或直接联系作者。