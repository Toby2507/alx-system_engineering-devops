# Second batch of executables

## 0-iam_betty

This executable switches the current user to the user betty.
- You should use exactly 8 characters for your command (+1 character for the new line)
- You can assume that the user betty will exist when we will run your script.

## 1-who_am_i

This executable prints the effective username of the current user.

## 2-groups

This executable prints all the groups the current user is part of.

## 3-new_owner

This executable changes the owner of the file hello to the user betty.

## 4-empty

This executable creates an empty file called hello.

## 5-execute

This executable adds execute permission to the owner of the file hello.

## 6-multiple_permissions

This executable adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

## 7-everybody

This executable adds execution permission to the owner, the group owner and the other users, to the file hello.

## 8-James_Bond

This executable sets the permission to the file hello as follows:
- Owner: no permission at all
- Group: no permission at all
- Other users: all the permissions

## 9-John_Doe

This executable sets the mode of the file hello to this:
```bash
 -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
```

## 10-mirror_permissions

This executable sets the mode of the file hello the same as olleh’s mode.

## 11-directories_permissions

This executable adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
Regular files should not be changed.

## 12-directory_permissions

This executable creates a directory called my_dir with permissions 751 in the working directory.

## 13-change_group

This executable changes the group owner to school for the file hello.