
This project uses Vagrant to create three virtual machines. Then you can connect to Cloudera Manager to install Hadoop and other tools.

1. Install Vagrant
2. Install git
3. Clone this project.
4. Connect to project directory.
5. Run 'vagrant up'
6. Visit http://10.211.55.100:7180 for the Cloudera Manager utility.
7. Use admin/admin to login.
8. Select Cloudera Standard to use free licenses, then click continue.
9. Click continue.
10. Enter the following IP addresses, one per line, then click search.
  10.211.55.100
  10.211.55.101
  10.211.55.102
11. Click continue.
12. Unselect SOLR and Impala (or don't) then click continue. (If you following this advice, you can't select 'All Services' in step 20 below)
13. Select 'another user' then enter 'vagrant' as the username.
14. Select the 'vagrant' file in this project as the private key file.
15. Click continue.
16. Click ok to continue with no passphrase.
17. Click continue after installation is complete on all three nodes.
18. Click continue after parcels are installed.
19. Click continue after hosts are inspected.
20. Select HDFS, MapReduce, ZooKeeper, HBase, Hive, Oozie, Hue, and Sqoop.
21. Select 'Inspect Role Assignments'
22. Ensure Zookeeper is on 'vm-cluster-node1' (and only there)
23. Ensure NameNode is on 'vm-cluster-node1'.
24. Ensure HBase Master is on 'vm-cluster-node1'.
25. Click continue.
26. Click 'Test Connection'
27. Click continue when all connections have been successful.
28. Click continue after reviewing the configuration settings.
29. Click continue after cluster services have started.
30. You're Done!

Handy URLS

CLOUDERA MANAGER: http://10.211.55.100:7180/
NAME NODE http://10.211.55.100:50070/dfshealth.jsp
JOB TRACKER: http://10.211.55.101:50030/jobtracker.jsp

