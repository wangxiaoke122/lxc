### 更新日志

2023.06.07 将部分组件的安装移动到ssh.sh文件中，且优化依赖安装的部分，支持依赖自修复

2023.05.28 修复部分宿主机原生的DNS和IPV4网络优先级的问题

2023.05.15 增加CDN加速配置文件下载

2023.05.10 增加屏蔽掉可能会导致滥用的组件列表

2023.04.29 修复zfs加载进入内核失败时轮询检测哪个存储类型可用

2023.04.27 修复了老系统一键安装lxd环境时需要lxd.migrate的问题，优化zfs的判别条件

2023.04.26 修复了debian(仅限x86_64架构)的zfs问题，现在一键安装lxd环境的脚本支持debian和ubuntu了
