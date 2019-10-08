# mynote
this is note


fail2ban linux防爆破

Firewalld linux动态防火墙

solr 搜索服务器

# PHP

* 关于array数组(二维数组)里面的数据类型问题处理
由于从json_decode(xxx)转换的子对象是object类型,所以在使时要注意该问题,可使用json_decode(xxx,true)全部转成array形式
该问题会导致使用数值合并方法是,子数据类型会有array和object的情况,合并的解决方法是统一子数据格式,例如都先json_encode()后重新json_decode()再合并


# 正则表达式

* (\[+:\w+\]|\[+:+\]|\[+(/vc_|vc_)+\w+\]) 例:[vc_xx]
* \[(?:[^\"'>]|\"[^\"]*\"|'[^']*')*\] 例[xxxxx]
* \[[^\]]+\] 未测试项(先做笔记)
