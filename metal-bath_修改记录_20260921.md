# metal-bath-manual 网站 · 修改记录（2026-09-21）

> 仓库：`jingjingblackpink/metal-bath-manual`（GitHub Pages，`main` 分支 `/docs` 目录部署）
> 站点：https://jingjingblackpink.github.io/metal-bath-manual/
> 本次共 2 次提交（`4b4dc8d`、`4122fd1`），均已推送并线上验证生效。
> 参考做法：本地《爱津_修改记录_20260921.md》与 `爱津涡旋仪\` 文件夹（aijin_Manual 站点双语化方案）
> 入口二维码：`46二维码.bmp`（全程未改动二维码图片及其指向链接，扫码仍直达中文首页，无需重新印刷）

---

## 修改一：新增三个英文版产品手册页面

**提交：`4b4dc8d` style: 新增英文版页面并添加中英文切换按钮**

新建 `docs/index_en.html`、`docs/intro_en.html`、`docs/manual_en.html` 三个页面，风格与中文版（`index.html` / `intro.html` / `manuals.html`）完全一致，共用同一份 `style.css`，仅将中文文案替换为英文，页面内链接均指向英文版页面。

### 1. 英文版首页 `index_en.html`

| 位置 | 中文版（原文） | 英文版（本次新增） |
|------|------|------|
| 页面标题 | B5 MAX 金属浴 · 产品手册 | **B5 MAX Metal Bath · Product Manual** |
| 顶部大标题 | B5 MAX 金属浴（h1，26px） | **B5 MAX Metal Bath**（h1，内联 22px，与爱津英文首页做法一致） |
| 副标题 | 智能金属浴加热制冷仪器 · B5 MAX | **Smart Heating & Cooling Metal Bath · B5 MAX** |
| 欢迎语 | 欢迎扫码访问，请选择： | **Welcome! Please scan the QR code to access the following options:** |
| 按钮一标题 | 产品简介 | **Product Introduction** |
| 按钮一副标题 | 了解产品特点与参数 | **Learn about the product features and specifications** |
| 按钮二标题 | 产品说明书下载 | **Product Manual Download** |
| 按钮二副标题 | 中文版 / 英文版 在线预览与下载 | **Online preview and download of the Chinese / English versions** |
| 页脚品牌名 | B5 MAX 金属浴 · 加热制冷 | **B5 MAX Metal Bath · Heating & Cooling**（英文页不出现中文字符） |
| 页脚提示行 | 扫描二维码 · 随时查阅产品说明书 | **Scan the QR code · Access the product manual anytime** |
| 右上角版本标识 | 说明书版本V1.0 / 时间：2026年9月10日 | **Manual Version: V1.0 / Date: September 10, 2026** |
| 页面内链接 | intro.html / manuals.html | 指向 **intro_en.html / manual_en.html** |

### 2. 英文版简介页 `intro_en.html`

| 位置 | 中文版（原文） | 英文版（本次新增） |
|------|------|------|
| 页面标题 | 产品简介 · B5 MAX 金属浴 | **Product Introduction · B5 MAX Metal Bath** |
| 返回栏 | ‹ 返回首页 / 产品简介 | **‹ Back to Home / Product Introduction** |
| 卡片一标题 | B5 MAX 智能金属浴（加热制冷型） | **B5 MAX Smart Metal Bath (Heating & Cooling)** |
| 产品描述 | B5 MAX —— 面向实验室的高精度加热制冷金属浴，采用双闭环级联 PID 温控与模块化设计，为分子生物学实验提供稳定可靠的温度环境。 | **B5 MAX — a high-precision heating & cooling metal bath for laboratories. It features dual closed-loop cascade PID temperature control and a modular design, providing a stable and reliable temperature environment for molecular biology experiments.** |
| 特性 1 | 双闭环级联 PID 智能温控，控温精度 ±0.1°C | **Dual closed-loop cascade PID temperature control with ±0.1°C accuracy** |
| 特性 2 | 加热制冷一体，温控范围 4~100°C | **Integrated heating and cooling, temperature range 4~100°C** |
| 特性 3 | 三档升降温速率可选（基础 / 高速 / 极限模式） | **Three selectable heating/cooling rate modes (Basic / High-speed / Ultimate)** |
| 特性 4 | 7 寸 DGUS 串口触摸屏，操作直观简便 | **7-inch DGUS serial touch screen, intuitive and easy to operate** |
| 特性 5 | 50 组程控程序（每组最多 10 步），断电不丢失 | **50 programmable groups (up to 10 steps each), retained after power failure** |
| 特性 6 | 运行曲线实时显示，最多 12800 个数据点，支持 USB 数据导出 | **Real-time running curve with up to 12,800 data points, USB data export supported** |
| 卡片二 | 技术参数（10 行参数表） | **Technical Specifications**：Temperature Range 4°C ~ 100°C / Temperature Accuracy ±0.1°C / Temperature Uniformity ±0.3°C / Heating Rate Approx. 2 / 5 / >5 °C/min (3 modes) / Cooling Rate ≥0.5 / ≥1 / ≥2 °C/min (3 modes) / Timer Range 1 min ~ 99 h 59 min / Program Capacity 50 groups × 10 steps each / Display 7-inch DGUS touch screen / Input Power 150 W / Dimensions 260×195×170 mm（数据与中文版完全一致） |
| 卡片三标题 | 查看完整说明书 | **View the Complete Manual** |
| 卡片三说明 | 如需查看详细操作说明，请下载中英文版产品说明书。 | **For detailed operating instructions, please download the product manual.** |
| 卡片三按钮 | 产品说明书下载 / 中文版 / 英文版 | **Product Manual Download / Chinese Version / English Version** |
| 页脚 | 同中文首页 | 同英文首页（B5 MAX Metal Bath · Heating & Cooling） |
| 页面内链接 | index.html / manuals.html | 指向 **index_en.html / manual_en.html** |

### 3. 英文版说明书页 `manual_en.html`

| 位置 | 中文版（原文） | 英文版（本次新增） |
|------|------|------|
| 页面标题 | 产品说明书下载 · B5 MAX 金属浴 | **Product Manual Download · B5 MAX Metal Bath** |
| 返回栏 | ‹ 返回首页 / 产品说明书 | **‹ Back to Home / Product Manual** |
| 卡片一角标 | 中 | **ZH**（英文页面不出现中文字符） |
| 卡片一标题 | 中文版产品说明书 | **Chinese Product Manual** |
| 卡片一副标题 | B5 MAX 智能金属浴使用说明书（中文）· PDF 1.94 MB | **B5 MAX Smart Metal Bath User Manual (Chinese) · PDF 1.94 MB** |
| 卡片一按钮 | 在线预览 / 下载 PDF | **Preview Online / Download PDF**（仍指向 B5_MAX_Metal_Bath_Manual_zh.pdf） |
| 卡片二标题 | 英文版产品说明书 | **English Product Manual** |
| 卡片二副标题 | B5 MAX Intelligent Metal Bath User Manual · PDF 1.97 MB | 保持不变 |
| 卡片二按钮 | 在线预览 / 下载 PDF | **Preview Online / Download PDF**（仍指向 B5_MAX_Metal_Bath_Manual_en.pdf） |
| 提示行 | 提示：点击「在线预览」可在浏览器中直接查看；点击「下载 PDF」可保存到本地。 | **Note: Click 「Preview Online」 to view the manual directly in your browser. Click 「Download PDF」 to save it to your device.**（引号沿用「」风格，与爱津优化后一致） |
| 页脚 | 同中文首页 | 同英文首页 |
| 页面内链接 | index.html | 指向 **index_en.html** |

---

## 修改二：中文首页左上角添加中英文切换按钮

| 文件 | 修改内容 |
|------|----------|
| `index.html` | 左上角新增「**EN · English**」按钮，点击跳转英文首页 `index_en.html`（原有内容除该按钮与 CSS 引用版本号外均未改动） |
| `index_en.html` | 左上角对应「**中文 · Chinese**」按钮，点击切回中文首页 `index.html` |
| `style.css` | 新增 `.lang-switch` 样式（固定于页面左上角，半透明白底圆角小标签，与右上角版本标识风格呼应，不遮挡顶部内容；与爱津站点同款） |

### 说明

- 中文版 `index.html`、`intro.html`、`manuals.html` 原有内容除新增按钮与 CSS 版本号外**均未改动**，中文版仍是扫码默认打开的状态。
- 切换按钮位于两个首页（`index.html` / `index_en.html`）；英文版子页面通过「Back to Home」返回英文首页后再切换。
- **二维码图片未做任何改动**（含 `46二维码.bmp` 与仓库内 `B5_MAX二维码_首页.bmp`），扫码指向地址不变，无需重新印刷。
- PDF 文件（20260910 版）及站点文件名均未改动，英文页与中文版共用同一对 PDF 文件。

---

## 修改三：CSS 版本号同步升级（缓存约定）

本次 `style.css` 有改动（新增 `.lang-switch`），按 2026-09-09 会话确立的缓存约定（「今后每次修改 style.css 时，需同步更新 `?v=` 版本号」），全部 **6 个** HTML 页面的 CSS 引用统一由 `style.css?v=20260908` 升级为 **`style.css?v=20260921`**（含未改版式的 `intro.html` / `manuals.html`），确保缓存了旧 CSS 的设备（含已扫码的手机）下次打开自动拉取新样式，语言按钮正常显示，无需手动清缓存。

```diff
- <link rel="stylesheet" href="style.css?v=20260908">
+ <link rel="stylesheet" href="style.css?v=20260921">
```

---

## 修改四：修改记录文档追加本次会话

**提交：`4122fd1` docs: 修改记录追加20260921会话**

仓库根《metal-bath-manual网站修改记录.md》追加「十、2026年9月21日会话」一节，本地工作目录同名副本已同步更新（两者内容一致）。

---

## 修改五：中英文首页页脚添加公司名称

**提交：`cefee82` docs: 中英文首页页脚添加公司名称**

| 文件 | 修改内容 |
|------|----------|
| `index.html` | 页脚新增第三行「**上海泉心品生物科技有限公司**」（位于「扫描二维码 · 随时查阅产品说明书」下方） |
| `index_en.html` | 页脚新增第三行「**Shanghai Quanxinpin Biotechnology Co., Ltd.**」（位于「Scan the QR code · Access the product manual anytime」下方） |

### 说明

- 仅改动两个首页（`index.html` / `index_en.html`）的页脚，其余页面（intro / manuals / intro_en / manual_en）、`style.css`、PDF、二维码均未改动。
- `style.css` 本次无改动，CSS 引用版本号保持 `?v=20260921` 不变，无缓存风险。
- **二维码图片未做任何改动**，扫码指向地址不变，无需重新印刷。
- 仓库根《metal-bath-manual网站修改记录.md》同步追加 10.6 节（提交 `07ec7ef`）；本文档（`metal-bath_修改记录_20260921.md`）亦已提交至仓库根目录，与《metal-bath-manual网站修改记录.md》并存。

---

## 修改六：中英文子页面页脚添加公司名称

**提交：`02f5aef` docs: 中英文子页面页脚添加公司名称**

| 文件 | 修改内容 |
|------|----------|
| `intro.html` | 页脚新增第三行「**上海泉心品生物科技有限公司**」 |
| `manuals.html` | 页脚新增第三行「**上海泉心品生物科技有限公司**」 |
| `intro_en.html` | 页脚新增第三行「**Shanghai Quanxinpin Biotechnology Co., Ltd.**」 |
| `manual_en.html` | 页脚新增第三行「**Shanghai Quanxinpin Biotechnology Co., Ltd.**」 |

### 说明

- 至此全部 **6 个页面**页脚均含公司名称（中文页：上海泉心品生物科技有限公司；英文页：Shanghai Quanxinpin Biotechnology Co., Ltd.）。
- 仅页脚各新增一行，其余内容、`style.css`、PDF、二维码均未改动；CSS 无改动故 `?v=20260921` 保持不变。
- **二维码图片未做任何改动**，扫码指向地址不变，无需重新印刷。

---

## 线上验证（2026-09-21）

| 页面 | 网址 | 验证结果 |
|------|------|----------|
| 英文首页 | https://jingjingblackpink.github.io/metal-bath-manual/index_en.html | ✓ 200 OK，全部英文文案生效，「中文 · Chinese」切换按钮正常，页脚公司名称「Shanghai Quanxinpin Biotechnology Co., Ltd.」已生效 |
| 英文简介页 | https://jingjingblackpink.github.io/metal-bath-manual/intro_en.html | ✓ 200 OK，全部英文文案生效，参数表数据一致，页脚公司名称已生效 |
| 英文说明书页 | https://jingjingblackpink.github.io/metal-bath-manual/manual_en.html | ✓ 200 OK，全部英文文案生效，PDF 链接不变（1.94 / 1.97 MB 文案正确），页脚公司名称已生效 |
| 中文首页 | https://jingjingblackpink.github.io/metal-bath-manual/ | ✓ 200 OK，左上角已显示「EN · English」按钮，页脚公司名称「上海泉心品生物科技有限公司」已生效，其余内容无改动 |
| 中文简介页 | https://jingjingblackpink.github.io/metal-bath-manual/intro.html | ✓ 200 OK，CSS 引用已升级 v=20260921，无旧参数残留，页脚公司名称已生效 |
| 中文说明书页 | https://jingjingblackpink.github.io/metal-bath-manual/manuals.html | ✓ 200 OK，CSS 引用已升级 v=20260921，无旧参数残留，页脚公司名称已生效 |
| style.css | https://jingjingblackpink.github.io/metal-bath-manual/style.css | ✓ 200 OK，已含 `.lang-switch` 新样式 |

> 注：GitHub Pages CDN 缓存最长 10 分钟（`Cache-Control: max-age=600`），推送后个别页面若短暂显示旧内容，刷新或等待几分钟即可。

---

## 当前网站整体状态

| 项目 | 内容 |
|------|------|
| 二维码图片 | `46二维码.bmp` 等本地 5 个二维码文件及仓库内 `B5_MAX二维码_首页.bmp` 均未改动，扫码仍直达中文首页 |
| 中文首页 | https://jingjingblackpink.github.io/metal-bath-manual/ （左上角可切换英文） |
| 中文简介页 | https://jingjingblackpink.github.io/metal-bath-manual/intro.html |
| 中文说明书页 | https://jingjingblackpink.github.io/metal-bath-manual/manuals.html |
| 英文首页 | https://jingjingblackpink.github.io/metal-bath-manual/index_en.html （左上角可切回中文） |
| 英文简介页 | https://jingjingblackpink.github.io/metal-bath-manual/intro_en.html |
| 英文说明书页 | https://jingjingblackpink.github.io/metal-bath-manual/manual_en.html |
| 中文版 PDF | `B5_MAX_Metal_Bath_Manual_zh.pdf`（52 页 / 1.94 MB，20260910 版，中英文页面共用） |
| 英文版 PDF | `B5_MAX_Metal_Bath_Manual_en.pdf`（44 页 / 1.97 MB，20260910 版，中英文页面共用） |
| 品牌名 | 中文版：B5 MAX 金属浴 · 加热制冷；英文版：B5 MAX Metal Bath · Heating & Cooling |
| 版本标识 | 中文首页：说明书版本V1.0 · 时间：2026年9月10日；英文首页：Manual Version: V1.0 · Date: September 10, 2026（均在右上角） |
| 语言切换 | 两个首页左上角：中文页「EN · English」⇄ 英文页「中文 · Chinese」 |
| 公司名称 | 全部 6 个页面页脚第三行：中文页（index / intro / manuals）上海泉心品生物科技有限公司；英文页（index_en / intro_en / manual_en）Shanghai Quanxinpin Biotechnology Co., Ltd. |
| CSS 版本 | `style.css?v=20260921`（全部 6 个 HTML 页面统一引用） |

### 本次提交历史（含此前会话）

```
02f5aef  docs: 中英文子页面页脚添加公司名称
d5fca0a  docs: 20260921修改记录提交历史补充文档入库提交号
aa64570  docs: 新增20260921修改记录文档至仓库
07ec7ef  docs: 修改记录补充中英文首页页脚公司名称
cefee82  docs: 中英文首页页脚添加公司名称
4122fd1  docs: 修改记录追加20260921会话
4b4dc8d  style: 新增英文版页面并添加中英文切换按钮
7276cbc  docs: 修改记录追加20260910会话(PDF更新至20260910版)
6dac2f2  docs: 版本戳时间更新为2026年9月10日
cfe8a1a  docs: 更新中英文说明书PDF至20260910版
f886856  docs: 添加网站修改记录文档(20260909)
dc7db31  docs: 版本戳时间更新为2026年9月9日
e75d804  fix: CSS引用加版本号参数强制刷新缓存
5845afb  style: 参考涡旋仪风格重构首页/简介/下载页前端界面
c3a6b0e  docs: 更新中英文说明书PDF至20260908版
7c5a106  docs: 更正二维码使用说明(仓库/URL/文件清单)
fe73a31  B5 MAX 金属浴产品手册 (覆盖部署到 metal-bath-manual)
```

推送均使用 Windows 凭据管理器中已保存的 GitHub 凭据，未在任何命令或仓库中暴露 Token。
