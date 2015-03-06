ip
==

由于最近DDNS服务不能用了，于是我写了这个脚本，
每隔一段时间会把IP提交到这里来。这样我就可以
远程访问我的电脑了。
中国电信，中国移动，中国联通，都有固定IP服务。
但对我来说，只是远程访问，没必要花大价钱来买
一个固定的IP地址。

recently, ddns is not working on our server.
and i have just check with china telecom,
a fixed ip, will cost 2099/1699/899 per month,
it's not worth to pay for that.
so, i write a script for a workaround,
it will update our server's ip ervery hour to
github.
to login our server, please check the [link](https://github.com/ddns/brick/blob/master/ip):

```
https://github.com/ddns/brick/blob/master/ip
```

需要提醒一下，我的SSH服务端口号是`6622`，并非
通常的`22`号端口。
如果你想登陆我的电脑，可以按照下面我提供的账号。
有问题也可以与我联系：
note that, our ssh port is `6622`, not 22.
for account, please email me:

```
Kevin Du Huanpeng
u74147@gmail.com
```

or use this guest account:

```
username: guess
password: db75356f14646a4bca7b712f2128435e97f55c17
```

the eval board is attached on `/dev/ttyS0`.
the control board is attached on `/dev/ttyUSB0`.
but mostly, you just need to type

```
$ screen -x
```

and press `ctrl-a, ctrl-a` to switch between the
asm9260t-evk board serial and the control board's
console.
