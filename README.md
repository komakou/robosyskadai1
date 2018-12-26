# robosyskadai1
# 2018ロボットシステム学課題１
# 概要
　1を入力すると点灯し，0を入力すると消灯するデバイスドライバー．
# 手法
##  デバイスドライバの作成
```
$ git clone https://github.com/ryuichiueda/raspberry_pi_kernel_build_scripts.git
$ cd raspberry_pi_kernel_build_scripts
$ sudo ./karnel_build_and_install_for_pi2_pi3.bash
$ sudo reboot
```
## 使用方法
```
$ git clone https://github.com/komakou/robosyskadai1.git
$ cd robosyskadai1
$ make
$ sudo insmod myled.ko
$ sudo chmod 666 /dev/myled0
```

## 実行
```
$ echo 1 > /dev/myled0
$ echo 0 > /dev/myled0
```
## youtube
　https://m.youtube.com/watch?feature=youtu.be&v=R1ZrxQxopn8
