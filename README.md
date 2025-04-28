# 汉诺塔教学演示 (Interactive Tower of Hanoi Tutorial)

这是一个使用纯 HTML, CSS, 和 JavaScript 实现的交互式汉诺塔教学演示程序。它旨在通过可视化的方式帮助理解经典的汉诺塔递归算法。

(This is an interactive Tower of Hanoi teaching simulator built with pure HTML, CSS, and JavaScript. It aims to help understand the classic Tower of Hanoi recursive algorithm through visualization.)

![image](https://github.com/user-attachments/assets/86616fc3-3b5d-476c-8226-609315bdab06)


## 主要特性 (Features)

*   **交互式动画**: 清晰演示汉诺塔问题的递归解法步骤。(Interactive animation demonstrating the Hanoi solution steps.)
*   **自定义圆盘**: 可选择 4 到 20 个圆盘进行模拟。(Customizable number of disks from 4 to 20.)
*   **动画控制**: 提供 开始 / 暂停 / 继续 / 上一步 / 下一步 / 重置 功能。(Full animation controls: Start / Pause / Continue / Previous / Next / Reset.)
*   **速度调节**: 可通过滑块实时调整动画播放速度。(Adjustable animation speed via a slider.)
*   **步数显示**: 实时跟踪并显示移动的总步数。(Real-time move counter display.)
*   **现代 UI**: 采用简洁美观的卡片式设计。(Modern user interface with a clean card-based design.)
*   **主题切换**: 支持浅色和深色主题，并可记忆用户偏好。(Light/Dark theme switching support with user preference persistence.)
*   **双语支持**: 界面主要元素提供中英文对照。(Bilingual UI text support for main elements - Chinese/English.)
*   **响应式设计**: 自动适应桌面、平板和手机竖屏等不同设备。(Responsive design adapting to desktop, tablet, and mobile portrait views.)
*   **辅助信息**: 包含清晰的使用说明和（可替换的）二维码区域。(Includes clear usage instructions and a (replaceable) QR code area.)

## 技术栈 (Technology Stack)

*   HTML5
*   CSS3 (使用 CSS 变量实现主题切换 / Using CSS Variables for theming)
*   JavaScript (ES6+)

## 如何开始 (Getting Started)

本项目无需复杂的构建或安装步骤。

1.  **获取代码**: 克隆或下载本仓库代码到您的本地计算机。
    ```bash
    git clone <your-repository-url>
    cd <repository-directory>
    ```
    或者直接下载 ZIP 文件并解压。

2.  **文件准备**: 确保 `index.html`, `styles.css`, `script.js`, 和 `qrcode.png` 这四个文件位于同一个目录下。

3.  **本地运行**:
    *   **直接打开**: 在现代 Web 浏览器（如 Chrome, Firefox, Edge, Safari）中直接打开 `index.html` 文件即可查看。
    *   **(推荐) 使用本地服务器**: 为了获得最佳体验并避免某些浏览器对本地文件 (`file://` 协议) 的潜在限制（例如 `localStorage` 可能无法工作），建议使用一个简单的本地 HTTP 服务器。
        *   如果您安装了 Node.js，可以在项目目录下打开终端并运行：
            ```bash
            npx serve
            ```
            然后在浏览器中访问 `http://localhost:3000` (端口号可能会变化，请留意终端输出)。
        *   您也可以使用其他任何简单的本地服务器工具（如 Python 的 `http.server` 等）。

## 如何使用 (Usage)

打开页面后，您可以通过界面上的控件进行以下操作：

*   **圆盘数量**: 在输入框中选择 4 到 20 之间的数字，模拟将自动重置。
*   **动画速度**: 拖动滑块调整圆盘移动的速度。
*   **控制按钮**:
    *   点击 **开始 (Start)** 启动动画。
    *   动画运行时，按钮变为 **暂停 (Pause)**，点击可暂停。
    *   暂停后，按钮变为 **继续 (Continue)**，点击可继续播放。
    *   暂停状态下，**上一步 (Previous)** 和 **下一步 (Next)** 按钮可用，用于单步查看移动过程。
    *   **重置 (Reset)** 按钮可随时将模拟恢复到初始状态。
*   **主题切换**: 点击页面右上角的图标 (☀️/🌙) 在浅色和深色主题间切换。您的选择会被浏览器记住。

## 部署 (Deployment)

本项目是一个纯粹的静态网站，可以部署到任何支持静态文件托管的平台。

1.  **准备文件**: 确保您拥有最终的 `index.html`, `styles.css`, `script.js`, 和 `qrcode.png` 文件。您可以直接使用项目根目录下的文件，或者使用之前创建的 `out` 目录中的副本。

2.  **上传文件**: 将这四个文件上传到您的静态托管服务提供商。

3.  **配置**: 通常无需特殊配置，平台会自动将 `index.html` 作为入口文件。确保文件路径正确（例如，如果它们在子目录中，HTML 中的引用需要对应调整，但我们目前的设计是都在根目录）。

4.  **常见平台**:
    *   Cloudflare Pages
    *   GitHub Pages
    *   Netlify
    *   Vercel
    *   AWS S3 (配置为静态网站托管)
    *   等等...

## 注意 (Note)

*   项目中的 `qrcode.png` 文件是一个占位符图片。在您部署或分享时，请务必将其替换为您自己的有效二维码图片。

---

(可以根据需要添加贡献指南或许可证信息 / Add Contributing guidelines or License information if desired)
