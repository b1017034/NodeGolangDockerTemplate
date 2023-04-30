# NodeGolangDockerTemplate

## フォルダ構成

```
- Template
  |- frontend : node
    |- Dockerfile : node:17.4.0-alpine
  |- backend : golang
    |- .air.toml : hot reload
    |- Dockerfile : golang:1.20-alpine
  |- database
    |- init : mysqlの初回起動時に呼ばれるスクリプト
    |- .env : mysqlのパスワードとか
    |- Dockerfile : mysql:8.0
    
  
```