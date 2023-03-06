# HTTP-Caching-Proxy
An http	proxy – a	 server	 whose	 job	 it	 is	 to	 forward	
requests to	the	origin	server	on behalf	of	the	client. <br>
To begin, run the below command in HTTP-Caching-Proxy directory<br>
`sudo docker-compose up`

## Overview
Supports 	GET,	POST,	and	CONNECT. <br>
Cache responses	(when	they	are	200-OK)	to	GET	requests <br>
Able	 to	handle	multiple	concurrent	requests	effectively	using
multiple	 threads. <br>
Can produce	 a	 log	 (in	 /var/log/erss/proxy.log)	 which	 contains	
information	about	each	 request.

