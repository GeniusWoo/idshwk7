下载LSB-Steganography，修改LSBSteg.py。

使用python3 LSBSteg.py encode -i input.jpg -o test.png -f info.txt将ID和姓名隐藏在图像的颜色中

使用python3 LSBSteg.py decode -i test.png -o info2.txt即可提取出隐藏在图像中的信息
