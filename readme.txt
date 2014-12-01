hbase-standalone branch contains configuration of the local environment, zookeeper is not used. Coprocessor should be located in $HBASE_HOME/ext folder. Make sure you start Hbase master before running hbase shell. (~/bin/start-hbase.sh)

hbase-distributed branch contains configuration of hbase using zookeeper installed locally. Coprocessor should be located  in $H
BASE_HOME/ext folder. To be using this configuration zookeeper server should be started first. Then hbase master has to be started.

hbase-dev branch has configuration to connect to the external hbase (dev env in D2L). Just start hbase shell.

hbase-cert branch has configuration to connect to the external hbase (cert env in D2L).Just start hbase shell.

