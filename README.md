# autopwn

cd /usr/share/metasploit-framework/plugins   定位到msf插件目录

git clone https://github.com/AeolusTF/autopwn.git  安装db_autopwn

cd metasploit-db_autopwn

mv db_autopwn.rb /usr/share/metasploit-framework/plugins

打开msfconsole，查看db_autopwn是否安装成功，执行如下命令：

load db_autopwn

自动加载模块

db_autopwn –t –p –r –e
