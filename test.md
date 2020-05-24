本次作业使用藏于色块的方式将包含学号和姓名的txt文件隐藏在png照片中
隐藏信息使用的命令为：python LSBSteg.py encode –i input.png -o output.png -f info.txt
解码使用的命令为：python LSBSteg.py decode –i output.png –o info.txt