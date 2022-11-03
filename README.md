- 👋 Hi, I’m @xiangnanscu
- 👀 I’m interested in fullstack web devs(openresty, nodejs, vue, python)
- 🌱 I’m currently learning golang
- 💞️ I’m looking to collaborate on web devs.
- 📫 How to reach me: 280145668@qq.com

# 各种疑难解决记录
## 重置win10网络条件
突然git和sshuttle各种不好使了, 例如git kex_exchange_identification: Connection closed by remote host, 网上搜了一下,运行下列命令, 重启电脑, 搞定
```sh
netsh winsock reset
netsh int ip reset
ipconfig /release
ipconfig /renew
ipconfig /flushdns
```
