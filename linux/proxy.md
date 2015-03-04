
#### PROXY

```

export HTTP_PROXY=http://username:password@ip:port
export HTTPS_PROXY=http://username:password@ip:port

Para apt
nano /etc/apt/apt.conf

Acquire::http::proxy "http://username:password@ip:port";
Acquire::https::proxy "http://username:password@ip:port";
Acquire::socks::proxy "http://username:password@ip:port";

Para o wget
nano /etc/wgetrc
http://username:password@ip:port
```

