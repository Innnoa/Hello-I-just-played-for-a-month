close_wait代表在服务端接收到客户端close的请求后,等待本机调用close()的一个过程
![[Pasted image 20250430123245.png]]

即异步操作的过程,那么可以认为如果没有这段异步操作,则没有close_wait
