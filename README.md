Proxy for Dockploy. forwards the requests to web nodes

backends should be in file ext_backends.conf

example:

1.1.1.1:1234;
2.2.2.2:2345;

redirects - in file redirects.conf

example 

server {
  listen 80;
  server_name mydomain1.com;
  return 301 https://mydomain2.com/;
}
