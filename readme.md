#### 構築（web_desktopリポジトリ用）
---
* web_desktop用の開発環境: [web_desktop](https://github.com/Taukon/web_desktop.git)
```
$cd docker_dev
$git checkout web_desktop_dev
$rm -rf .git
$mkdir src

$docker-compose build
$docker-compose up -d
```

#### ブランチ
---
* php: php_dev
* node.js: node_dev