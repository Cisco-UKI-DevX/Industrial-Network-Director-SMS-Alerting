# Cisco Industrial Network Director SMS Alerting

## SMS Alerting with Industrial Network Director (Under development)

This project utilises Cisco Industrial Network Director (IND) - a network management tool specifically for operational technology networks, this script acts as an extension of Industrial Network Director to allow for the inbuilt alerts to be sent via an SMS

https://www.cisco.com/c/en/us/products/cloud-systems-management/industrial-network-director/index.html

The challenge however exists in the fact that these networks can be very large and manual creation of discovery profiles is sometimes unfeasible. Therefore with this playbook we have automated part of that process.

With the user providing a csv file of the estimated asset information (IP addressing and discovery profile requried) this playbook is able to automatically create the discovery profiles for the devices it is instructed to discover within the IND tool.

Prerequsites for this project - Python 2.7 or later, Ansible - This project assumes some knowledge of Ansible


This python script utilises Cisco Industrial Network Director to send an SMS to a user when a new device alert occurs on IND. 

When the user runs the python script they are queried for information around their IND setup, Twilio account and phone number. The script then proactively monitors IND to send an SMS anytime a new alert is encountered.
