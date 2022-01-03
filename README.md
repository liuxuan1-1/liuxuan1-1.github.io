个人网站, 基于HEXO, 主题butterfly

`hexo serve` 启动服务本地调试
`hexo generate -f` 加个force参数, 强制generate, 否则有时候(没深究, 反正发现不对, 就加-f)改config不会生效
`hexo deploy` 调试好了之后, 走下这个命令

将生成的public文件夹改成docs(因为github-page只能识别docs文件夹和root), 再将root下的CNAME复制一份到docs里面
