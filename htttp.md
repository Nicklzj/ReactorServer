HTTP 请求
GET /pic/1.jpg HTTP/1.1   /r/n
请求头 键值对
Host: 192.168.1.2:6789
（空行一定是空行）
/r/n

GET /?
key-val键值对


POST /HTTP/1.1
请求头 键值对
（空行）
请求体
key=val  json  xml mulitpart/form-data



HTTP响应
四部分为：
·状态行
·消息报头/响应头
·空行
·回复给客户端的数据

HTTP/1.1 200 ok
Content-type: text/plain
Content-Length: 32 (可加可不加)