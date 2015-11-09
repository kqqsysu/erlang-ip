# erlang-ip
Erlang lib for 17MonIP(http://www.ipip.net/download.html)

#How To Use
$ make
$ erl -pa ebin
1> monip:test("115.29.161.118").

monip:104 Ip:115.29.161.118 -> 中国     浙江    杭州 
ok

2> monip:find("115.29.161.118").

{ok,<<228,184,173,229,155,189,9,230,181,153,230,177,159,
      9,230,157,173,229,183,158,9>>}
