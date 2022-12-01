0x01-shell_permissions

Script:
1) 0-iambetty
 - Switches the current user to BETTY. 
   [You should use exactly 8 characters for your command (+1 character for the new line
  [You can assume that the user betty will exist when we will run your script]

2) 1-who_am_i
 - prints the effective username of the current user.

3) 2-groups
 - prints all the groups the current user is part of.

4) 3-new_owner
 - changes the owner of the file hello to the user betty.

5) 4-empty
 - creates an empty file called hello.

6) 5-execute
 - adds execute permission to the owner of the file hello.

7) 6-multiple_permissions
 - adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

8) 7-everybody
 - adds execution permission to the owner, the group owner and the other users, to the file hello.

9) 8-James_Bond
 - sets the permission to the file hello as follows:
   [Owner: no permission at all]
   [Group: no permission at all]
   [Other users: all the permissions]
