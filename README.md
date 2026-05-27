**0-iam_betty**: Switches the current user to `betty`.
* **1-who_am_i**: Prints the effective username of the current user.
* **2-groups**: Prints all the groups the current user is part of.
* **3-new_owner**: Changes the owner of the file `hello` to `betty`.
* **4-empty**: Creates an empty file named `hello`.
* **5-execute**: Adds execute permission to the owner of the file `hello`.
* **6-multiple_permissions**: Adds execute permission to owner/group, and read permission to others for `hello`.
* **7-everybody**: Adds execution permission to everyone for `hello` (no commas used).
* **8-James_Bond**: Sets permissions of `hello` to no permissions for owner/group, and all permissions for others.
* **9-John_Doe**: Sets the mode of `hello` to `-rwxr-x-wx`.
* **10-mirror_permissions**: Replicates `olleh`'s permission mode onto `hello`.
* **11-directories_permissions**: Adds execute permission to all subdirectories in the current directory for all users.
* **12-directory_permissions**: Creates a directory `my_dir` with `751` permissions.
* **13-change_group**: Changes the group owner of `hello` to `school`.
* **14-change_owner_and_group**: Changes owner to `vincent` and group to `staff` for all contents in the working directory.
* **15-symbolic_link_permissions**: Changes owner and group owner of a symbolic link `_hello`.
* **16-if_only**: Changes owner of `hello` to `vincent` only if it is currently owned by `guillaume`.
