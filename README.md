# ssh-connection-manager


[![GitHub license](https://img.shields.io/github/license/hosein-yousefii/ssh-connection-manager)](https://github.com/hosein-yousefii/ssh-connection-manager/blob/master/LICENSE)
![LinkedIn](https://shields.io/badge/style-hoseinyousefi-black?logo=linkedin&label=LinkedIn&link=https://www.linkedin.com/in/hoseinyousefi)


This is a simple tool for managing ssh connections on commandline.

DevOps engineers use ssh on a daily basis in order to connect to servers so, having a tool to group connections would be great.

### Benefits of using SSC

- Simple to use
- connect to a node by selecting through menu or direct with their name
- Add new node in 5 sec
- Able to use private key
- Able to backup & restore
- Multi group connections


# USAGE

You are able to change the configuration file in the script but, the default is $HOME/.ssc.conf.

```
chmod +x ssc
ln -s $PWD/ssc /usr/bin/
```

# HOW TO

This gift shows you 90% of the usage:

![](https://github.com/hosein-yousefii/ssh-connection-manager/blob/main/ssc-help.gif)

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
ssc -l
```

# CONTRIBUTE

Do you want to contribute so, don't waste your time and send me an email: Yousefi.hosein.o@gmail.com

