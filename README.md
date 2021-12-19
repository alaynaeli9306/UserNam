# UserNam
#RequireAdmin ; Script Start - Add your code below here Local $sUserName = "" Local $sPassword = "" Local $sDomain = ""  RunAs($sUserName, $sDomain, $sPassword, 0, 'msiexec /i "C:\Temp\WindowsAgent.msi" /quiet')
