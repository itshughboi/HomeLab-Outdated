curl -o setup-repos.sh https://raw.githubusercontent.com/webmin/webmin/master/setup-repos.sh

sh setup-repos.sh

sudo apt-get install --install-recommends webmin
#login uses server credentials for login. Login how you normally would to the system

Default port is '10000' e.g. ubnt-prod:10000
