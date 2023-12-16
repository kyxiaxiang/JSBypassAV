# JSBypassAV

GadgetToJScript 的原始代码来自@med0x2e - https://github.com/med0x2e/GadgetToJScript
感谢: @EncodeGroup


myBlog: https://xiaxiang.xyz/弃用
  New url : https://kyxiaxiang.github.io/

环境Kali Linux目前不适合win。
初始化   apt install mono-complete
设置JsBypass.cna中的环境变量。已经在文件中标注了。

  1	$toolpath是安装目录的绝对路径。（记得先mkdir）

  2	$outpath是用于输出所有生成的工件的目录。

  3	$python3是 python3 二进制文件的绝对路径。

  4	$gzip是 gzip 二进制文件的绝对路径。

  5	$mcs是 mcs 二进制文件的绝对路径



将cna脚本添加到Cobaltstrike，菜单栏会出现一个可视的菜单。
正常选择配置点击生成，就会在outpath定义的绝对路径下生成GadeToJScript.exe，复制到windows下运行即可生成js文件。不放心的可以在虚拟机使用。源码都能看得清清楚楚就不要傻逼一样哔哔有后门了。
