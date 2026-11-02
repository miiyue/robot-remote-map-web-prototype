# Remote Map Web Prototype

机器人远程建图 Web 工具交互原型。

## 公开入口

- 主界面：`index.html`
- Web 工具：`assets/remote-map-web/index.html#/editor`
- 地图编辑器：`assets/map2-editor/terminal/index.html?embed=web-v16`

## 项目边界

- 本仓库仅用于 Web 端远程建图工具原型。
- 机器人终端交互原型使用独立仓库 `robot-map2.0-editor-prototype`，两者不混用。
- 不包含本地评审页的左侧导航和右侧交互说明。

## 目录

```text
.
├── index.html
├── assets/
│   ├── remote-map-web/
│   │   └── index.html
│   └── map2-editor/
│       ├── robot-heading.svg
│       └── terminal/
│           ├── index.html
│           └── assets/
└── CHANGELOG.md
```

## 本地预览

```sh
python3 -m http.server 4173
```

打开 `http://localhost:4173/`。
