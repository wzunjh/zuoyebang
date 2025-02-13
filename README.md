# 百川任务平台 作业帮领题自动化工具

[![GitHub Stars](https://img.shields.io/github/stars/wzunjh/baichuan_task_tool?style=social)](https://github.com/wzunjh/baichuan_task_tool)
[![GitHub Forks](https://img.shields.io/github/forks/wzunjh/baichuan_task_tool?style=social)](https://github.com/wzunjh/baichuan_task_tool)
[![GitHub Issues](https://img.shields.io/github/issues/wzunjh/baichuan_task_tool)](https://github.com/wzunjh/baichuan_task_tool/issues)

**免责声明：** 本工具由智通全网络工作室开发，仅供学习交流使用，请勿用于任何商业或非法用途。因滥用工具造成的任何损失，开发者概不负责。

## 项目简介

本工具旨在帮助百川任务平台的作业帮用户更高效地领取题目，提高工作效率。 通过自动化登录和任务领取流程，解放双手，告别手动刷新，让领题变得更加轻松便捷。

## 功能特点

*   **自动化登录：** 支持Cookie登录和短信验证码登录两种方式，灵活方便。
    *   **Cookie 登录:**  使用BCUSS Cookie值一键登录，避免频繁输入账号密码。  **(首次请使用短信登录会获得BCUSS值，请妥善保存，便于重复使用)**
    *   **短信验证码登录:**  通过手机号和验证码快速登录，方便快捷。
*   **多模式领题：** 支持录课领题、自审领题以及同时进行两种任务模式，满足不同用户的需求。
*   **智能任务领取：** 自动识别并领取当前可领取的任务，无需人工干预。
*   **实时日志显示：** 详细记录任务领取过程中的各种信息，方便用户了解任务状态。
*   **人性化暂停功能：** 随时暂停和恢复任务领取，灵活控制任务流程。
*   **简洁易用：** 采用Tkinter图形界面，操作简单直观，无需专业知识即可轻松上手。

## 使用方法

1.  **环境准备：**
    *   **安装Python:** 确保您的计算机上已安装Python 3.x版本。
    *   **安装依赖库:**  在命令行中执行 `pip install selenium tkinter` 安装必要的依赖库。
    *   **下载ChromeDriver:** 下载与您的Chrome浏览器版本相匹配的ChromeDriver，并将其放置在与程序相同的目录下。（若无驱动可在CSDN查看教程）

2.  **配置：**
    *   修改 `chrome_driver_path = r'chromedriver.exe'` 为您的 ChromeDriver 路径。

3.  **运行：**
    *   双击运行程序，打开图形界面。

4.  **登录：**
    *   **Cookie登录：**  在 "BCUSS Cookie" 输入框中填入有效的BCUSS值，然后选择 "Cookie" 登录方式，点击 "登录" 按钮。
    *   **短信验证码登录：**  选择 "短信验证码" 登录方式，填入手机号，点击 "发送验证码" 按钮，收到验证码后填入 "验证码" 输入框，点击 "登录" 按钮。

    ```
   ![3b3d1c6a40e785919301c47befa9e8b](https://github.com/user-attachments/assets/7a21542b-84a5-4194-b493-3198f4af7f42)

    ```

    ```
    ![e46ba660c65889da65dafa9deeb0b4f](https://github.com/user-attachments/assets/b5cbfe51-f787-4f1c-aff1-9cb43a714a60)

    ```

5.  **选择模式：**
    *   根据您的需求选择 "录课领题"、"自审领题" 或 "同时录课和自审" 模式，点击相应的按钮开始任务。

    ```
    ![e8daa3cf23d9ef78edba883c1fc2a79](https://github.com/user-attachments/assets/d1dd5e7a-c1f6-4f1e-b988-5914e52ee0bd)

    ```

6.  **监控日志：**
    *   在 "日志" 区域查看任务领取过程中的各种信息。

7.  **暂停任务：**
    *   如果需要暂停任务，点击相应的 "暂停录课" 或 "暂停自审" 按钮。

## 注意事项

*   **请确保您的Chrome浏览器版本与ChromeDriver版本相匹配，否则可能导致程序无法正常运行。**
*   **建议首次使用短信登录方式获取BCUSS值，并保存该值以便后续使用Cookie登录。**
*   **不要随意使用验证码功能(最好保存BCUSS用Cookie登录),封号后果自负!**
*   **运行过程中，请保持网络连接稳定。**
*   **本工具仅供学习交流使用，请勿用于任何商业或非法用途。**

## 技术支持

*   **GitHub:** [github.com/wzunjh](https://github.com/wzunjh)
*   **工作室官网:** [www.9fai.com](http://www.9fai.com)

##  更新日志
* 2024-05-15：
  * 首次发布。

## 贡献

欢迎各位开发者参与到本项目的开发中来！如果您有任何建议或意见，请在GitHub上提交Issue或Pull Request。
