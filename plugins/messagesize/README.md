Roundcube Webmail MessageSize
=============================

This plugin limits the overall size of a message 
by capping the cumulative size of all the attachments.

Its a fork of original JhonDoe plugin, but feature some translations updates

Install
=======
* Place 'messagesize' plugin directory into plugins directory of RoundCube/Simplemail
* Add messagesize to $rcmail_config['plugins'] in your RoundCube config

Config
======
The default config file is plugins/messagesize/config.inc.php.dist
Only rename this to plugins/messagesize/config.inc.php 
if want to change default of 10Mb

'max_message_size'
This is the maximum overall size of all the attachments added to a message
The value can be:
* A number (in bytes): 2097152 (for 2MB)
* A string: "10MB" (the units K, KB, M, MB, G and GB are supported, they are not case sensitive)