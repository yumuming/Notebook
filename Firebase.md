<!-- Firebase.md -->

# firebase cli 教程地址 （需要开启VPN）
https://firebase.google.com/docs/cli?authuser=0

1、npm install -g firebase-tools
Error: sha1-7Qoe24fAXU2xA3xfj0g9ijtfCCU= integrity checksum failed when using sha1: wanted sha1-7Qoe24fAXU2xA3xfj0g9ijtfCCU= but got sha512-mYQLZnx5Qt1JgB1WEiMCf2647plpGeQ2NMR/5L0HNZzGQo4fuSPnK+wjfPnKZV0aiJDgzmWqqkV/g7JD+DW0qw== sha1-psC74fOPOqC5Ijjstv9Cw0TUE10=. 

解决方案 设置远端仓库地址
npm config set registry https://registry.npm.taobao.org/

2、firebase login
Error: 登陆验证卡住
解决方案 设置代理地址
export http_proxy=http://127.0.0.1:1087;export https_proxy=http://127.0.0.1:1087;