
#### PROXY

```

export HTTP_PROXY=http://username:password@ip:port
export HTTPS_PROXY=http://username:password@ip:port

nano /etc/apt/apt.conf

Acquire::http::proxy "http://username:password@ip:port";
Acquire::https::proxy "http://username:password@ip:port";
Acquire::socks::proxy "http://username:password@ip:port";

```

