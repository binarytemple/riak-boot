

TODO ... 

command to run the 3 node cluster.... 

hint ` start-riak `


stopping `stop-riak`

connecting to nodes `connect-riak-dev*` 

# Cluster Joining 

General
```
riak ping 
```

dev2 and dev3 
```
riak-admin cluster join riak@riak-dev1.riak
```

dev1
```
riak-admin cluster plan 
riak-admin cluster commit 
riak-admin transfers
```

