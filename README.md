# Invoke-Mimikatz.ps1-Version-2.1.1
Invoke-Mimikatz.ps1 Version 2.1.1
Original files from https://github.com/gentilkiwi/mimikatz/files/4167347/mimikatz_trunk.zip

Copied from the original Invoke-Mimikatz.ps1. This is not a new version of the original file and merely changed PEByets64 and PEByetes32 values after Encoding x86 and x64 binaries using $base64string = [Convert]::ToBase64String([IO.File]::ReadAllBytes($FileName))

This was created because some versions of Windows are not compatible with some versions of Mimikatz!
