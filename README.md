This is my clone configuration. I created the repository for backup reasons and if I accidently delete my config, yup that really happened!


![Used rclone Browser version](https://github.com/CHEF-KOCH/RBC/blob/master/Screenshots/About.png?raw=true "About rclone Browser")


### Which versions do I use/prefer?
* [kapitainsky / RcloneBrowser beta versions](https://github.com/kapitainsky/RcloneBrowser/issues/93)
* [rclone beta builds](https://beta.rclone.org/)



## General

![My settings](https://github.com/CHEF-KOCH/RBC/blob/master/Screenshots/Preferences.png?raw=true "Preferences")

### Settings
**Settings** | **Priority** | **Details and Hints**
--- | --- | ---
**rclone location** | Default | I use and prefer the default location:`C:\Users\CHEF-KOCH\AppData\Local\rclone\rclone.exe`.
**rclone.conf location** | Default | The default location seems fine: `C:\Users\CHEF-KOCH\.config\rclone\rclone.conf`.
**Stream command** | Default | I use and prefer MPC-BE (modded version of MPC-HC), with `"C:/Program Files (x86)/MPC-BE/mpc-hc64.exe" -` as command line params.
**Default mount options** | Default | `--vfs-cache-mode writes`
**Default download folder** | Optional | Matter of taste, I typically use the default here too, `C:\Users\CHEF-KOCH\Downloads`.
**Default upload folder** | Optional | `C:\Users\CHEF-KOCH\Uploads`
**Default download options** | Default | `--include *.{png,jpeg,avihevc}`
**Default upload options** | Suggestion | `--exclude *.{tmp,temp,thumbnails,desktop.ini,RARBG_DO_NOT_MIRROR.exe,RARBG.txt,WWW.YTS.AG.jpg,1.jpg,sample.mkv}`
**Default rclone options** | Default | `--fast-list`
**Finished queue script** | None | None (right now)



### Update Notifications
**Settings** | **Priority** | **Details and Hints**
--- | --- | ---
**Check for Rclone Browser updates** | Enabled (Default) | It does not matter if it's enabled or disabled because the original project is no longer under development.
**Check for rclone updates** | Enabled (Default) | Leave it enabled.



## Interface

### System Tray
**Settings** | **Priority** | **Details and Hints**
--- | --- | ---
**Always show in system tray** | Default | Enabled.
**Close to system tray** | Default | Enabled.
**Start minimised to system tray** | Changed | Disabled.
**Notify about finished transfers** | Changed | Disabled.
**Play sound when transfer finished** | Changed | Disabled, because it's annoying.


### User Interface
**Settings** | **Priority** | **Details and Hints**
--- | --- | ---
**Show folder icons** | Default | Enabled.
**Show file icons** | Default | Enabled.
**Alternating row colours** | Default | Enabled, makes it easier to view the list.
**Show hidden files and folders** | Changed | Enabled.
**Enable dark mode** | Default | Enabled.


## GUI style

**Settings** | **Priority** | **Details and Hints**
--- | --- | ---
**Font size increased by n points** | Changed | 2
**Buttons' style (requires application restart)** | Default | Text and Icon
**Buttons icons size (requires application restart)** | Default | S
**Remotes icons layout** | Default | Tiles
**Remotes icons size** | Default | M
**All icons colour (requires application restart)** | Default | Black



## Proxy

I do not use any extra socks/proxy, since I'm already behind a VPN.
