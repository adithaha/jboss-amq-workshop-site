## LAB 01 – INSTALLING JBOSS A-MQ

Installing JBoss A-MQ 6.2 is easy. You'll need to unzip the distribution into the target directory. You can get a JBoss A-MQ distribution from  http://www.jboss.org/products/amq.

1. Create folder `/server/jboss/amq/`
2. Put jboss-a-mq-6.2.0.redhat-133.zip inside that folder
3. Unzip jboss-a-mq-6.2.0.redhat-133.zip
4. This will create jboss-a-mq-6.2.0.redhat-133

You will need to edit a single configuration file after your first install to setup an administrative username and password.
Edit <JBoss A-MQ Home>/etc/users.properties, and uncomment (remove the leading #) the last line. The format is 

```
<username>=<password>,<role>. 
```

For the purposes of this lab, let's use admin/admin.

```
admin=admin,admin
```

That's it! An install so fast, you don't even have time to get a cup of coffee...
