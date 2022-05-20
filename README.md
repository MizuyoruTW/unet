# U-net modified for my environment

# Thanks

The original code is forked from [zhixuhao](https://github.com/zhixuhao/unet).

The environments is from [Nelson-Gon](https://github.com/Nelson-Gon/cytounet/blob/master/requirements.txt)

# Environment

For pip packages, see [requirement.txt](https://github.com/MizuyoruTW/unet/blob/master/requirement.txt) for more details.

Other environment I use:

-   Hardware
    -   RAM: 16G
    -   CPU: Intel i5-8400
    -   GPU: Nvidia Geforce GTX 1050 2GB
-   Software
    -   OS: Windows 11 21H2
    -   Python Virtual Env: Anaconda
    -   CUDAtoolkit: 11.3.1
    -   cudnn: 8.2.1

# Usage

You can setup environment by using pip:

```
pip install -r requirement.txt
```

Run main.py to train 1 epoch and predict test images:

```
python main.py
```
