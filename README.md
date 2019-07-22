# Cisco Industrial Network Director SMS Alerting

This project utilises Cisco Industrial Network Director (IND) - a network management tool specifically for operational technology networks, this script acts as an extension of Industrial Network Director to allow for the inbuilt alerts to be sent via an SMS. When a new alert is recieved on Industrial Network Director this script will utilise the Twilio API

https://www.cisco.com/c/en/us/products/cloud-systems-management/industrial-network-director/index.html

Typically management of these networks can either be at a site level where operational engineers may not include tools such as Industrial Network Director in their day to day workflows. Therefore building this extension with SMS will notify OT users proactively to alert and reduce time falt finding

> Prerequsites for this project - Python 2.7 or later, Twilio account

> To run these scripts you will need an instance of Industrial Network Director running. dcloud.cisco.com has an "Cisco Industrial Network Director v3" demo which can be used for this integration or alternatively you can download IND from the cisco.com website, a fresh install has a 90 day trial license. https://software.cisco.com/download/home/286310815/type/286310951/release/1.6.1

## Steps

#### Step 1

The first step to running this project
