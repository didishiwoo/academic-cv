---
title: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: |-
        安徽医科大学生物医学工程专业本科生（专业排名 11/119，GPA 3.57，四级 519/六级 488），具备一定的模拟电路调试、嵌入式开发与电磁场仿真基础。

        **科研经历**：以第一作者身份在 IEEE EMBC 2025 国际会议作口头报告。主要利用磁共振多模态图像数据，在 COMSOL 软件中构建了个性化的头部各向异性电导率模型，并完成了相应的脑部电磁场有限元仿真量化分析。

        **硬件开发**：主持一项省级大创项目，设计并调试了一款四通道脑刺激仪样机（基于增强型霍兰德恒流源电路，输出频率 1–100 kHz，电流范围0-5ma，误差 ≤ 1% ），实现了基于 STM32 的信号时序控制与阻抗监测。

        **竞赛经历**：曾获全国大学生电赛省级二等奖、全国大学生生物医学工程创新设计竞赛全国二等奖、大学生物理实验竞赛国家级二等奖。
      button:
        text: 下载简历
        url: uploads/resume.pdf
      headings:
        about: 个人简介
      design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
  - block: markdown
    id: research
    content:
      title: '科研经历'
      text: |-
        <div class="research-entry">
          <div class="research-title">1）基于磁共振电导率张量成像对时域干涉刺激仿真进行优化</div>
          <div class="research-date">2024.09 – 2025.07</div>
          <div class="research-desc">

        **内容**：针对时域干涉刺激（TIS）仿真中传统各向同性电导率模型精度不足的问题，融合磁共振电导率成像与弥散张量成像构建个性化各向异性电导率模型，并在 COMSOL 中进行有限元仿真

        **负责工作**：
          - 提出创新点：将 NODDI 模型引入 TIS 电导率建模，在神经突密度、定向分散度、细胞外体积分数等微结构参数中重构各向异性电导率张量
          - 在 COMSOL 中构建三种电导率模型，设置 5 种 10-10 电极系统配置进行 TIS 电场仿真
          - 手稿撰写

        **所获成果**：在 IEEE EMBC 2025 国际会议（丹麦·哥本哈根）进行 **口头报告（Oral presentation）**
          </div>
        </div>

        <div class="research-entry">
          <div class="research-title">2）智控脑阈：个性化经颅时域干涉刺激系统的研制（省级大创，项目负责人）</div>
          <div class="research-date">2025.06 – 2026.05</div>
          <div class="research-desc">

        **内容**：研制一套四通道经颅时域干涉刺激系统，实现 1–100kHz、0–5 mA、精度 ≤ 1% 的高精度恒流输出

        **负责工作**：
          - **硬件设计**：设计增强型 Howland 压控恒流源，实现 4 通道、1–100kHz、0–5 mA 的刺激输出，电流控制误差 ≤ 1%
          - **STM32 固件开发**：基于 IIC 总线实现主控板与刺激板间通信，通过 ADC 实时采样实现电流闭环控制与阻抗监测
          - **上位机开发**：基于 PySide6 编写上位机软件，完成联合调试与样机封装

        **所获成果**：完成样机研制并提交一项软件著作权申请
          </div>
        </div>
    design:
      columns: '1'
  - block: markdown
    id: current-work
    content:
      title: '当前参与研究内容'
      text: |-
        <div class="research-entry">
          <div class="research-title">1）时域干涉刺激仪的磁共振兼容性改造</div>
          <div class="research-date">2026.01 – 至今</div>
          <div class="research-desc">

        正在尝试对大创项目研制的四通道时域干涉刺激仪进行磁共振兼容性的初步硬件改造与电磁屏蔽设计。计划在本科毕业前，完成该刺激仪在磁共振电磁环境下的兼容性评估与基础射频测试，重点熟悉高频信号的抗干扰处理与屏蔽技术，为后续研究生阶段的科研工作打好基础。
          </div>
        </div>

        <div class="research-entry">
          <div class="research-title">2）NeuronWave 睡眠波：头戴式便携 EEG 脑电采集与 CES 电刺激助眠系统</div>
          <div class="research-date">2026.01 – 至今</div>
          <div class="research-desc">

        研发一款放置于前额的便携式头戴设备，集成 EEG 脑电信号采集与 CES 经颅电刺激功能，实现睡眠阶段的实时检测与闭环电刺激干预，以达到智能助眠的效果。
          </div>
        </div>
    design:
      columns: '1'
  - block: markdown
    id: awards
    content:
      title: '荣誉奖项'
      text: |-
        <div class="awards-wrapper">
          <ul class="award-list">
            <li><strong>全国大学生生物医学工程创新设计竞赛 全国二等奖</strong>（中国生物医学工程学会，2025）—— 作品"眼周经络电脉冲治疗仪（E-MASK）"，集成 AI 智能医疗辅助诊断系统</li>
            <li><strong>全国大学生电子设计竞赛 省级二等奖</strong>（教育部，2025）—— 电路模型探究装置（G题），实现 FFT 频谱分析与数字锁相放大器算法</li>
            <li><strong>全国大学生物理实验竞赛 全国二等奖</strong>（全国大学生物理实验竞赛组委会，2025）—— "电介质极化：微观世界的极化竞赛"：实验设计与 C4D 三维可视化</li>
            <li><strong>张锡祺一等奖学金</strong>（安徽医科大学，2024、2025）—— 连续两年获校级一等奖学金</li>
            <li><strong>"挑战杯"竞赛 校级一等奖</strong>（安徽医科大学，2026）—— 作品"NeuronWave 睡眠波"：放置于前额的便携式 EEG 脑电检测与 CES 电刺激助眠系统</li>
          </ul>
        </div>
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: 论文
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation
      columns: 1
  - block: markdown
    content:
      title: '兴趣爱好'
      text: |-
        <div class="photo-gallery">

        <p class="photo-gallery-intro">热爱摄影，习惯用镜头记录旅途中的风景与人文</p>

        <div class="photo-location">
          <h4 class="photo-location-title">安徽 · 黄山</h4>
          <div class="photo-grid">
            <a href="/photography/huangshan/DSC_7024-1.jpg" target="_blank" class="photo-item" title="黄山">
              <img src="/photography/huangshan/DSC_7024-1.jpg" alt="黄山" loading="lazy" />
            </a>
            <a href="/photography/huangshan/DSC_7032-1.jpg" target="_blank" class="photo-item" title="黄山">
              <img src="/photography/huangshan/DSC_7032-1.jpg" alt="黄山" loading="lazy" />
            </a>
            <a href="/photography/huangshan/DSC_7125-1.jpg" target="_blank" class="photo-item" title="黄山">
              <img src="/photography/huangshan/DSC_7125-1.jpg" alt="黄山" loading="lazy" />
            </a>
            <a href="/photography/huangshan/DSC_7133-1.jpg" target="_blank" class="photo-item" title="黄山">
              <img src="/photography/huangshan/DSC_7133-1.jpg" alt="黄山" loading="lazy" />
            </a>
          </div>
        </div>

        <div class="photo-location">
          <h4 class="photo-location-title">福建 · 平潭岛</h4>
          <div class="photo-grid">
            <a href="/photography/pingtan/2025-0568.jpg" target="_blank" class="photo-item" title="平潭岛">
              <img src="/photography/pingtan/2025-0568.jpg" alt="平潭岛" loading="lazy" />
            </a>
            <a href="/photography/pingtan/2025-0697.jpg" target="_blank" class="photo-item" title="平潭岛">
              <img src="/photography/pingtan/2025-0697.jpg" alt="平潭岛" loading="lazy" />
            </a>
            <a href="/photography/pingtan/2025-0928.jpg" target="_blank" class="photo-item" title="平潭岛">
              <img src="/photography/pingtan/2025-0928.jpg" alt="平潭岛" loading="lazy" />
            </a>
          </div>
        </div>

        <div class="photo-location">
          <h4 class="photo-location-title">湖北 · 武汉</h4>
          <div class="photo-grid">
            <a href="/photography/wuhan/DSC_3460-2.jpg" target="_blank" class="photo-item" title="武汉">
              <img src="/photography/wuhan/DSC_3460-2.jpg" alt="武汉" loading="lazy" />
            </a>
            <a href="/photography/wuhan/DSC_3564-21.jpg" target="_blank" class="photo-item" title="武汉">
              <img src="/photography/wuhan/DSC_3564-21.jpg" alt="武汉" loading="lazy" />
            </a>
            <a href="/photography/wuhan/DSC_3646-21.jpg" target="_blank" class="photo-item" title="武汉">
              <img src="/photography/wuhan/DSC_3646-21.jpg" alt="武汉" loading="lazy" />
            </a>
            <a href="/photography/wuhan/Image_1779285029567.jpg" target="_blank" class="photo-item" title="武汉">
              <img src="/photography/wuhan/Image_1779285029567.jpg" alt="武汉" loading="lazy" />
            </a>
          </div>
        </div>

        <div class="photo-location">
          <h4 class="photo-location-title">合肥 · 逍遥津</h4>
          <div class="photo-grid">
            <a href="/photography/hefei/000004.jpg" target="_blank" class="photo-item" title="逍遥津">
              <img src="/photography/hefei/000004.jpg" alt="逍遥津" loading="lazy" />
            </a>
            <a href="/photography/hefei/000006.jpg" target="_blank" class="photo-item" title="逍遥津">
              <img src="/photography/hefei/000006.jpg" alt="逍遥津" loading="lazy" />
            </a>
            <a href="/photography/hefei/000042.jpg" target="_blank" class="photo-item" title="逍遥津">
              <img src="/photography/hefei/000042.jpg" alt="逍遥津" loading="lazy" />
            </a>
            <a href="/photography/hefei/000048.jpg" target="_blank" class="photo-item" title="逍遥津">
              <img src="/photography/hefei/000048.jpg" alt="逍遥津" loading="lazy" />
            </a>
            <a href="/photography/hefei/000049.jpg" target="_blank" class="photo-item" title="逍遥津">
              <img src="/photography/hefei/000049.jpg" alt="逍遥津" loading="lazy" />
            </a>
          </div>
        </div>

        </div>
    design:
      columns: '1'
      spacing:
        padding: ['2rem', 0, '2rem', 0]
---
