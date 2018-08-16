# node版本管理工具nvm的安装和使用（mac）

# 使用npm安装
npm install nvm

# nvm使用命令

nvm --help                          显示所有信息

nvm --version                       显示当前安装的nvm版本

nvm install <version>  -latest-npm  安装指定的版本，平且下载最新的npm

nvm install <version>               安装指定版本，可模糊安装，如：安装v4.4.0，既可nvm install v4.4.0，又可nvm install 4.4
  
nvm install-latest-npm              安装最新的npm

nvm reinstall-packages <version>    重新安装指定的版本
  
nvm uninstall <version>             删除已安装的指定版本，语法与install类似

nvm use <version>                   切换使用指定的版本node

nvm ls                              列出所有安装的版本

nvm ls-remote                       列出所以远程服务器的版本（官方node version list）

nvm current                         显示当前的版本

nvm alias <name> <version>          给不同的版本号添加别名

nvm unalias <name>                  删除已定义的别名

nvm reinstall-packages <version>    在当前版本node环境下，重新全局安装指定版本号的npm包

nvm alias default <version>         设置默认 node 版本

nvm cache dir                       显示nvm的cache

nvm cache clear                     清空nvm的cache

# nvm-mac-
