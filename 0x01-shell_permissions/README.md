1. su command will temporarily change user to betty.
2. id -un will print a script that prints the effective username of the current user.
3. id -nG will print script that prints all the groups the current user is part of.
4. sudo chown betty hello - will changes the owner of the file hello to the user betty.
5. touch hello will creat an empty file.
6. chmod u+x hello wil add execution permission file hello.
7. chmod 754  hello will adds execute permission to the owner and the group owner, and read permission to other users, to the file hello8. chmod ugo+x hello will adds execution permission to the owner, the group owner and the other users, to the file hello
9. chmod 007 hello will sets the permission to the file hello as follows,Owner: no permission at all,Group: no permission at all,Other users: all the permissions.
10. chmod 753 hello will sets the mode of the file hello to this.
