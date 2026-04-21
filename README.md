# willy-clinical-tools

跨平台 Claude plugin，包含兩個 skill：

- **icd-coder** — ICD-10-CM 查碼助手，針對台灣門診情境設計
- **presentation** — 簡報設計規範（基於《你的簡報就是比AI強》日比野春男）

## 安裝

### Claude Code

```
/plugin marketplace add <your-github-repo>
/plugin install willy-clinical-tools
```

或從本地安裝：

```
/plugin install /Users/weiyu/willy-clinical-tools
```

### Claude Chat / Cowork

透過 [claude.com/plugins](https://claude.com/plugins) 安裝同一個 plugin。

## 結構

```
willy-clinical-tools/
├── .claude-plugin/
│   └── plugin.json
├── skills/
│   ├── icd-coder/
│   │   └── SKILL.md
│   └── presentation/
│       ├── SKILL.md
│       └── references/        # 30+ 設計心理學參考卡
└── README.md
```

## 觸發方式

兩個 skill 都支援**自動觸發**（依 description 關鍵字）與**手動觸發**（`/icd-coder`、`/presentation`）。
