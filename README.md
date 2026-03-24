# 中文学习网站

一个模仿vhs lernportal的中文学习网站，包含汉语拼音入门和基础课程。

## 项目结构

```
.
├── index.html          # 首页
├── preparation.html    # 汉语拼音入门课程
├── level0.html         # Level 0 中文零基础入门
├── lesson1.html        # 第一课 单韵母 a o e
├── lesson1-2.html      # 单韵母 a
├── lesson1-3.html      # 单韵母 o
├── lesson1-4.html      # 单韵母 e
├── practice.html       # 练习页面
└── README.md           # 项目说明
```

## 功能特点

- 支持中文和英文双语切换
- 拼音发音演示视频
- 录音功能，可录制和播放自己的发音
- 拼音练习，测试听力理解
- 响应式设计，适配不同设备

## 如何部署到GitHub

1. **安装Git**
   - 访问 https://git-scm.com/downloads 下载并安装Git
   - 安装完成后重启电脑

2. **初始化Git仓库**
   ```bash
   # 在项目目录中执行
   git init
   git add .
   git commit -m "Initial commit"
   ```

3. **创建GitHub仓库**
   - 登录GitHub账号
   - 点击右上角的"+"按钮，选择"New repository"
   - 填写仓库名称，选择公开或私有，然后点击"Create repository"

4. **关联本地仓库与GitHub仓库**
   ```bash
   # 在GitHub仓库页面复制远程仓库URL
   git remote add origin <远程仓库URL>
   git push -u origin main
   ```

5. **验证部署**
   - 刷新GitHub仓库页面，确认所有文件已上传

## 技术栈

- HTML5
- CSS3
- JavaScript
- Web Audio API (录音功能)
- MediaRecorder API (录音功能)
