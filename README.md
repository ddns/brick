ip
==

recently, ddns is not working on our server.
and i have just check with china telecom,
a fixed ip, will cost 2099/1699/899 per month,
it's not worth to pay for that.
so, i write a script for a workaround,
it will update our server's ip ervery hour to
github.
to login our server, please check the [link](https://github.com/zhang3/ip/blob/test/ip):

```
https://github.com/ddns/brick/blob/master/ip
```

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
