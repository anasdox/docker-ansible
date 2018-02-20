
# Description

This image contains ansible and git to use ansible galaxy ;)

# Versions

```
docker run -it -v $PWD:/app anasdox/ansible-git ansible --version
ansible 2.4.3.0
  config file = None
  configured module search path = [u'/root/.ansible/plugins/modules', u'/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/lib/python2.7/site-packages/ansible
  executable location = /usr/bin/ansible
  python version = 2.7.14 (default, Dec 14 2017, 15:51:29) [GCC 6.4.0]
```

```
docker run -it -v $PWD:/app anasdox/ansible-git git --version
git version 2.15.0
```
