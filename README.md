# LYU

LYU 项目仓库。

## 版本

- 当前版本：**v1.5.8**（见 `VERSION` 文件）
- 对应源码：`WCBarkPush_源码_1.5.8.c`

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

WCBarkPush 侧栏「最新版本」读取下列地址，内容应与编译时的 `WCB_VERSION` 保持一致：

```
https://raw.githubusercontent.com/lvsj575/LYU/refs/heads/main/VERSION
```

## 版本管理约定

- 版本号采用语义化版本 `MAJOR.MINOR.PATCH`
- 每次发布更新 `VERSION` 文件，并在 `CHANGELOG.md` 记录变更
