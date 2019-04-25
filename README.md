# ReadConfig
解析常见的配置文件（ini、json、yaml等）

1.使用
1）直接down下来后将，ReadConfig复制到项目根目录
2）在需要用到配置文件的参数值时.py，引入包
from ReadConfig import read_ini
然后调阅获取函数，如 PARA = get_conf(),以PARA['参数名']的方式引用


2.注意
1）目前暂时只支持ini的格式，
2）ini的配置文件名现默认为appsettings.ini,如有需要在read_*.py中找到对应代码进行更改
3）配置文件中 每个参数名不能相同，否则引用会出问题
