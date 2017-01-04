# Overview
An ansible playbook to install [MeetMe/newrelic-plugin-agent](https://github.com/MeetMe/newrelic-plugin-agent) on any host.

# How to use
Run following command with your correct parameter
```
ansible-playbook ./newrelic-plugin-agent-for-redis.yml --extra-vars "host=x.x.x.x redis_password=SOME_SUPER_STRONG_PASSWORD newrelic_license_key=YOUR_NEWRELIC_LICENSE_KEY"
```
* **host**: Your ansible host or any single ip address
* **redis_password**: Your redis password that's running
* **newrelic_license_key**: Your newrelic license key
