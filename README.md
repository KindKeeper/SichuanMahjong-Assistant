# 川麻实战助手 v0

牌效 + 迷你 EV 推荐的纯前端 PWA（Pyodide 在浏览器内运行引擎，无需服务器）。

**使用**：手机/电脑浏览器打开 https://kindkeeper.github.io/SichuanMahjong-Assistant/

- 输入 13~14 张手牌（点选），选精度，一键分析
- 输出：推荐牌型 + EV 条形 + 胡牌率 + 向听 + 切牌建议
- 口径：v1.9 引擎（碰杠开 / 官方累加计分 / 哑对手）

引擎源码与构建脚本：主仓库 KindKeeper/SichuanMahjong 的 app/pwa/。
更新流程：在主仓库运行 app/pwa/build.py 生成 dist/，拷贝到本仓库 docs/ 后推送。
