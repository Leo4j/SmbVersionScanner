# SmbScanner
A Smb Scanner written in powershell
Extracted from [PingCastle](https://www.pingcastle.com) and adapted to fit in a script.

Check for SMBv1 and SMBv2 (SMBv3 is a dialect of SMBv2)

## # Example Usage

```
iex(new-object net.webclient).downloadstring('https://raw.githubusercontent.com/Leo4j/SmbVersionScanner/refs/heads/master/smbscanner.ps1')
```
```
Get-SMBVersion -Targets "DC01.ferrari.local"
```
```
Get-SMBVersion -Targets "DC01.ferrari.local","Workstation-01.ferrari.local","Workstation-02.ferrari.local"
```
```
Get-SMBVersion -Targets "192.168.0.25"
```
```
Get-SMBVersion -Targets "10.0.2.0/24"
```
```
Get-SMBVersion -Targets "10.0.2.0/24" -SMBv1Only
```
