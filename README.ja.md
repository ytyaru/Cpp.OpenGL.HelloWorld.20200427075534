[en](./README.md)

# Cpp.OpenGL.HelloWorld

　C++でOpenGLの窓を作る。

# デモ

![demo](doc/demo.png)

# 開発環境

* <time datetime="2020-04-27T07:54:55+0900">2020-04-27</time>
* [Raspbierry Pi](https://ja.wikipedia.org/wiki/Raspberry_Pi) 4 Model B Rev 1.2
* [Raspbian](https://ja.wikipedia.org/wiki/Raspbian) buster 10.0 2019-09-26 <small>[setup](http://ytyaru.hatenablog.com/entry/2019/12/25/222222)</small>
* bash 5.0.3(1)-release
* gcc
* OpenGL

```sh
$ uname -a
Linux raspberrypi 4.19.97-v7l+ #1294 SMP Thu Jan 30 13:21:14 GMT 2020 armv7l GNU/Linux
```

# インストール

```sh
sudo apt -y install freeglut3 freeglut3-dev
```

# 使い方

```sh
git clone https://github.com/ytyaru/Cpp.OpenGL.HelloWorld.20200427075534
cd Cpp.OpenGL.HelloWorld.20200427075534/src
g++ -Wall -Weffc++ -o glut_main main.cpp -lglut -lGLU -lGL
./glut_main
```

# 著者

　ytyaru

* [![github](http://www.google.com/s2/favicons?domain=github.com)](https://github.com/ytyaru "github")
* [![hatena](http://www.google.com/s2/favicons?domain=www.hatena.ne.jp)](http://ytyaru.hatenablog.com/ytyaru "hatena")
* [![mastodon](http://www.google.com/s2/favicons?domain=mstdn.jp)](https://mstdn.jp/web/accounts/233143 "mastdon")

# ライセンス

　このソフトウェアはCC0ライセンスである。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)

