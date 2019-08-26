

### Beyond Compare 4 Linux 破解方法

key失效了可以[线上生成](https://www.serials.be/serial/Beyond_Compare_4_Linux_68803632.html)

### [Crack Beyond Compare 4 on Linux](https://github.com/jyma1991/Crack-Beyond-Compare-linux.git)

**1.官网下载最新版 [Beyond Compare 4](http://www.scootersoftware.com/download.php) 并安装**

安装命令：
```
sudo apt install -i bcompare-4.2.3.22587_amd64.deb
```

如果报错 “依赖关系问题 - 仍未被配置” 使用如下命令


```
sudo apt-get install -f
```

等分析完之后重新执行安装命令

**2.破解**

```
cd /usr/lib/beyondcompare/
sudo sed -i "s/keexjEP3t4Mue23hrnuPtY4TdcsqNiJL-5174TsUdLmJSIXKfG2NGPwBL6vnRPddT7tH29qpkneX63DO9ECSPE9rzY1zhThHERg8lHM9IBFT+rVuiY823aQJuqzxCKIE1bcDqM4wgW01FH6oCBP1G4ub01xmb4BGSUG6ZrjxWHJyNLyIlGvOhoY2HAYzEtzYGwxFZn2JZ66o4RONkXjX0DF9EzsdUef3UAS+JQ+fCYReLawdjEe6tXCv88GKaaPKWxCeaUL9PejICQgRQOLGOZtZQkLgAelrOtehxz5ANOOqCaJgy2mJLQVLM5SJ9Dli909c5ybvEhVmIC0dc9dWH+/N9KmiLVlKMU7RJqnE+WXEEPI1SgglmfmLc1yVH7dqBb9ehOoKG9UE+HAE1YvH1XX2XVGeEqYUY-Tsk7YBTz0WpSpoYyPgx6Iki5KLtQ5G-aKP9eysnkuOAkrvHU8bLbGtZteGwJarev03PhfCioJL4OSqsmQGEvDbHFEbNl1qJtdwEriR+VNZts9vNNLk7UGfeNwIiqpxjk4Mn09nmSd8FhM4ifvcaIbNCRoMPGl6KU12iseSe+w+1kFsLhX+OhQM8WXcWV10cGqBzQE9OqOLUcg9n0krrR3KrohstS9smTwEx9olyLYppvC0p5i7dAx2deWvM1ZxKNs0BvcXGukR+/g" BCompare
```

**3.输入秘钥**

此时BCompare文件已被破解，打开软件会提示“Trial Mode Error！”表示成功，输入下面TEAM ZWT生成的密钥即可注册成功

```
--- BEGIN LICENSE KEY ---
GXN1eh9FbDiX1ACdd7XKMV7hL7x0ClBJLUJ-zFfKofjaj2yxE53xauIfkqZ8FoLpcZ0Ux6McTyNmODDSvSIHLYhg1QkTxjCeSCk6ARz0ABJcnUmd3dZYJNWFyJun14rmGByRnVPL49QH+Rs0kjRGKCB-cb8IT4Gf0Ue9WMQ1A6t31MO9jmjoYUeoUmbeAQSofvuK8GN1rLRv7WXfUJ0uyvYlGLqzq1ZoJAJDyo0Kdr4ThF-IXcv2cxVyWVW1SaMq8GFosDEGThnY7C-SgNXW30jqAOgiRjKKRX9RuNeDMFqgP2cuf0NMvyMrMScnM1ZyiAaJJtzbxqN5hZOMClUTE+++
--- END LICENSE KEY -----
```

**4.破解成功**
成功后在目录~/.config/bcompare/下会生成文件BC4Key.txt 如下

```
Beyond Compare 4
Licensed to:    pwelyn
Quantity:       9999 users
Serial number:  9571-9981
License type:   Pro Edition for Windows/Linux/OS X

--- BEGIN LICENSE KEY ---
GXN1eh9FbDiX1ACdd7XKMV7hL7x0ClBJLUJ-zFfKofjaj2yxE53xauIfk
qZ8FoLpcZ0Ux6McTyNmODDSvSIHLYhg1QkTxjCeSCk6ARz0ABJcnUmd3d
ZYJNWFyJun14rmGByRnVPL49QH+Rs0kjRGKCB-cb8IT4Gf0Ue9WMQ1A6t
31MO9jmjoYUeoUmbeAQSofvuK8GN1rLRv7WXfUJ0uyvYlGLqzq1ZoJAJD
yo0Kdr4ThF-IXcv2cxVyWVW1SaMq8GFosDEGThnY7C-SgNXW30jqAOgiR
jKKRX9RuNeDMFqgP2cuf0NMvyMrMScnM1ZyiAaJJtzbxqN5hZOMClUTE+
--- END LICENSE KEY -----
```

我最近全新安装了一次18.04，最小化安装的。
然后第一件事就是装SSR，发现之前都能用现在怎么不行了。
配置什么的一切正常，其实是python没设置好。
因为默认装的是python3，然后终端输入python会提示没安装，其实已经安了，只是没有链接命令而已。
sudo ln -s /usr/bin/python3 /usr/bin/python
搞定！重启一下electron-ssr和浏览器，根本不需要任何插件和浏览器设置，系统设置里的网络代理保持自动模式即可。



	
export http_proxy="http://127.0.0.1:12333"

export https_proxy="http://127.0.0.1:12333"

