# Cisco Industrial Network Director SMS Alerting

This project utilises Cisco Industrial Network Director (IND) - a network management tool specifically for operational technology networks, this script acts as an extension of Industrial Network Director to allow for the inbuilt alerts to be sent via an SMS. When a new alert is recieved on Industrial Network Director this script will utilise the Twilio API

https://www.cisco.com/c/en/us/products/cloud-systems-management/industrial-network-director/index.html

Typically management of these networks can either be at a site level where operational engineers may not include tools such as Industrial Network Director in their day to day workflows. Therefore building this extension with SMS will notify OT users proactively to alert and reduce time falt finding

Prerequsites for this project - Python 2.7 or later, Twilio account

## Steps

#### Step 1
