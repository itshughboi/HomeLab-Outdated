1. You will need to use either DNS name or public IP for the WG_HOST
2. Port forwarding for UDP 51820 must be setup to point to the server hosting wg-easy
3. Should also setup reverse proxy entry for it just so web interface has SSL encrypted connection
4. To add a device, you will download the config file, put it in its proper directory on the client (depends on the OS)
and then run `wg-quick up (client name in wg interface)`

    If everything worked, if you run `ip -4 -brief a` you should see your wireguard IP and the interface will show connectivity
   and network statistics
