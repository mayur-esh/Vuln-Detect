# Vuln-Detect
Vulnerability detection engineering
# Ivanti/Pulse Secure Version Identification:
```
wget https://x.x.x.x/dana-cached/hc/HostCheckerInstaller.osx --no-check-certificate cat HostCheckerInstaller.osx | grep -a "<key>version</key>" -A 1

wget https://x.x.x.x/dana-cached/sc/PulseSecureInstallerService.exe --no-check-certificate cat PulseSecureInstallerService.exe | grep -a "<key>version</key>" -A 1

curl -k https://x.x.x.x/dana-na/nc/nc_gina_ver.txt | grep '<PARAM NAME="ProductVersion" VALUE="'
```
