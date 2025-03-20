# cp

C\Downloads> powershell -Command "(New-Object System.Net.WebClient).DownloadFile('https://github.
elease/download/v4.1.dev1/winpmem64.exe', 'C:\Users\win7\WinPMEM.exe')"
loadFile" with "2" argument(s): "The underlying connection was closed: An unexpected error occur

[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12

Invoke-WebRequest -Uri "https://github.com/Velocidex/WinPmem/releases/download/v4.1.dev1/winpmem64.exe" -OutFile "C:\Users\win7\WinPMEM.exe"



t.WebClient).DownloadFile <<<< ('https://github.com/Velocidex/WinPmem/release/download/v4.1.dev1
ers\win7\WinPMEM.exe')
     : NotSpecified: (:) [], MethodInvocationException
orId : DotNetMethodException
