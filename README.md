# vue專案初始化 - vscode編輯器 開箱即用設定

**特別感謝 [這篇文章](http://stariveer.coding.me/fe-doc/code_format/Getting-Started.html)**

解決每次要開新專案時，都要處理一堆編輯器設定的麻煩😂

1️⃣ 先切換到 `專案根目錄` 

❗ 如果害怕 `.git 目錄`、`README.md 文件` 會出問題，**請先備份** 💪

```bash
cd path/to/project/root # 專案根目錄
[[ -f README.md ]] && mv README.md README.md.bak
[[ -d .git ]] && mv .git .git.bak
git clone https://github.com/david-fox-chang/vscode-vue-dev-init-setting.git .
npm i eslint eslint-config-airbnb-base eslint-config-prettier eslint-plugin-import eslint-plugin-prettier eslint-plugin-vue prettier -D
[[ -f README.md.bak ]] && mv README.md.bak README.md
rm -rf .git && [[ -d .git.bak ]] && mv .git.bak .git
```

詳細設定內容，已有[珠玉](http://stariveer.coding.me/fe-doc/code_format/Getting-Started.html)在前，不再贅述
