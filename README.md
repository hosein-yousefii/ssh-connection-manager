# ssh-connection-manager


[![GitHub license](https://img.shields.io/github/license/hosein-yousefii/ssh-connection-manager)](https://github.com/hosein-yousefii/ssh-connection-manager/blob/master/LICENSE)
![LinkedIn](https://shields.io/badge/style-hoseinyousefi-black?logo=linkedin&label=LinkedIn&link=https://www.linkedin.com/in/hoseinyousefi)


This is a simple tool for managing ssh connections on commandline.

DevOps engineers use ssh on a daily basis in order to connect to servers so, having a tool to group connections would be great.

### Benefits of using SSC

- Simple to use
- Copy to/from node
- Add new node in 5 sec
- Able to use private key
- Able to backup & restore
- Multi group connections

# How it works in a minute

![](https://github.com/hosein-yousefii/ssh-connection-manager/blob/main/ssh-connection-manager.gif)

# USAGE

You are able to change the configuration file in the script but, the default is $HOME/.ssc.conf.

```
chmod +x ssc
ln -s $PWD/ssc /usr/bin/
```

# HOW TO

This is a simple help.

In order to see the help menu

```
ssc
# or
ssc -h
```

If you want to add a new node

```
ssc -a
```

For the list of servers:

```
# To see the list first then connect.

ssc

# Directly connect without list

ssc sample
```

To copy from/to nodes:
ATTENTION: Nodes should exist on the list.

```
# You have 2 options

# ssc -c Host PathOnHost PathOnLocal

# ssc -c PathOnLocal Host PathOnHost


# Example:

ssc -c /opt/file.txt sample /tmp       # Copy /opt/file.txt to sample node on the /tmp path.

ssc -c sample /etc/sample /tmp         # Copy sample directory from sample node to local /tmp path.
```


# CONTRIBUTE

Do you want to contribute so, don't waste your time and send me an email: Yousefi.hosein.o@gmail.com

