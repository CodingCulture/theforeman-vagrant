# Foreman Vagrant

I've created this box to develop a simple, self-checkout foreman client. I wanted
to use other boxes, but they kept failing on me.

## Howto

1. Vagrant up
2. Vagrant SSH
3. Open up /etc/hosts and add precise32.local to 127.0.1.1 record.
4. ```foreman-installer```
5. exit
6. Edit your hostsfile (with Gas Mask, ...) to include precise32.local and map it to 192.168.33.10
