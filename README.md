# Weex Template

Weex template for [vue-cli](https://github.com/vuejs/vue-cli).

## Usage

```bash
# Install vue-cli first.
npm install -g vue-cli

# Start a Weex Project.
vue init u3u/weex-template <project-name>
```

## 修改说明

- 新增了 `.we` 对 `jade/pug` 和 `stylus` 的支持
- 新增了 [weex-adapter-image](https://market.dotwe.org/ext/list.htm#11) 插件用于显示 iOS Native 端的图片

## 使用说明

**权限**

```sh
$ sudo chmod -R 777 <your_path>
```

**安装依赖**

```sh
$ npm install
```

**打包**

```sh
$ npm run build
```

**开发**

```sh
$ weex run web
$ npm run dev
```

**调试**

```sh
$ weex debug
```

**在模拟器运行**

```sh
$ sudo weex platform add ios
$ sudo gem install cocoapods --pre
$ weex run ios
```

