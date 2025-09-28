# Linux Command Activities

## Activity-1 → ls command options

Using man ls, here are the explanations for the flags mentioned:

- ls -b → Prints non-printable characters in file names as octal escape sequences (\xxx).
- ls -c → Sorts files by ctime (last status change) instead of modification time. Also affects -lt.
- ls -d → Lists only directory entries themselves, not their contents (e.g., ls -d /etc just shows /etc).
- ls -e → On some systems, shows access control list (ACL) info (like ls -l --time=atime).
- ls -f → Displays directory contents unsorted (as they are stored). Also implies -a (show hidden files).
- ls -z → Shows SELinux security context for files (useful in security-enabled systems).

---

### Other commands to explore (run on terminal):

- whoami → Prints your current logged-in username.
- pwd → Shows the current working directory.
- cd → Changes directory.
- cd / → Moves you to the root directory.
- cd .. → Moves you one level up (to the parent directory).
- cd <path> → Moves you to the specified path.

---

## Activity-2 → tree command options

Using man tree:

- tree -a → Shows all files including hidden ones (those starting with .).
- tree -d → Lists only directories.
- tree -u → Shows the file owner’s username.
- tree -p → Shows permissions (rwx) for each file/directory.