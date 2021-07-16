1. 先设置 electron 镜像
npm config set ELECTRON_MIRROR https://npm.taobao.org/mirrors/electron/

2. 直接使用 npm 安装

3. 出现 electron 启动慢的问题，是因为项目没安装 vue-dev-tools，解决办法：第一次启动项目时使用梯子，或者在 background.js 中关闭 vue 开发工具(VUEJS_DEVTOOLS)