
| Links |
| --- |
| [Bitwarden Repo](https://mobileapp.bitwarden.com/fdroid/repo?fingerprint=BC54EA6FD1CD5175BCCCC47C561C5726E1C3ED7E686B6DB4B18BAC843A3EFE6C) |
| [Bromite Repo](https://fdroid.bromite.org/fdroid/repo?fingerprint=E1EE5CD076D7B0DC84CB2B45FB78B86DF2EB39A3B6C56BA3DC292A5E0C3B9504) |
| [IzzyOnDroid Repo](https://apt.izzysoft.de/fdroid/repo?fingerprint=3BF0D6ABFEAE2F401707B6D966BE743BF0EEE49C2561B9BA39073711F628937A) |
| [GTK - Materia Blackout](https://www.xfce-look.org/p/1381066/) |
| [GTK - Sweet Dark](https://www.xfce-look.org/p/1253385/) |


### Sysytem App (Android)
- List packages :
```
adb shell pm list packages | grep '<keyword>'
```
- Uninstall package (keep data and cache) :
```
adb shell pm uninstall -k --user 0 <package>
```
- Reinstall package :
```
adb shell pm install-existing <package>
```


### Revert Pushed Commit -
- First locally reset commit you want to remove: `git reset`
- Then make changes and create new commit
- Then push changes forcefully: `git push -f`

**Note:**<br>
For this to work you will have to temporarily allow force pushing on the branch youre pushing to.<br>
This can be done in the settings of github project.
