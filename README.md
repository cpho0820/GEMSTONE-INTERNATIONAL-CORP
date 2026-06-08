# 積燁國際有限公司網站

這是積燁國際有限公司的靜態形象網站，內容包含：

- 耐火材料更新
- 寵物焚化爐維修、設計與製造
- 環保金爐製造與維修
- 空汙設備設計、製造與維修

## 本機預覽

```powershell
python -m http.server 5188 --bind 127.0.0.1
```

開啟：

```text
http://127.0.0.1:5188/
```

## 部署

本 repo 使用 GitHub Pages workflow 部署。推送到 `main` 後，GitHub Actions 會自動發布網站。
