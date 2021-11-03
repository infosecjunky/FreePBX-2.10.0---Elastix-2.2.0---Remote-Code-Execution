# FreePBX 2.10.0 / Elastix 2.2.0 - Remote Code Execution
### For HTB Beep hints go https://github.com/A1vinSmith/OSCP-PWK/tree/master/HackTheBox/Linux/Beep

Please do the neccesary changes or else the script will not work

Edit the following /etc/ssl/openssl.cnf

at the bottom of the config file make the following changes.

[system_default_sect]
#MinProtocol = DEFAULT@SECLEVEL=2
MinProtocol = None
#CipherString = DEFAULT@SECLEVEL=2
CipherString = None
