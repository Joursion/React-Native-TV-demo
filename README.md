## React-Native-TV-demo

> 使用 React-Native 构建简单的 TV 应用 （Demo）

### 前置

1. React-Native 的官方文档关于 TV APP 开发的仅有一页，且不够详细。[详见](www.baidu.com)

2. React-Native 似乎是从 0.55 版本开始支持 Android TV，所以尽量安装比较新的 RN 版本。[CHANGELOG](https://github.com/react-native-community/react-native-releases/blob/master/CHANGELOG.md#055)

3. React-Native 自带的 RNTester 一直存在运行不起来的问题(玄学)，可以在 issues 或使用 google 搜索。

### Demo 包含

- 列表的焦点处理

- 菜单选项

- 页面跳转

- Slider

- 视频播放

- 图表信息

- 音频播放

- 本地缓存

### 运行

默认已经安装好 `React-Native` 的环境

1. `git clone https://github.com/Joursion/React-Native-TV-demo.git`

2. `cd React-Native-TV-demo`

3. `npm i`

#### tvOS

使用 Xcode 打开 `/React-Native-TV-demo/ios` 目录，选择 tvOS，运行。

#### Android TV

### 开发

1. `git clone https://github.com/Joursion/React-Native-TV-demo.git`

2. `cd React-Native-TV-demo`

3. `npm i`

4. 全局安装TypeScript `npm i typescript -g`

5. `npm run dev`，代码在 `src` 目录，编译目录为 `lib`，可在 `tsconfig.json` 中修改。

6. 可在模拟器中，设置 `hot reloading`。TV OS 使用 `command + D`，Android TV 使用 `command + M` 呼出菜单，进行选择。v

### 其他

#### 系列文章:



### 参考

- [RNTesterAndroidTVDemo - YouTube](https://www.youtube.com/watch?v=EzIQErHhY20)

- [Chain React 2017: React Native on the Apple TV Platform by Doug Lowder - YouTube](https://www.youtube.com/watch?v=jDRXGqb9hno)

- [Chian React 2017 配套代码](https://github.com/dlowder-salesforce/RNAppleTVTalk)