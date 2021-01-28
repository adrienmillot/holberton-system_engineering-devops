Permissions
---

# Change your ID
To change your ID, on linux, means "change user", for that you shoud type below console:
```bash
su <new user ID>
```

# To know current ID
To know the current ID, you have to type:
```bash
whoami
```

# To know all the groups of your current ID
```bash
groups
```

# To change the owner of a file
```bash
chown betty hello
```

# To create an empty file
```bash
touch <filename>
```

# To change owner,group,user of a file,repository
o: owner
g: group
u: user

To give the execute right to owner to a filename
```bash
chmod o+x <filename>
``` 

#  To change file rights
To change file rights, you have two ways

## First with number
chmod 331 <filename>

first number is for owner
second is for group
and the third is for user

## Second with character
chmod o=rx,g=rx,u=x

w = write
r = read
x = execute
