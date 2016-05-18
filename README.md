# Oracle_Create-tablespace
How to create tableSpace

#create tablespace
create tablespace tablespaceName
logging
datafile 'D:\oracle\tablespaceName.dbf'
size 50m
autoextend on 
next 50m maxsize 2048m
extent manangement local;

#How to  Create user 
Create user userName identified by password
default tablespace tablespaceName;

#How to grant to user
grant connect,resource,dba to username;
grant dba to username;

