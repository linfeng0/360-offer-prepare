# gitSkills
全力准备360春招，希望自己的所有努力不要白费，git也实现一遍！

编码问题导致READEme文件在本地终端打开乱码：
1.查看readme.md的文件编码（vi底部命令模式:set fileencoding)
2.首先需要对mac终端的设置进行更改编码：utf-8
3.配置终端配置文件.bash_profile 
	export LC_ALL = zh_CN.UTF-8
4.配置vim配置文件 .vimrc
	set fencs=utf-8,gbk
	set encoding=utf-8
	set fileencoding=gb18030
	set fileencodings=utf-8,gb18030,utf-16,big5
	set fileencoding=ucs-bom,utf-8,cp936,gb18030,big5,euc-jp,euc-kr,layin1

source一下，ok！！！

测试一下冲突！master
