# Install apache2 in Ubuntu
```
$ apt install apache2
$ which apache2
$ systemctl start apache2
$ systemctl status apache2
$ curl http://localhost
```

# How to install mod_status on your Apache servers and enable ExtendedStatus?
https://www.devopsschool.com/blog/how-to-install-mod_status-on-your-apache-servers-and-enable-extendedstatus/

# How to install Apache Integration in newrelic agent?

```
$ curl -Ls https://download.newrelic.com/install/newrelic-cli/scripts/install.sh | bash && sudo  NEW_RELIC_API_KEY=NRAK-L1OD0ZKZ2XEIA8I01IGMXOD43XN NEW_RELIC_ACCOUNT_ID=3889913 /usr/local/bin/newrelic install -n apache-open-source-integration
```

# How to configure Apache Integration in newrelic agent?
```
$ vi /etc/newrelic-infra/integrations.d/apache-config.yml
- Observe and Understand
```
# Generate a traffic

<img width="866" alt="image" src="https://user-images.githubusercontent.com/44023974/230897723-3d34d936-69de-4429-b8b5-df0cb94d161b.png">


