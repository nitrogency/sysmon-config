# sysmon-config | A Sysmon configuration file for everybody to fork #

This fork adds additional logging settings, related to LSASS, SMB and others.



## Use ##
### Install ###
Run with administrator rights
~~~~
sysmon.exe -accepteula -i sysmonconfig-export.xml
~~~~

### Update existing configuration ###
Run with administrator rights
~~~~
sysmon.exe -c sysmonconfig-export.xml
~~~~

### Uninstall ###
Run with administrator rights
~~~~
sysmon.exe -u
~~~~

## Required actions ##

### Prerequisites ###
Highly recommend using [Notepad++](https://notepad-plus-plus.org/) to edit this configuration. It understands UNIX newline format and does XML syntax highlighting, which makes this very understandable. I do not recommend using the built-in Notepad.exe.


## Sources which were used ##
https://www.splunk.com/en_us/blog/security/you-bet-your-lsass-hunting-lsass-access.html
https://learn.microsoft.com/en-us/windows/win32/procthread/process-security-and-access-rights?redirectedfrom=MSDN
https://rootdse.org/posts/understanding-sysmon-events/#event-id-10-processaccess
