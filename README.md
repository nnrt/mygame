# 夜市小队 · GitHub Pages 试玩版

## 第一次发布
1. 登录GitHub，右上角 + → New repository。Owner选自己，名称可填mygame。免费账号选择Public，勾选Add README，再创建仓库。GitHub Free的Pages要求公开仓库，因此游戏代码和运行图片会公开。
2. 在仓库Code页面选择 Add file → Upload files。将解压后的index.html、assets文件夹、.nojekyll拖入上传区，保留assets目录结构，点击Commit changes提交到main。不要上传ZIP或在外面多套一层文件夹。README可保留GitHub初始化版本。
3. 仓库Settings → Pages。Source选择Deploy from a branch；Branch选择main；文件夹选择/(root)；Save。
4. 等待部署完成，在同一Pages页面点击Visit site，复制实际网址发给朋友。通常为https://你的用户名.github.io/mygame/，以页面显示为准。
5. 用无痕窗口复测：能免登录进入、角色图片正常、可以选择武器进入战斗，才算发布成功。若失败，到Actions查看pages build and deployment的报错。

更新时把新的index.html和assets覆盖提交到main，GitHub会重新部署。首次或更新发布可能需要几分钟。源码/图片的文件名和大小写不要改变。

不需要上传GitLab的.gitlab-ci.yml，也不需要创建GitHub自定义工作流。本包的.nojekyll是空文件，用于跳过Jekyll处理；Windows可能不显眼，上传时不要漏掉。

本包只含V9运行文件。角色原图、生成提示词和开发检查保留在完整V9工程中。游戏为网页试玩，存档在每个人自己的浏览器中，不共享进度，没有联网对战。手机尚未做真机验证，优先用电脑试玩。

目前只完成发布包准备，没有登录你的GitHub账号、上传文件或得到正式试玩地址。

官方说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
