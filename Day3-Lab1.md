# COLLECTING A LOG USING NEW RELIC INFRA AGENT DEFUALT SOURCE
- Check this file  - /etc/newrelic-infra/logging.d/logging.yml

<img width="749" alt="image" src="https://user-images.githubusercontent.com/44023974/231421264-f8ed53af-2ba2-4499-8337-aa7e58536f39.png">


# COLLECTING A LOG USING Integration. Example apache integration
- Install Apache Integration
- Rename a file apache-log.yml.example under /etc/newrelic-infra/logging.d
- Restart Infra agent

# CUSTOM LOG COLLECTION METHOD

### Step 1 - Install NewRelic Infra Agent

### Step 2 - Install and Start Apache

### Step 3 - Enable NewRelic Agent for Apache Log
- Go to /etc/newrelic-infra/logging.d
- Add a file called apache.yml with following content

logs:
  - name: apache access log
    file: /var/log/apache2/access.log
 
### Step 4 - Restart NewRelic Infra Agent	
$ systemctl restart newrelic-infra

### Step 5 - Create some traffic on apache 

### Step 6 - Validates logs data in newRelic UI

### Step 7 - Search which matters to you.
