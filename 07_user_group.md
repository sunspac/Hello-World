# USER AND GROUP ADMINISTRATION
#### Some Important Points related to Users:
1. Users and groups are used to control access to files and resources
2. Users login to the system by supplying their username and password
3. Every file on the system is owned by a user and associated with a group
4. Every user of the system is assigned a unique user ID number UID
5. Users name and UID are stored in /etc/passwd
6. User’s password is stored in /etc/shadow in encrypted form.
7. Users cannot read, write or execute each other’s files without permission.

## In Linux there are three types of users.

1. Super user or root user
   
Super user or the root user is the most powerful user. He is the administrator user.

2. System user

System users are the users created by the softwares or applications. For example if we install
Apache it will create a user apache. These kinds of users are known as system users.

3. Normal user
   
Normal users are the users created by root user. They are normal users like Rahul, Musab etc.
Only the root user has the permission to create or remove a user.
