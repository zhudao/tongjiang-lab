# 铜匠实验室

[English](README.md) | 简体中文

**免费、可交互的高中科学 3D 实验课件，覆盖物理、化学、生物、地理。**

在线使用：**https://lab.tongjiang.app**

目前共 50 门。每门课都是**一个独立的 HTML 文件**，约 1 MB：双击就能打开，断网、投影、电子白板都能用。每门课是一个 3D 世界，配常驻中控台、主线问题和步骤条，老师按「下一步」就能从头讲到尾。

科学内容来自公开数据、原始文献和通用科学结论，全部文字和画面为本站原创；每门课附 NGSS* 编码和 OpenStax 参考章节（只给链接和章节名，不转载正文）。课件界面目前是中文，其他语言在计划中。

## 怎么用

- **在线**：点下面表格里的 **▶ 在线上课**。在 GitHub 上点开 HTML 文件只会显示代码，要看课件请用这些链接。
- **离线**：在 [Releases](https://github.com/smithjohn78390/tongjiang-lab/releases/latest) 下载全部课件的压缩包，或者在 https://lab.tongjiang.app 的课程页下载单门课，用 Chrome 或 Edge 打开。解压后打开 `courses/index.html` 就是离线目录，能浏览全部课程（`courses/` 与 `covers/` 两个文件夹要放在一起）。
- **嵌入**：`<iframe src="https://lab.tongjiang.app/<slug>" width="100%" style="aspect-ratio:16/9;border:0" allow="fullscreen"></iframe>`
- **数据**：[`catalog.json`](catalog.json) 列出每门课的 NGSS* 编码、OpenStax 章节和步骤。

## 课程

### 物理（10 门）

| 课程 | NGSS* · OpenStax | 步数 | 打开 | 源文件 |
|---|---|---|---|---|
| [光电效应](https://lab.tongjiang.app/c/photoelectric-step/) | [HS-PS4-3](https://www.nextgenscience.org/dci-arrangement/hs-ps4-waves-and-their-applications-technologies-information-transfer) · [Physics §21.2](https://openstax.org/books/physics/pages/21-2-einstein-and-the-photoelectric-effect) | 9 | [▶ 在线上课](https://lab.tongjiang.app/photoelectric-step) | [HTML](courses/photoelectric-step.html) |
| [观察电容器的充放电](https://lab.tongjiang.app/c/capacitor-step/) | [Physics §18.5](https://openstax.org/books/physics/pages/18-5-capacitors-and-dielectrics) | 9 | [▶ 在线上课](https://lab.tongjiang.app/capacitor-step) | [HTML](courses/capacitor-step.html) |
| [实验：探究加速度与力、质量的关系](https://lab.tongjiang.app/c/accel-force-step/) | [HS-PS2-1](https://www.nextgenscience.org/dci-arrangement/hs-ps2-motion-and-stability-forces-and-interactions) · [Physics §4.3](https://openstax.org/books/physics/pages/4-3-newtons-second-law-of-motion) | 8 | [▶ 在线上课](https://lab.tongjiang.app/accel-force-step) | [HTML](courses/accel-force-step.html) |
| [实验：验证机械能守恒定律](https://lab.tongjiang.app/c/energy-step/) | [HS-PS3-1](https://www.nextgenscience.org/dci-arrangement/hs-ps3-energy)<br>[HS-PS3-2](https://www.nextgenscience.org/dci-arrangement/hs-ps3-energy)<br>[Physics §9.2](https://openstax.org/books/physics/pages/9-2-mechanical-energy-and-conservation-of-energy) | 8 | [▶ 在线上课](https://lab.tongjiang.app/energy-step) | [HTML](courses/energy-step.html) |
| [实验：探究平抛运动的特点](https://lab.tongjiang.app/c/projectile-step/) | [HS-PS2-1](https://www.nextgenscience.org/dci-arrangement/hs-ps2-motion-and-stability-forces-and-interactions) · [Physics §5.3](https://openstax.org/books/physics/pages/5-3-projectile-motion) | 9 | [▶ 在线上课](https://lab.tongjiang.app/projectile-step) | [HTML](courses/projectile-step.html) |
| [向心力大小与半径、角速度及质量的关系](https://lab.tongjiang.app/c/centripetal-step/) | [HS-PS2-1](https://www.nextgenscience.org/dci-arrangement/hs-ps2-motion-and-stability-forces-and-interactions) · [Physics §6.2](https://openstax.org/books/physics/pages/6-2-uniform-circular-motion) | 8 | [▶ 在线上课](https://lab.tongjiang.app/centripetal-step) | [HTML](courses/centripetal-step.html) |
| [自感与涡流](https://lab.tongjiang.app/c/self-induction-step/) | [HS-PS2-5](https://www.nextgenscience.org/dci-arrangement/hs-ps2-motion-and-stability-forces-and-interactions)<br>[HS-PS3-5](https://www.nextgenscience.org/dci-arrangement/hs-ps3-energy)<br>[College Physics 2e §23.9](https://openstax.org/books/college-physics-2e/pages/23-9-inductance)<br>[College Physics 2e §23.4](https://openstax.org/books/college-physics-2e/pages/23-4-eddy-currents-and-magnetic-damping) | 9 | [▶ 在线上课](https://lab.tongjiang.app/self-induction-step) | [HTML](courses/self-induction-step.html) |
| [测电源电动势和内阻](https://lab.tongjiang.app/c/emf-step/) | [College Physics 2e §21.2](https://openstax.org/books/college-physics-2e/pages/21-2-electromotive-force-terminal-voltage) | 9 | [▶ 在线上课](https://lab.tongjiang.app/emf-step) | [HTML](courses/emf-step.html) |
| [电流的磁场](https://lab.tongjiang.app/c/current-field-step/) | [HS-PS2-5](https://www.nextgenscience.org/dci-arrangement/hs-ps2-motion-and-stability-forces-and-interactions) · [Physics §20.1](https://openstax.org/books/physics/pages/20-1-magnetic-fields-field-lines-and-force) | 9 | [▶ 在线上课](https://lab.tongjiang.app/current-field-step) | [HTML](courses/current-field-step.html) |
| [布朗运动与扩散](https://lab.tongjiang.app/c/brownian-step/) | [College Physics 2e §13.4](https://openstax.org/books/college-physics-2e/pages/13-4-kinetic-theory-atomic-and-molecular-explanation-of-pressure-and-temperature) | 9 | [▶ 在线上课](https://lab.tongjiang.app/brownian-step) | [HTML](courses/brownian-step.html) |

### 化学（25 门）

| 课程 | NGSS* · OpenStax | 步数 | 打开 | 源文件 |
|---|---|---|---|---|
| [合成氨工业](https://lab.tongjiang.app/c/haber-step/) | [HS-PS1-6](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions)<br>[HS-ETS1-3](https://www.nextgenscience.org/dci-arrangement/hs-ets1-engineering-design)<br>[Chemistry 2e §13.3](https://openstax.org/books/chemistry-2e/pages/13-3-shifting-equilibria-le-chateliers-principle) | 7 | [▶ 在线上课](https://lab.tongjiang.app/haber-step) | [HTML](courses/haber-step.html) |
| [化学反应速率的影响因素](https://lab.tongjiang.app/c/rate-step/) | [HS-PS1-5](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions) · [Chemistry 2e §12.2](https://openstax.org/books/chemistry-2e/pages/12-2-factors-affecting-reaction-rates) | 8 | [▶ 在线上课](https://lab.tongjiang.app/rate-step) | [HTML](courses/rate-step.html) |
| [搭建球棍模型 · 认识有机分子结构](https://lab.tongjiang.app/c/ball-stick-step/) | [Chemistry 2e §7.6](https://openstax.org/books/chemistry-2e/pages/7-6-molecular-structure-and-polarity)<br>[Chemistry 2e §20.1](https://openstax.org/books/chemistry-2e/pages/20-1-hydrocarbons) | 9 | [▶ 在线上课](https://lab.tongjiang.app/ball-stick-step) | [HTML](courses/ball-stick-step.html) |
| [强酸与强碱的中和滴定](https://lab.tongjiang.app/c/titration-step/) | [HS-PS1-7](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions)<br>[HS-PS1-6](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions)<br>[Chemistry 2e §14.7](https://openstax.org/books/chemistry-2e/pages/14-7-acid-base-titrations) | 9 | [▶ 在线上课](https://lab.tongjiang.app/titration-step) | [HTML](courses/titration-step.html) |
| [氯气的制备及性质](https://lab.tongjiang.app/c/chlorine-step/) | [HS-PS1-2](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions) · [Chemistry 2e §18.11](https://openstax.org/books/chemistry-2e/pages/18-11-occurrence-preparation-and-properties-of-halogens) | 9 | [▶ 在线上课](https://lab.tongjiang.app/chlorine-step) | [HTML](courses/chlorine-step.html) |
| [高炉炼铁](https://lab.tongjiang.app/c/blast-furnace-step/) | [HS-PS1-2](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions)<br>[HS-ETS1-3](https://www.nextgenscience.org/dci-arrangement/hs-ets1-engineering-design)<br>[Chemistry 2e §19.1](https://openstax.org/books/chemistry-2e/pages/19-1-occurrence-preparation-and-properties-of-transition-metals-and-their-compounds) | 8 | [▶ 在线上课](https://lab.tongjiang.app/blast-furnace-step) | [HTML](courses/blast-furnace-step.html) |
| [金属冶炼：电解熔融盐 + 铝热](https://lab.tongjiang.app/c/smelting-step/) | [HS-PS1-2](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions)<br>[HS-ETS1-3](https://www.nextgenscience.org/dci-arrangement/hs-ets1-engineering-design)<br>[Chemistry 2e §17.7](https://openstax.org/books/chemistry-2e/pages/17-7-electrolysis)<br>[Chemistry 2e §19.1](https://openstax.org/books/chemistry-2e/pages/19-1-occurrence-preparation-and-properties-of-transition-metals-and-their-compounds) | 8 | [▶ 在线上课](https://lab.tongjiang.app/smelting-step) | [HTML](courses/smelting-step.html) |
| [煤的综合利用：以煤的气化为主线](https://lab.tongjiang.app/c/coal-gas-step/) | — | 8 | [▶ 在线上课](https://lab.tongjiang.app/coal-gas-step) | [HTML](courses/coal-gas-step.html) |
| [接触法制硫酸](https://lab.tongjiang.app/c/sulfuric-step/) | [HS-PS1-6](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions)<br>[HS-ETS1-3](https://www.nextgenscience.org/dci-arrangement/hs-ets1-engineering-design) | 7 | [▶ 在线上课](https://lab.tongjiang.app/sulfuric-step) | [HTML](courses/sulfuric-step.html) |
| [盐类的水解及其应用](https://lab.tongjiang.app/c/hydrolysis-step/) | [Chemistry 2e §14.4](https://openstax.org/books/chemistry-2e/pages/14-4-hydrolysis-of-salts) | 9 | [▶ 在线上课](https://lab.tongjiang.app/hydrolysis-step) | [HTML](courses/hydrolysis-step.html) |
| [工业制水泥](https://lab.tongjiang.app/c/cement-step/) | — | 8 | [▶ 在线上课](https://lab.tongjiang.app/cement-step) | [HTML](courses/cement-step.html) |
| [铁及其化合物：铁的价态转化](https://lab.tongjiang.app/c/iron-step/) | [HS-PS1-2](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions) · [Chemistry 2e §19.1](https://openstax.org/books/chemistry-2e/pages/19-1-occurrence-preparation-and-properties-of-transition-metals-and-their-compounds) | 9 | [▶ 在线上课](https://lab.tongjiang.app/iron-step) | [HTML](courses/iron-step.html) |
| [电解原理：电解 CuCl₂ 溶液与饱和食盐水](https://lab.tongjiang.app/c/electrolysis-step/) | [HS-PS1-2](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions)<br>[HS-ETS1-3](https://www.nextgenscience.org/dci-arrangement/hs-ets1-engineering-design)<br>[Chemistry 2e §17.7](https://openstax.org/books/chemistry-2e/pages/17-7-electrolysis) | 9 | [▶ 在线上课](https://lab.tongjiang.app/electrolysis-step) | [HTML](courses/electrolysis-step.html) |
| [氨的制备与性质（含喷泉实验）](https://lab.tongjiang.app/c/ammonia-step/) | [HS-PS1-2](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions) · [Chemistry 2e §18.7](https://openstax.org/books/chemistry-2e/pages/18-7-occurrence-preparation-and-properties-of-nitrogen) | 9 | [▶ 在线上课](https://lab.tongjiang.app/ammonia-step) | [HTML](courses/ammonia-step.html) |
| [探究影响化学平衡移动的因素](https://lab.tongjiang.app/c/equilibrium-step/) | [HS-PS1-6](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions) · [Chemistry 2e §13.3](https://openstax.org/books/chemistry-2e/pages/13-3-shifting-equilibria-le-chateliers-principle) | 9 | [▶ 在线上课](https://lab.tongjiang.app/equilibrium-step) | [HTML](courses/equilibrium-step.html) |
| [焰色试验与原子光谱](https://lab.tongjiang.app/c/flame-step/) | [Chemistry 2e §6.2](https://openstax.org/books/chemistry-2e/pages/6-2-the-bohr-model)<br>[Chemistry 2e §6.1](https://openstax.org/books/chemistry-2e/pages/6-1-electromagnetic-energy) | 8 | [▶ 在线上课](https://lab.tongjiang.app/flame-step) | [HTML](courses/flame-step.html) |
| [原电池：单液到双液](https://lab.tongjiang.app/c/galvanic-step/) | [HS-PS3-3](https://www.nextgenscience.org/dci-arrangement/hs-ps3-energy)<br>[HS-PS1-2](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions)<br>[Chemistry 2e §17.2](https://openstax.org/books/chemistry-2e/pages/17-2-galvanic-cells) | 9 | [▶ 在线上课](https://lab.tongjiang.app/galvanic-step) | [HTML](courses/galvanic-step.html) |
| [电解质的电离与溶液导电性、离子反应的实质](https://lab.tongjiang.app/c/conductivity-step/) | [HS-PS1-3](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions) · [Chemistry 2e §11.2](https://openstax.org/books/chemistry-2e/pages/11-2-electrolytes) | 9 | [▶ 在线上课](https://lab.tongjiang.app/conductivity-step) | [HTML](courses/conductivity-step.html) |
| [浓稀硝酸的性质与氮氧化物的转化](https://lab.tongjiang.app/c/nitric-lab-step/) | [HS-PS1-2](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions) · [Chemistry 2e §18.7](https://openstax.org/books/chemistry-2e/pages/18-7-occurrence-preparation-and-properties-of-nitrogen) | 9 | [▶ 在线上课](https://lab.tongjiang.app/nitric-lab-step) | [HTML](courses/nitric-lab-step.html) |
| [海水提溴：空气吹出法](https://lab.tongjiang.app/c/bromine-step/) | [HS-PS1-2](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions)<br>[HS-ESS3-2](https://www.nextgenscience.org/dci-arrangement/hs-ess3-earth-and-human-activity)<br>[Chemistry 2e §18.11](https://openstax.org/books/chemistry-2e/pages/18-11-occurrence-preparation-and-properties-of-halogens) | 7 | [▶ 在线上课](https://lab.tongjiang.app/bromine-step) | [HTML](courses/bromine-step.html) |
| [金属钠的性质（含钠着火扑救）](https://lab.tongjiang.app/c/sodium-step/) | [HS-PS1-2](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions) · [Chemistry 2e §18.2](https://openstax.org/books/chemistry-2e/pages/18-2-occurrence-and-preparation-of-the-representative-metals) | 9 | [▶ 在线上课](https://lab.tongjiang.app/sodium-step) | [HTML](courses/sodium-step.html) |
| [硫、二氧化硫、浓硫酸的性质与不同价态含硫物质的转化](https://lab.tongjiang.app/c/sulfur-step/) | [HS-PS1-2](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions) · [Chemistry 2e §18.10](https://openstax.org/books/chemistry-2e/pages/18-10-occurrence-preparation-and-properties-of-sulfur) | 9 | [▶ 在线上课](https://lab.tongjiang.app/sulfur-step) | [HTML](courses/sulfur-step.html) |
| [吸氧腐蚀与暖贴的设计](https://lab.tongjiang.app/c/corrosion-step/) | [HS-PS1-2](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions)<br>[HS-ETS1-3](https://www.nextgenscience.org/dci-arrangement/hs-ets1-engineering-design)<br>[Chemistry 2e §17.6](https://openstax.org/books/chemistry-2e/pages/17-6-corrosion) | 9 | [▶ 在线上课](https://lab.tongjiang.app/corrosion-step) | [HTML](courses/corrosion-step.html) |
| [氯碱工业](https://lab.tongjiang.app/c/chlor-alkali-step/) | [HS-PS1-2](https://www.nextgenscience.org/dci-arrangement/hs-ps1-matter-and-its-interactions)<br>[HS-ETS1-3](https://www.nextgenscience.org/dci-arrangement/hs-ets1-engineering-design)<br>[Chemistry 2e §17.7](https://openstax.org/books/chemistry-2e/pages/17-7-electrolysis) | 8 | [▶ 在线上课](https://lab.tongjiang.app/chlor-alkali-step) | [HTML](courses/chlor-alkali-step.html) |
| [侯氏制碱](https://lab.tongjiang.app/c/hou-soda-step/) | — | 8 | [▶ 在线上课](https://lab.tongjiang.app/hou-soda-step) | [HTML](courses/hou-soda-step.html) |

### 生物（5 门）

| 课程 | NGSS* · OpenStax | 步数 | 打开 | 源文件 |
|---|---|---|---|---|
| [植物细胞的吸水和失水](https://lab.tongjiang.app/c/plasmolysis-step/) | [Biology 2e §30.5](https://openstax.org/books/biology-2e/pages/30-5-transport-of-water-and-solutes-in-plants)<br>[Biology 2e §5.2](https://openstax.org/books/biology-2e/pages/5-2-passive-transport) | 8 | [▶ 在线上课](https://lab.tongjiang.app/plasmolysis-step) | [HTML](courses/plasmolysis-step.html) |
| [物质跨膜运输](https://lab.tongjiang.app/c/transport-step/) | [Biology 2e §5.2](https://openstax.org/books/biology-2e/pages/5-2-passive-transport)<br>[Biology 2e §5.3](https://openstax.org/books/biology-2e/pages/5-3-active-transport) | 8 | [▶ 在线上课](https://lab.tongjiang.app/transport-step) | [HTML](courses/transport-step.html) |
| [神经冲动的产生和传导](https://lab.tongjiang.app/c/impulse-step/) | [Biology 2e §35.2](https://openstax.org/books/biology-2e/pages/35-2-how-neurons-communicate) | 9 | [▶ 在线上课](https://lab.tongjiang.app/impulse-step) | [HTML](courses/impulse-step.html) |
| [根尖分生区细胞的有丝分裂](https://lab.tongjiang.app/c/mitosis-step/) | [HS-LS1-4](https://www.nextgenscience.org/dci-arrangement/hs-ls1-molecules-organisms-structures-and-processes) · [Biology 2e §10.2](https://openstax.org/books/biology-2e/pages/10-2-the-cell-cycle) | 9 | [▶ 在线上课](https://lab.tongjiang.app/mitosis-step) | [HTML](courses/mitosis-step.html) |
| [影响酶活性的条件](https://lab.tongjiang.app/c/enzyme-step/) | [Biology 2e §6.5](https://openstax.org/books/biology-2e/pages/6-5-enzymes) | 8 | [▶ 在线上课](https://lab.tongjiang.app/enzyme-step) | [HTML](courses/enzyme-step.html) |

### 地理（10 门）

| 课程 | NGSS* · OpenStax | 步数 | 打开 | 源文件 |
|---|---|---|---|---|
| [河流地貌的发育](https://lab.tongjiang.app/c/river-step/) | [HS-ESS2-5](https://www.nextgenscience.org/dci-arrangement/hs-ess2-earths-systems)<br>[HS-ESS2-1](https://www.nextgenscience.org/dci-arrangement/hs-ess2-earths-systems) | 8 | [▶ 在线上课](https://lab.tongjiang.app/river-step) | [HTML](courses/river-step.html) |
| [海—气相互作用与厄尔尼诺、拉尼娜](https://lab.tongjiang.app/c/enso-step/) | [MS-ESS2-6](https://www.nextgenscience.org/dci-arrangement/ms-ess2-earths-systems) | 7 | [▶ 在线上课](https://lab.tongjiang.app/enso-step) | [HTML](courses/enso-step.html) |
| [大气受热过程](https://lab.tongjiang.app/c/heating-step/) | [HS-ESS2-4](https://www.nextgenscience.org/dci-arrangement/hs-ess2-earths-systems) | 9 | [▶ 在线上课](https://lab.tongjiang.app/heating-step) | [HTML](courses/heating-step.html) |
| [喀斯特地貌的形成与识别](https://lab.tongjiang.app/c/karst-step/) | [HS-ESS2-5](https://www.nextgenscience.org/dci-arrangement/hs-ess2-earths-systems)<br>[HS-ESS2-2](https://www.nextgenscience.org/dci-arrangement/hs-ess2-earths-systems) | 7 | [▶ 在线上课](https://lab.tongjiang.app/karst-step) | [HTML](courses/karst-step.html) |
| [全球气候变化与国家安全](https://lab.tongjiang.app/c/carbon-step/) | [HS-ESS3-5](https://www.nextgenscience.org/dci-arrangement/hs-ess3-earth-and-human-activity)<br>[HS-ESS2-6](https://www.nextgenscience.org/dci-arrangement/hs-ess2-earths-systems)<br>[Biology 2e §44.5](https://openstax.org/books/biology-2e/pages/44-5-climate-and-the-effects-of-global-climate-change) | 8 | [▶ 在线上课](https://lab.tongjiang.app/carbon-step) | [HTML](courses/carbon-step.html) |
| [构造地貌的形成](https://lab.tongjiang.app/c/tectonic-step/) | [HS-ESS2-1](https://www.nextgenscience.org/dci-arrangement/hs-ess2-earths-systems)<br>[HS-ESS1-5](https://www.nextgenscience.org/dci-arrangement/hs-ess1-earths-place-universe) | 6 | [▶ 在线上课](https://lab.tongjiang.app/tectonic-step) | [HTML](courses/tectonic-step.html) |
| [土壤的形成因素与剖面观察](https://lab.tongjiang.app/c/soil-step/) | [Biology 2e §31.2](https://openstax.org/books/biology-2e/pages/31-2-the-soil) | 8 | [▶ 在线上课](https://lab.tongjiang.app/soil-step) | [HTML](courses/soil-step.html) |
| [大气热力环流](https://lab.tongjiang.app/c/thermal-step/) | [MS-ESS2-6](https://www.nextgenscience.org/dci-arrangement/ms-ess2-earths-systems) | 9 | [▶ 在线上课](https://lab.tongjiang.app/thermal-step) | [HTML](courses/thermal-step.html) |
| [大气的水平运动——风](https://lab.tongjiang.app/c/wind-step/) | [MS-ESS2-6](https://www.nextgenscience.org/dci-arrangement/ms-ess2-earths-systems) | 8 | [▶ 在线上课](https://lab.tongjiang.app/wind-step) | [HTML](courses/wind-step.html) |
| [水循环的过程与地理意义](https://lab.tongjiang.app/c/water-cycle-step/) | [MS-ESS2-4](https://www.nextgenscience.org/dci-arrangement/ms-ess2-earths-systems) · [Biology 2e §46.3](https://openstax.org/books/biology-2e/pages/46-3-biogeochemical-cycles) | 9 | [▶ 在线上课](https://lab.tongjiang.app/water-cycle-step) | [HTML](courses/water-cycle-step.html) |

## 许可

- 课件、封面与目录按 **[CC BY-NC 4.0](LICENSE)** 授权：可以免费使用、分享和修改，须署名「铜匠实验室（https://lab.tongjiang.app）」，不得用于商业用途。
- 课件里打包的第三方代码和字体（three.js，MIT；Noto Sans SC、Inter，SIL OFL 1.1）保留其原有许可，见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。
- 部分课件里的 3D 模型由 Tripo AI 生成。

## 作者

**铜匠十点睡觉**，做 3D 可视化：课件、数字孪生、工厂与设备演示。
关注 X：[@CopperForgeAI](https://x.com/CopperForgeAI)。发现错误欢迎提 Issue，或在 X 私信。

## 商标

*NGSS 是 WestEd 的注册商标。WestEd 及制定《下一代科学标准》的牵头州与合作方均未参与本站制作，也不为本站背书。

章节链接指向 OpenStax（莱斯大学）免费教材，仅供参考；本站与 OpenStax 无关联。

*NGSS is a registered trademark of WestEd. Neither WestEd nor the lead states and partners that developed the Next Generation Science Standards were involved in the production of this product, and do not endorse it.
