| `0-iam_betty` | Switches the current user to the user `betty`. |
| `1-who_am_i` | Prints the effective username of the current user. |
| `2-groups` | Prints all the groups the current user is part of. |
| `3-new_owner` | Changes the owner of the file `hello` to the user `betty`. |
| `4-empty` | Creates an empty file called `hello` in the working directory. |
| `5-execute` | Adds execute permission to the owner of the file `hello`. |
| `6-multiple_permissions` | Adds execute permission to the owner and group, and read permission to others, for the file `hello`. |
| `7-everybody` | Adds execution permission to the owner, group, and other users for the file `hello` (without commas). |
| `8-James_Bond` | Sets permissions for `hello` to: no permissions for owner/group, all permissions (`rwx`) for others. |
| `9-John_Doe` | Sets the explicit file mode of `hello` to `-rwxr-x-wx`. |
| `10-mirror_permissions` | Sets the mode of the file `hello` to match the exact permissions of the file `olleh`. |
| `11-directories_permissions` | Adds execute permission to all subdirectories of the current directory for all users, without changing regular files. |
| `12-directory_permissions` | Creates a directory called `my_dir` with `751` permissions in the working directory. |
| `13-change_group` | Changes the group owner of the file `hello` to `school`. |
| `14-change_owner_and_group` | Changes both owner to `vincent` and group to `staff` for all files and directories in the working directory. |
| `15-symbolic_link_permissions` | Changes the owner and group owner of the symbolic link `_hello` to `vincent` and `staff`. |
| `16-if_only` | Changes the owner of `hello` to `vincent` only if it is currently owned by `guillaume`. |
