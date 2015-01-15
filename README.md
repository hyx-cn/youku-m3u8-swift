# youku-m3u8-swift
优酷m3u8地址的swift解析



这个代码基本就是照着网上找到的一份python代码改成的swift代码。

swift就学了几天，该的可能不太规范，讲究吧。

其实我也不想改的。只不过没找到现成的。呵呵。。。

其实我也就是想在app里放优酷，可是我不会啊，只能用mpmovieplayer放m3u8，如果有人会知道怎么处理，劳烦告诉我一下啊亲！！！

这个东西的用法只要把youku.swift导入工程，然后用parse_url函数就能返回。具体用法如下

var new_url = parseUrl("http://v.youku.com/v_show/id_XODMzOTcyNjg0.html") 
println("m3u8: (new_url)")
