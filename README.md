FaceBoard AR – Shadow Edition
WebAR（A‑Frame + AR.js）を使った 顔出し看板 AR アプリです。
看板モデル（Barnic_Face_Hole.glb）を AR 空間に表示し、
UI 操作で 前後・左右・上下・回転・拡大縮小 が可能です。

さらに、Directional Light による リアル影（Shadow Mapping） を実装し、
看板の形状に沿った影が地面に落ちるようになっています。

🚀 Features（機能）
✔ 顔出し看板モデルの AR 表示
GLB モデルを WebAR 上に表示

カメラの前に自由配置可能

✔ UI 操作
前進 / 後退

左右移動

上昇 / 下降

左右回転

拡大 / 縮小

✔ リアル影（Shadow Mapping）
Directional Light による本物の影

看板の形状に沿った影が透明地面に落ちる

現実の地面に影が落ちているように見える

✔ 船モデル（koukaihune.glb）も同時表示
水面エフェクト

船首波アニメーション

UI は看板と共通

📁 Project Structure（構成）
コード
FaceBoardAR/
│
├── index.html
├── models/
│   ├── Barnic_Face_Hole.glb
│   └── koukaihune.glb
│
├── assets/
│   └── shadow.png   ← 透明地面に影を落とすための補助画像（不要な場合あり）
│
└── README.md
🔧 Technologies（使用技術）
A‑Frame 1.4.2

AR.js

JavaScript

GLB（3Dモデル）

Shadow Mapping（Directional Light）

🌐 How to Run（動作方法）
1. ローカルで動かす場合
WebAR は HTTPS が必要なので、
VSCode の Live Server か、ローカル HTTPS サーバーを使います。

例：

コード
npx http-server -S -C cert.pem -K key.pem
2. GitHub Pages で公開する場合
後述の「GitHub Pages 公開手順」を参照。

📸 Screenshots（任意）
必要なら後で追加できます。

📄 License
© 2026 Freedom
This project is for educational and creative use.