Experimental environment: win10 x64     
Software official website:https://safe.2345.cc   
Software version:1.4.0.13033   
Affected Component: 2345FileShre.exe    
  
Although 2345 Security Guard cannot be started by a normal user, its additional program file deletion program 2345FileShre.exe can be started by a normal user. The root cause of this vulnerability is that 2345FileShre.exe did not judge the target file to be used when deleting the target file or directory. Whether the user has write permission or does not use an impersonation token, so that any file or directory can be deleted to achieve local privilege escalation
