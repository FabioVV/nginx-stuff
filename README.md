# nginx-stuff
Just saving some nginx stuff

# Examples for my fish memory

- Install certbot  and the nginx plugin
`sudo apt install certbot python3-certbot-nginx`


- Obtain and install the certificates
`sudo certbot --nginx -d domainhere.com -d www.domainhere.com`

then, certbot will link manually the keys to the default nginx site
