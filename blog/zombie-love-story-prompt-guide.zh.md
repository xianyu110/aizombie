export const meta = {
  title: 'Zombie Love Story 提示词说明（为什么两张图必须是不同的人）',
  description:
    'ZombieHug 如何绑定照片 1 / 照片 2，参考图同人时为什么会「自己抱自己」，以及何时其实不用写提示词。',
  created_at: '2026-10-07',
  author_name: 'ZombieHug',
  author_image: '/logo.png',
};

很多丧尸拥抱成片翻车，原因很无聊：**模型只看到了一个人**。两张参考图如果是同一张脸（或同一段 demo 的两帧），拥抱就会变成同款衣服的自我克隆。

## 在 aizombie.app 通常不用写提示词

[ZombieHug](https://aizombie.app) 用固定模板。你上传两张图，服务端拼 Seedance 2.5 提示词：

- **@image1 / 照片 1** → 持枪的幸存者
- **@image2 / 照片 2** → 变成丧尸的一方（回忆里恢复健康）

可选备注只改**回忆地点**，不改剧情结构。

## 照片检查清单

1. 两个**不同**的人（宠物模板则是人 + 猫狗）。
2. 脸清楚、光线正常，别拿别人爆款成片截帧当参考。
3. 人像槽位每张一个成年人；猫狗只用对应模板。
4. 有权使用肖像。

## 如果你在别的工具里自己写提示词

锁住两张脸、卡准扑抱切点、禁止血腥与开枪、保持常速。骨架示例：

> 约 20 秒，竖屏 9:16，写实，硬切，无慢动作，无文字。照片 1 持枪；照片 2 已变成丧尸。两张脸全程稳定。现在时：废弃小屋 → 放下枪 → 张开双臂 → 扑抱。接触瞬间硬切到同一对两人的温暖回忆。无血腥，枪不开火。

不想写提示词就直接用 [aizombie.app Create](https://aizombie.app)。

## 相关

- [怎么做 AI 僵尸拥抱短视频](/blog/how-to-make-ai-zombie-hug-video)
- 样片：[/samples/sample.mp4](https://aizombie.app/samples/sample.mp4)
