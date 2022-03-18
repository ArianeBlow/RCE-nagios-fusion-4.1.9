# RCE-nagios-fusion-4.1.9
Authentified Remote Code Execution on Nagios Fusion 4.1.9 product 

Exploit chain : 
Unsecure file uplaod.
Unsecure acces controle.
Remote code execution.

An authentified Remote Code Execution vulnerability was found in nagios fusion 4.1.9.

An admin can upload any file via the dashlet file upload fonction and can call this uploaded file via the "login componnent" installed by default on every instance. Result a remote code execution when this (bad) admin uplaod a php script and execute this script when visiting the LOGIN page.

