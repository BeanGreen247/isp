# isp

There are two versions
- base - the main hosts file for both Linux and Windows
  - hosts - The Linux version
  - hostsWindows - The Windows version
- Tweaked - the Tweaked hosts file for both Linux and Windows
  - hostsTweaked - The Linux version
  - hostsWindowsTweaked - The Windows version

The main difference is that the Tweaked version is a cleaner version with allowed social medias such as Facebook, Instagram and Pinterest.

### Linux

/etc/hosts to block all of the ad sites, porn and general junk
```
sudo wget -O /etc/hosts https://raw.githubusercontent.com/BeanGreen247/isp/master/hosts
```
or
```
sudo wget -O /etc/hosts https://raw.githubusercontent.com/BeanGreen247/isp/master/hostsTweaked
```

### Windows

Open this link https://raw.githubusercontent.com/BeanGreen247/isp/master/hostsWindows

or

Open this link https://raw.githubusercontent.com/BeanGreen247/isp/master/hostsWindowsTweaked

Save file as and in the open dialog navigate to here `C:\Windows\System32\drivers\etc` and save the file by replacing the original and make sure the file type says `File`

If that does not work open Command prompt as Administrator and type in the following example with VSCodium `C:\Users\<UserNameHere>\AppData\Local\Programs\VSCodium\VSCodium.exe C:\Windows\System32\drivers\etc`

Can be done with any editor that allows elevated privileges. VSCodium is one.
