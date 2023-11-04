# Create Admin from SSH

Created: November 3, 2023 6:13 PM
Tags: SSH

Here are the options that you have when creating an admin account from ssh as root.

```json
create_admin

# -p : prompt for password
# -r : admin rold
# -s : ssh key
```

Example 1:

```json
lab1# create_admin tcb -r
please wait
Existing Roles:
1: Super User
2: Read Only
3: Web Designer
4: Conference Controller
5: Conference User
6: RG Nets
Enter admin role selection from the list above:
```