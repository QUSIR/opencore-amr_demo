# 使用说明

源码`test`目录下有相应的测试程序支持`wav`文件编解码

解压出来目录修改过后支持`pcm`文件编解码


#相应测试指令
##pcm
编码

	./amrnb-enc -r 8000 compare.pcm out.amr

解码

	./amrnb-dec out.amr out.pcm
##wav
编码

	./amrnb-enc -r 8000 compare.wav out.amr

解码

	./amrnb-dec out.amr out.wav

`test`目录下为静态库编译链接方式测试程序 