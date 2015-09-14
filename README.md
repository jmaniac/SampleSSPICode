# SampleSSPICode
Sample SSPI Code from MSDN

This is the code from https://msdn.microsoft.com/en-us/library/windows/desktop/aa379449(v=vs.85).aspx, 
with the fixes suggested by the "Community Additions" applied. It should build cleanly in VS (I used 
VS 2015 CTP). To run it, set the ServerName and ClientName macros in Client.cpp; and build the sln. 
Then open two Powershell terminals: Run "Server.exe" in the first; then run "Client.exe" in the second. 

[![Build status](https://ci.appveyor.com/api/projects/status/ip4xl48kp660758n?svg=true)](https://ci.appveyor.com/project/sishtiaq/samplesspicode)


