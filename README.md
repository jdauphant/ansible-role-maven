ansible-role-maven
==================

Ansible role to manage maven

# Support 
- Maven installation from packages for Debian and RedHat families
- Proxy configuration for maven
- Tested on Ubuntu only

# Usage without proxy
```
---
 - hosts: all
   roles:
     - maven
```
# Usage with proxy
```
---
 - hosts: all
   roles:
     - role: maven
       maven_proxies: 
         host: proxy.mydomain.com
         port: 8888
```

# Author
Julien DAUPHANT