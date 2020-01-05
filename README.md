# pdftotext

PDF转换Text

运行环境：windows

测试环境：windows 10 64位

打包环境：python 2.7.13

引用核心： [PDFMiner](http://www.unixuser.org/~euske/python/pdfminer/)


----------

# 配置手册

setup 1. 打包下载本程序[访问](https://github.com/bioinfo1992/pdftotext)

setup 2. 解压

setup 3. 将程序根目录添加到windows系统环境变量

setup 4. 打开DOS 输入

    >pdf2txt
  显示如下：
    usage: pdf2txt.exe [-d] [-p pagenos] [-m maxpages] [-P password] [-o output] [-C] [-n] [-A] [-V] [-M char_margin] [-L line_margin] [-W word_margin] [-F boxes_flow] [-Y layout_mode] [-O output_dir] [-R rotation] [-t text|html|xml|tag] [-c codec] [-s scale] file ...
    
  说明配置成功，如果出现：
  
    'pdf2txt' 不是内部或外部命令，也不是可运行的程序或批处理文件。
    
  请重新配置系统环境！
  
setup 5. 配置成功后就可以测试你的pdf文档

    #pdf2txt -o output.txt demo.pdf
    
 查看效果！
 
 # pdf2txt 参数介绍（节选自官方文档）
 
 
 查看官方文档：[访问](http://www.unixuser.org/~euske/python/pdfminer/)
 
 ## 部分参数：
 
 -o filename
   
   输出文件名，默认输出text文档
 
 -t type
   
   输出文件格式：
   
   text:默认输出格式
   
   html
   
   xml
   
   tag
 
 -c codec
 
   指定输出文件的编码格式
 
 更多参数请访问官方文档......[more](http://www.unixuser.org/~euske/python/pdfminer/)
