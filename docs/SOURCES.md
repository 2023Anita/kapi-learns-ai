# 素材与整理说明

- 输入文件：用户提供的《卡皮学AI课件.html》。原文件保持不变。
- 原课件署名：动画由 lemo-opuscar 用代码绘制，角色姿势图为 AI 生成。
- `assets/`：由输入文件的 Base64 媒体逐字节解码提取；按内容去重，未重新编码视频或图片。文件校验见 `media-manifest.json`。
- `docs/images/cover.png`：以原课件角色和原画面制作的项目封面；排版源文件为 `showcase.html`。
- `docs/images/course.png`、`quiz.png`：本地浏览器运行课件的截图。
- README 的课堂用时为整理时提出的使用建议，不是原课件的教学效果结论。

原课件列出的科普来源：NASA Moon Facts、NOAA Fisheries、British Heart Foundation。本次项目整理未独立复核全部科普数据，也未验证教学效果。

原文件未附许可证或完整权利证明。本次不擅自添加 MIT、CC 等许可证；后续公开发布及再授权范围需由权利人明确。
