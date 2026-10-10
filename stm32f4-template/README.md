# STM32F4 工程模板

## 项目目标

提供基于 STM32F4xx 标准外设库和 CMSIS 的工程基线，支持 Keil MDK 和 eIDE 开发环境。

## 目录说明
- User：应用入口、中断处理和配置文件
- Hardware：板级硬件驱动扩展目录
- Library：STM32F4 标准外设库
- Start：启动文件和系统初始化
- .cmsis、.eide、.vscode：CMSIS 与开发环境配置
- Project.uvprojx：Keil MDK 工程

## 使用方式
使用 Keil MDK5 打开 Project.uvprojx，在 User/main.c 中编写应用逻辑并配置目标芯片。
