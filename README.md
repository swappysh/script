# Script - git-annex-remote-rclone

Wrapper script over `git-annex-remote-rclone` to help integrate and make its usage easier for RoboComp users.

## Commands Available
```
git_tool initremote <remote_name> type=external externaltype=rclone target=<rclone_target_name> prefix=git-annex chunk=50MiB encryption=shared mac=HMACSHA512 rclone_layout=lower
```
```
git_tool add <binary_files> <remote_name>
```
```
git_tool get <binary_files> <remote_name>
```