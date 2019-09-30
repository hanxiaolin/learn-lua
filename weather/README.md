# 天气预报
 命令行接收用户的城市名，请求天气预报网, 返回最近一个礼拜的天气
 
# 实现
使用luarocks安装包
1. cjson解析json
2. luasocket发起http请求
3. lua-zlib解码gizp安装
4, lua-iconv编码转换