﻿# jsc-Decryption

⚡This is a script that decrypts the coco2d-js.jsc file⚡

🌈The core process is the decryption of **`XXTEA`** and **`GZIP`**.🌈

### Usage :
        python main.py [-d] [xxteaKey] [jscDir]
### Example :
        python main.py -d 6362d9fe-c3ad-47 C:\DecJsc-master\src
### Tips :
        -d or -decrypt [decrypt]
### Outputs :
        The output folder is located in the same directory as the JSC folder.

### ❗Waiting for repair and Known errors :
- [x] The XXTEA&zip mode cannot be decrypted.
- [x] XXTEA mode cannot be decrypted.

![example](https://github.com/shiyingqi/jsc-Decompile/blob/main/jsc-Decompile_example.png)

If you have any questions, please contact [ MasonShi@88.com ]
