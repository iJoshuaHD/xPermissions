# xPermissions

![xPermissions](https://raw.githubusercontent.com/64FF00/xPermissions/master/xPermissions.png)

## Features

- Uses the new API in PocketMine-MP Alpha_1.4
- Set up permissions for different groups
- Multi-world permissions
- Multi-group inheritance system
- Group aliases
- Support of prefixes, suffixes, world name, and chat format
- Custom build permissions that can deny a group building rights for a world

## Commands

| Command | Parameters |
| ------- | ---------- |
| /xperms group create | [GROUP_NAME] |
| /xperms group list | ... |
| /xperms group remove | [GROUP_NAME] |
| /xperms group setperm | [GROUP_NAME], [PERMISSION], (LEVEL_NAME) |
| /xperms group unsetperm | [GROUP_NAME], [PERMISSION], (LEVEL_NAME) |
| /xperms help | ... | 
| /xperms info | ... | 
| /xperms plist | (PAGE_NUMBER / PLUGIN_NAME) | 
| /xperms reload | ... | 
| /xperms user info | [USER_NAME], (LEVEL_NAME) |
| /xperms user setgroup | [USER_NAME], [GROUP_NAME], (LEVEL_NAME) | 
| /xperms user setperm | [USER_NAME], [PERMISSION], (LEVEL_NAME) | 
| /xperms user unsetperm | [USER_NAME], [PERMISSION], (LEVEL_NAME) | 
 
## Permissions

- xperms.group.*
 * xperms.group.create
 * xperms.group.help
 * xperms.group.list
 * xperms.group.remove
 * xperms.group.setperm
 * xperms.group.unsetperm
- xperms.help
- xperms.info
- xperms.plist
- xperms.reload
- xperms.user.*
 * xperms.user.help
 * xperms.user.info
 * xperms.user.setgroup
 * xperms.user.setperm
 * xperms.user.unsetperm
