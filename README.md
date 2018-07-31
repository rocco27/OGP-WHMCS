With this files you will be able to use WHCMS as billing panel for OGP.

I've been added 4 custom fields and 2 config options that you need to configure in WHMCS.

Custom fields:
"Server name"
"RCON password"
"FTP password"

Config options:
"Slots"
"Debranding"

The server brand will be the Panel name.
The module will use the client email as the user name.

NEW**
WHMCS mod has been rewritten.
Updating files from old version is completely discouraged, updating them won't work at all, but if you still wanted to update you will need:
- Before updating files:
"Terminate" all services and remove the table ogp_whmcs from OGP database.
- After updating files:
Reconfigure all products and "Create" all services again.

NEW**
For TS3 product, the API will create virtual TS3 servers if there is a TS3 host in the Panel.

NEW**
Added an email notification when a new service is created, for more information read "Email notification.txt" file.
