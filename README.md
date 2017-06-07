# OpenStack
OpenStack based Stuff


Federated Keystone in Docker is available on Docker hub. You can get the container by:

#FOR Identity Provider Keystone
docker run -it 16pj/keystone.idp /bin/bash

#FOR Service Provider Keystone
docker run -it 16pj/keystone.sp /bin/bash

#FOR Service Provider Keystone with glance service
docker run -it 16pj/key_glance /bin/bash

To make the IDP and SP know each other, simply change the /etc/hosts file to add myidp.example.com and mysp.example.com along with the IP addresses.
