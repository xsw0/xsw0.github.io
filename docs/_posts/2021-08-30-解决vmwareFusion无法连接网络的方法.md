```
vmware fusion could not connect 'ethernet0' to virtual network '/dev/vmnet8'

sudo rm /Library/Preferences/SystemConfiguration/preferences.plist
sudo rm /Library/Preferences/SystemConfiguration/NetworkInterfaces.plist
sudo killall -9 configd
```
