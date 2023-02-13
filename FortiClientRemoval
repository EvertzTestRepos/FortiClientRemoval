Get-WmiObject Win32_Product -Filter "name like 'FortiClient'" | Select-Object -ExpandProperty IdentifyingNumber | ForEach-Object { & 'C:\Windows\System32\MSIEXEC.exe' '/x' $_}
