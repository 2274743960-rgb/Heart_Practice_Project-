# Interactive Heart Particle Experience / 交互式心形粒子体验

## 项目概述 / Project Overview
一个融合计算机视觉、3D图形和音频技术的沉浸式网页应用，创造情感化数字交互体验。由暨南大学国际学院开发，展示前沿网页技术在创造有意义数字体验方面的应用。

An immersive web application combining computer vision, 3D graphics, and audio to create emotional digital interactions. Developed at Jinan University International College, showcasing cutting-edge web technologies for meaningful digital experiences.

## 功能特色 / Features

### 手势识别 / Hand Gesture Recognition
- 使用MediaPipe Hands进行实时手部追踪
- 食指和拇指之间的捏合检测
- 基于手部距离的动态粒子操控
- 带特殊动画触发的手势计数器

- Real-time hand tracking using MediaPipe Hands
- Pinch detection between thumb and index finger
- Dynamic particle manipulation based on hand distance
- Gesture counter with special animation triggers

### 眨眼检测 / Blink Detection
- 使用MediaPipe Face Mesh进行面部关键点检测
- 使用眼睛纵横比算法进行实时眨眼检测
- 每次眨眼自动切换粒子效果
- 四种不同的视觉效果：心形、螺旋、爆炸和波浪

- Facial landmark detection using MediaPipe Face Mesh
- Real-time blink detection using Eye Aspect Ratio algorithm
- Automatic particle effect switching with each blink
- Four distinct visual effects: Heart, Spiral, Explosion, and Wave

### 动态粒子系统 / Dynamic Particle System
- 基于Three.js的3D粒子动画
- 基于手势的响应式粒子缩放
- 多种交互式粒子效果
- 实时粒子位置更新

- Three.js-powered 3D particle animations
- Responsive particle scaling based on hand gestures
- Multiple interactive particle effects
- Real-time particle position updates

### 音频集成 / Audio Integration
- 带自适应播放的背景音乐播放器
- 手势触发的心跳音效
- 粒子效果转换音效
- 音量控制和进度跟踪

- Background music player with adaptive playback
- Heartbeat sound effects triggered by gestures
- Particle effect transition sounds
- Volume control and progress tracking

### 特殊效果 / Special Effects
- 全界面漂浮爱心动画
- 连续手势后的全屏"I LOVE YOU"动画
- 响应交互的情感语录
- 带视觉反馈的实时摄像头画面

- Floating heart animations throughout the interface
- Fullscreen "I LOVE YOU" animation after consecutive gestures
- Emotional quotes that respond to interactions
- Real-time camera feed with visual feedback

## 技术架构 / Technical Architecture

### 核心技术 / Core Technologies
- **MediaPipe Hands**：实时手部追踪解决方案，用于手势识别
- **MediaPipe Face Mesh**：面部关键点检测，用于眨眼识别
- **Three.js**：基于WebGL的3D图形库，用于粒子动画
- **Web Audio API**：高级音频处理和播放控制

- **MediaPipe Hands**: Real-time hand tracking solution for gesture recognition
- **MediaPipe Face Mesh**: Facial landmark detection for blink recognition
- **Three.js**: WebGL-based 3D graphics library for particle animations
- **Web Audio API**: Advanced audio processing and playback control

## 安装说明 / Setup Instructions

### 先决条件 / Prerequisites
- 支持WebGL的现代网页浏览器
- 用于手势和眨眼检测的摄像头
- 音频功能所需的麦克风权限

- Modern web browser with WebGL support
- Webcam for gesture and blink detection
- Microphone permissions for audio features

### 安装步骤 / Installation Steps
1. 将代码库克隆到本地环境
2. 确保所有音频文件位于正确目录
3. 在网页浏览器中打开index.html
4. 提示时允许摄像头和麦克风权限
5. 开始使用手势和面部表情进行交互

6. Clone repository to local environment
7. Ensure audio files in correct directory
8. Open index.html in web browser
9. Allow camera and microphone permissions
10. Begin interaction with gestures and expressions

## 使用指南 / Usage Guide

### 基本交互 / Basic Interactions
- **手部捏合**：将拇指和食指并拢以控制粒子大小
- **眨眼**：短暂闭眼以切换粒子效果
- **手势计数**：连续执行10次捏合以解锁特殊动画

- **Hand Pinching**: Control particle size by pinching thumb and index finger
- **Blinking**: Switch particle effects by blinking
- **Gesture Counting**: Unlock special animation with 10 consecutive pinches

### 高级功能 / Advanced Features
- **音乐控制**：使用播放器控件管理音频播放
- **语录交互**：悬停或点击语录以更改情感消息
- **效果选择**：从控制面板手动选择粒子效果

- **Music Control**: Manage audio playback with player controls
- **Quote Interaction**: Change emotional messages by hovering/clicking quotes
- **Effect Selection**: Manually choose particle effects from control panel

## 开发团队 / Development Team

### 项目负责人 / Project Lead
**夏国庆** - 暨南大学国际学院

**Xia Guoqing** - International College, Jinan University

### 学术指导 / Academic Advisor
**龙舜教授** - 指导教师

**Prof. Long Shun** - Faculty Advisor

### 联系信息 / Contact Information
- 邮箱：2274743960@qq.com
- 机构：暨南大学国际学院

- Email: 2274743960@qq.com
- Github Account: https://github.com/2274743960-rgb/Heart_Practice_Project-
- Institution: International College, Jinan University

## 致谢 / Acknowledgments
本项目作为国际学院促进跨学科学习和技术创新计划的一部分开发。特别感谢谷歌MediaPipe团队提供的开源计算机视觉解决方案。

Developed as part of Jinan University International College's initiative to promote interdisciplinary learning and technological innovation. Special thanks to the MediaPipe team at Google for their open-source computer vision solutions.

---

*暨南大学国际学院 - 通过创新连接科技与人文*

*Jinan University International College - Bridging Technology and Humanity Through Innovation*
