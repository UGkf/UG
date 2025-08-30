<div align="center">
<!-- logo -->
<p align="center">
  <img src="docs/image/UG-logo.png" width="100px" style="vertical-align:middle;">
</p>

<!-- language -->
[English](README.md) | [简体中文](README_zh-CN.md)
<br>
<br>
🚀<a href="http://ughelper.huiqi-service.cn/#/login">模具开发平台 官网入口→✅ 在线使用 ✅ 全功能客户端 ✅ UG二次开发交流社区讨论，速冲！</a>
</div>

# 📋 更新记录

  2025/08/29 1.2.0发布
  
- 平台根据用户反馈，为了提升用户体验进行了如下更新： 
- 工具箱页面： 
  - 将主要功能拆解为各个工具箱，用户可以选择特定工具解决相应问题。
- 交流论坛优化：
  - 优化用户交流论坛的使用，优化交流论坛的视觉感官，优化用户提问回复的操作。


<details>
  <summary>📚 历史日志</summary>
  <details>
    <summary>2025/08/29 1.2.0发布</summary>
    <ul>
      <li>工具箱页面上线。</li>
      <li>优化用户交流论坛。</li>
    </ul>
  </details>
  <details>
    <summary>2025/07/25 1.1.1发布</summary>
    <ul>
      <li>智能问答页面上线。</li>
      <li>更新视频解析功能。</li>
    </ul>
  </details>
  <details>
    <summary>2025/07/11 1.1.0发布</summary>
    <ul>
      <li>UG模具开发平台正式上线。</li>
    </ul>
  </details>
</details>

<!-- TABLE OF CONTENT -->
<details open="open">
  <summary><h2 style="display: inline-block">📋 文档目录</h2></summary>
  <ol>
    <li>
      <a href="#模具设计开发平台">模具设计开发平台</a>
      <ul>
        <li><a href="#项目简介">项目简介</a></li>
        <li><a href="#主要功能">主要功能</a></li>
        <li><a href="#快速开始">快速开始</a>
        </li>
      </ul>
    </li>
    <li><a href="#代办清单">代办清单</a></li>
    <li><a href="#注意事项">注意事项</a></li>
  </ol>
</details>

# 模具设计开发平台
## 项目简介
模具开发设计平台是一款集UG二开代码插件设计（生成UG代码以及进行代码编译）、UG二开社区一体的模具功能平台。
<br>
UG模具开发平台的诞生主要是为了使机械工程师、工艺师等非专业程序员也能通过自然语言完成简单的自动化任务以及让资深开发工程师从繁琐的API查询和基础代码编写中解放出来，专注于核心算法和复杂逻辑的实现，提升其工作效率；平台将UG二开与大模型应用相结合，旨在精简UG二开的工程任务。



https://github.com/user-attachments/assets/9a819570-01b4-47ad-8255-3ec1fc45382f



## 主要功能
- 支持用户输入用户需求，平台将会根据用户需求生成能够完成用户需求的UG二次开发C++的编码思路（用户可以进行修改）。
- 支持够根据生成的编码思路生成每一个步骤所需的UF函数（用户可以进行修改）。
- 支持函数信息查询，用户输入函数名，平台能够检索出函数对应的传参、函数描述、对应头文件。
- 支持UG二开C++代码的生成，平台能够根据用户确认过后的编码思路以及函数信息来生成能够完成用户需求的代码。
- 支持UG二开C++代码的编译，用户能够选择自己所需编译出来的NX版本来进行编译得到dll文件。
- 支持用户查看历史记录，可以直接跳转到对应历史记录进行编码设计。
- 支持用户查看过往dll文件，用户能够直接下载过往的dll文件。
- 支持用户选取特定工具来解决相应问题。


## 快速开始
[![UG二开平台](https://img.shields.io/badge/UG二开平台-立即使用-2196F3?style=flat&logo=desktop&logoColor=white)](http://ughelper.huiqi-service.cn/#/login)

# 代办清单
- [x] 用户需求生成代码
- [x] 代码编译功能返回可执行dll文件
- [x] 历史记录、dll文件库
- [x] 过多NX版本选择
- [x] 视频需求输入
- [ ] 基于 NX OPEN 实现UG二开
- [ ] 意图识别
- [ ] 插件（复制）需求解析

# 注意事项

- **早期限制**:平台初步阶段，知识库并不丰富生成的编码思路可能不完善，用户可以根据需求自行更改编码思路或所需函数。
- **复杂插件限制**:平台对过于复杂的插件设计效果较差，生成的代码可能无法完成某功能步骤的效果。
- **版本兼容性**:现版本只支持NX10、NX12、NX2306、NX2406版本的代码编译功能，编译的dll文件可能会无法在其他NX版本中使用。
