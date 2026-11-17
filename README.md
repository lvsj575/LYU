# LYU

LYU 项目仓库。

## 版本

- 当前版本：**v1.5.8**（见 `VERSION` 文件）
- 对应源码：`WCLyuPush_源码_1.5.8.c`

## 目录结构

```
LYU/
├── README.md
├── VERSION
├── CHANGELOG.md
└── .gitignore
```

## 使用

```bash
git clone https://github.com/lvsj575/LYU.git
cd LYU
```

## 版本号读取

WCLyuPush 侧栏「最新版本」读取下列地址，内容应与编译时的 `WCB_VERSION` 保持一致：

```
https://raw.githubusercontent.com/lvsj575/LYU/refs/heads/main/VERSION
```

## 版本管理约定

- 版本号采用语义化版本 `MAJOR.MINOR.PATCH`
- **每次更新源码（发布新版本）时必须同步更新本仓库版本号**：同步修改 `VERSION`、`README` 中的当前版本、`CHANGELOG`（新增对应条目），并确保编译宏 `WCB_VERSION` 与该值一致
- `VERSION` 文件只写版本号本身（如 `1.5.8`），不要带 `v` 前缀或额外文字
