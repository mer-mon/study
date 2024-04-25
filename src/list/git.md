?Failure when receiving data from the peer
#因为git在拉取或者提交项目时，中间会有git的http和https代理，但是我们本地环境本身就有SSL协议了，所以取消git的https代理即可，不行再取消http的代理。
git config --global --unset http.proxy
git config --global --unset https.proxy



