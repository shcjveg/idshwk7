## Tool Address

https://github.com/linyacool/blind-watermark/tree/python3

## Env requirement

```sh
pip3 install opencv-python
```

## 嵌入信息

info.png

> 57117227 邵长捷 :)

```shell
python3 encode.py --image kali.png --watermark info.png --result test.png
```

### 文件

原始图像 kali.png

嵌入信息 info.png

嵌入结果 test.png

## 提取水印

```shell
python3 decode.py --original kali.png --image test.png --result res.png
```

### 文件

原图：kali.png

含水印图像：test.png

提取结果：res.png