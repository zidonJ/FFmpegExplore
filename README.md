# FFmpegExplore
FFmpegStudy
准备条件
	•	先下载文件：https://github.com/libav/gas-preprocessor， 复制gas-preprocessor.pl到/usr/local/bin下， 修改文件权限：chmod 777 /usr/local/bin/gas-preprocessor.pl
	•	安装yasm
	•	curl http://www.tortall.net/projects/yasm/releases/yasm-1.2.0.tar.gz >yasm.tar.gz
	•	tar xzvf yasm.tar.gz
	•	cd yasm-1.2.0//现在是1.3.0版本
	•	./configure
	•	make
	•	sudo make install
具体步骤如下：
1. 下载脚本：https://github.com/kewlbear/FFmpeg-iOS-build-script
2. 解压，找到文件 build-ffmpeg.sh
3. 执行服本文件：./build-ffmpeg.sh
