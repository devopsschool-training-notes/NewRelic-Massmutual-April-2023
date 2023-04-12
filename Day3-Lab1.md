## Step 1 - Install NewRelic Infra Agent

## Step 2 - Install and Start Apache

## Step 3 - Enable NewRelic Agent for Apache Log
- Go to /etc/newrelic-infra/logging.d
- Add a file called apache.log with following content

logs:
  - name: apache access log
    file: /var/log/apache2/access.log
 
## Step 4 - Restart NewRelic Infra Agent	
$ systemctl restart newrelic-infra

## Step 5 - Create some traffic on apache 

## Step 6 - Validates logs data in newRelic UI

## Step 7 - Search which matters to you.
