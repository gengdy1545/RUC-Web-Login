# RUC-Web-Login
Login RUC-Web on Linux

编辑配置文件 `Config.yaml`，修改 `username`，`password`

```yaml
form:
    domain: go.ruc.edu.cn
    username: ""
    userType:
    password: ""
```

运行命令

```bash
./bitsrun --config=Config.yaml
```

-----
基于 https://github.com/Mmx233/BitSrunLoginGo 的智能登录脚本
