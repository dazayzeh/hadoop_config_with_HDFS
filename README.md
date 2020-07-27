# hadoop_config_with_HDFS
Integrating HDFS into Hadoop Standalone setup!

## Setup
1. Enable remote login (in sharing on mac)
2. Run `ssh localhost` and should see somthing like: `Last login: Fri Jul 24 19:29:04 2020`
3. copy `core-site.xml` and 'hdfs-site.xml'
4. Run `which hdfs' and you should see something like: `/Users/username/hadoop/hadoop-2.7.7/bin/hdfs`
5. format the namenode: `hdfs namenode -foramte`
6. run `start-dfs.sh` then `jps`
  And you should see the Hadoop FileSystem UI up and running at - http://localhost:50070/dfshealth.html#tab-overview 
7. Now you can run `hdfs dfs` to see all the commands that FS shell provides to interact with data in HDFS. 
8. At the end run `stop-dfs.all` 

  
