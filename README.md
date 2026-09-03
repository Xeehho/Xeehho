<img src="assets/banner.svg" width="100%" alt="XEEHHO Minecraft pixel banner" />

<p align="center">
  <img src="assets/creeper.svg" width="40" alt="creeper" />
  <img src="assets/diamond.svg" width="40" alt="diamond" />
  <img src="assets/chest.svg" width="40" alt="chest" />
  <img src="assets/crafting.svg" width="40" alt="crafting" />
  <img src="assets/creeper.svg" width="40" alt="creeper" />
</p>

<img align="right" src="assets/iron-golem.svg" width="160" alt="Iron Golem figurine" />

### 关于我

个人游戏独立开发者，正在使用 Godot 引擎开发独立游戏 **KufuWorld**（进行中），一人承担玩法设计、程序开发与资源管线。

写游戏之余也写工具：技术底色是跨端前端（React / Taro / TypeScript）与 AI 应用工程（Python / LangChain / LangGraph），擅长把工程化与 AI 工作流引入独立开发，一个人跑完从设计到发布的全流程。

热门插件库 **dsh-web**（原 dsh-web-ui）与桌面端 **dsh-desktop** 贡献者之一，深度参与皮肤中心 / Wallpaper Engine 壁纸模块的架构修复。

### 正在开发 / Now Building

<p>
  <a href="https://github.com/Xeehho/kufuworld">
    <img src="https://img.shields.io/badge/KufuWorld-Godot%20%20%7C%20%20GDScript-5D9C3D?style=for-the-badge&logo=godotengine&logoColor=white" alt="KufuWorld" />
  </a>
  <a href="https://github.com/Xeehho/kufuworld">
    <img src="https://img.shields.io/badge/%E4%BB%A3%E7%A0%81%E5%85%A8%E7%A8%8B%E5%85%AC%E5%BC%80-%E2%9C%94-4A7F2E?style=for-the-badge&logo=github&logoColor=white" alt="open source" />
  </a>
</p>
<sub>一款用 Godot 引擎从零打造的 2D 武侠 RPG：气候驱动的程序化开放世界，一个人 = 玩法 + 程序 + 资源管线。</sub>

<br clear="right" />

<img src="assets/kufuworld-preview.png" width="100%" alt="KufuWorld 青石城南门实机截图：坊市、城墙与山地荒野" />

<sub>▲ 青石城南门：坊市 / 城墙 / 山地荒野一图同框（实机截图，世界与贴图全部程序化生成）</sub>

<br /><br />

<details open>
<summary><b>开发进度 / Progress（2026-09）</b></summary>
<br />

| 模块 | 状态 |
|------|------|
| 程序化世界：气候七群系 · 河流水文 · 山口垭口可行域规划 | ✅ |
| 唐制城池「青石城」· 四门官道 · 7 村镇三模板 · 5 门派领地 | ✅ |
| 战斗：三架势 / 连招树 / 破绽反击 + 18 武学 + 6 内功五行相克 | ✅ |
| 任务告示板 / 20 种奇遇 / 誓约 / 供求定价商店 / 建造 / 农场 / 天气昼夜 / 死亡传承 | ✅ |
| 主线剧情铺量 · 音效 BGM · 存档 · 小地图 | 🔨 进行中 |

<sub>工程化底座：<b>118 项自动化回归断言全绿</b> · 71 个 GDScript 脚本（19,000+ 行）· 930 张程序化生成贴图 · 80+ 自研探针/验证工具 · AI 辅助开发工作流（Godot MCP 插件）</sub>

</details>

<br />

<img src="assets/divider-path.svg" width="100%" alt="path" />

### 开源贡献 / Open Source

<table>
  <tr>
    <td>
      <img src="https://img.shields.io/badge/dsh--web-7%20PRs%20merged-5D9C3D?style=for-the-badge&logo=github&logoColor=white" alt="dsh-web contributor" />
      <br />
      <sub>热门社区插件库（原 dsh-web-ui）· 皮肤中心 / 壁纸引擎模块</sub>
      <br /><br />
      <b>已合并的代表性 PR：</b>
      <br />
      <a href="https://github.com/zhu1090093659/dsh-web/pull/793">#793</a> 场景提取缓存版本化 —— 修复插件升级后旧缓存不失效导致的壁纸显示异常
      <br />
      <a href="https://github.com/zhu1090093659/dsh-web/pull/784">#784</a> 壁纸表面 token 回退解析 —— html 上缺变量时从 body 兜底
      <br />
      <a href="https://github.com/zhu1090093659/dsh-web/pull/789">#789</a> 皮肤半透明面板按 scrim 契约缩放
      <br />
      <a href="https://github.com/zhu1090093659/dsh-web/pull/622">#622</a> 开机恢复持久化壁纸
      <br />
      <a href="https://github.com/zhu1090093659/dsh-web/pull/843">#843</a> / <a href="https://github.com/zhu1090093659/dsh-web/pull/853">#853</a> / <a href="https://github.com/zhu1090093659/dsh-web/pull/860">#860</a> 皮肤与壁纸互斥、live 模式降级等 UX 修复
      <br />
      <a href="https://github.com/zhu1090093659/dsh-web/commits?author=Xeehho">→ 查看全部提交</a>
    </td>
    <td>
      <img src="https://img.shields.io/badge/dsh--desktop-1%20PR%20%2B%20fixes-4A7F2E?style=for-the-badge&logo=github&logoColor=white" alt="dsh-desktop contributor" />
      <br />
      <sub>DSH 桌面客户端 · <a href="https://github.com/anywhere-labs/dsh-desktop/graphs/contributors?from=2026%2F5%2F30">贡献者之一</a> · 插件加载与布局服务</sub>
      <br /><br />
      <b>已合入仓库的贡献：</b>
      <br />
      <a href="https://github.com/anywhere-labs/dsh-desktop/pull/518">#518</a> 桌面布局服务冲突降级 —— 插件与上游布局服务注册同名服务时安全让位，避免 cordis 整体回滚导致设置页样式消失
      <br />
      <a href="https://github.com/anywhere-labs/dsh-desktop/commit/2756dbc">→ 查看合入提交</a>
      <br /><br />
      <sub>另独立排查并修复过桌面端 lib/client.js 与宿主 lib/index.js 热更新不生效等运行时问题。</sub>
    </td>
  </tr>
</table>

### 技术栈 / Tech Stack

<p>
  <img src="assets/chest.svg" width="44" alt="skill chest" />
  <br /><br />
  <b>游戏开发 / Game Dev</b>
  <br />
  <img src="https://img.shields.io/badge/GDScript-35549E?style=flat-square&logo=godotengine&logoColor=white" />
  <img src="https://img.shields.io/badge/Godot%204-5D9C3D?style=flat-square&logo=godotengine&logoColor=white" />
  <img src="https://img.shields.io/badge/%E7%A8%8B%E5%BA%8F%E5%8C%96%E7%94%9F%E6%88%90-Procedural%20Art-DAA520?style=flat-square" />
  <br /><br />
  <b>前端 / Frontend</b>
  <br />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Taro-5D9C3D?style=flat-square&logo=taro&logoColor=white" />
  <br /><br />
  <b>AI 应用 / AI Engineering</b>
  <br />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-4A7F2E?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
</p>

<p align="center">
  <img src="assets/crafting.svg" width="44" alt="crafting" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Xeehho&theme=gruvbox" alt="stats" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Xeehho&theme=gruvbox" alt="langs" />
  <br />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Xeehho&theme=gruvbox" alt="repos" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Xeehho&theme=gruvbox&utc=8" alt="productive time" />
  <img src="assets/crafting.svg" width="44" alt="crafting" />
</p>

<img src="assets/divider-rich.svg" width="100%" alt="footer" />

<p align="center">
  <img src="assets/flower.svg" width="36" alt="flower" />
  <img src="assets/sheep.svg" width="36" alt="flower" />
  <img src="assets/flower.svg" width="36" alt="flower" />
</p>
