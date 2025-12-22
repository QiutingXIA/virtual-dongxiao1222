# virtual-dongxiao1222

**气韵 · 六合 (Virtual Dongxiao & Music Space)**

这是一个基于 Web 前端技术与 Arduino 硬件交互的虚拟洞箫艺术装置项目。

在线体验 (Live Demo)

点击这里访问项目网页 https://tianqiu489-del.github.io/virtual-dongxiao1222/


**项目简介**

本项目利用 HTML5、Three.js 和 Web Audio API 构建了一个沉浸式的视听空间。

视觉：通过 Three.js 构建六面立方体空间，分别对应五行（金木水火土）与虚空。

交互：

鼠标交互：悬停可“炸开”空间结构，观察内部。

声音交互：通过麦克风吹气或 Arduino 传感器控制音律与视觉形态。

回放功能：支持记录吹奏旋律并以 1.5 倍速进行视觉与听觉的回放。

**文件结构**

index.html: 核心代码文件。

electronic_dongxiao.png: 洞箫视觉素材。

**音频文件:**

si.wav (土/Earth)

la.wav (水/Water)

so.wav (木/Wood)

mi.wav (金/Metal)

re.wav (天/Void)

do.wav (火/Fire)

**使用说明**

打开网页后，点击左下角的 "Start Interaction" 允许音频权限。

观赏模式：点击 "Observe" 按钮，鼠标悬停在立方体上可查看解构效果。

演奏模式：点击 "Play" 按钮，通过点击屏幕按钮或连接 Arduino 进行吹奏。

回放：停止吹奏后，点击右侧的 "Perform" 按钮回放刚才的旋律。

**硬件支持**

支持通过 USB 串口连接 Arduino 自制洞箫控制器。

左手按钮 ID: btnConnectL

右手按钮 ID: btnConnectR
