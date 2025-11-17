# Firewall Configuration on Web-01

This Bash script configures a new Ubuntu machine to:

- Install Nginx
- Add a custom HTTP response header `X-Served-By` with the server hostname
- Ensure both web-01 and web-02 return this custom header
