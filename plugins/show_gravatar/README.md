#Show Gravatar

This is plugin for Roundcube webmail client which
displays gravatar for sender in every message.

Its a fork of original Kepi.cz plugin, but will be adapt to handle photos from directory
    https://github.com/kepi/show-gravatar

##Install
=======
* Place 'show_gravatar' plugin directory into plugins directory of RoundCube/Simplemail
* Add show_gravatar to $rcmail_config['plugins'] in your RoundCube config

##TODO

- Add setting page
  - Type of gravatar, from gravatar site or gravatar enterprise url/ldap
    - of course dependending a url for enterprise gravatar
    - bach response fo loading of gravatar from a directory url ftp/http
  - <del>enable/disable per user basis</del>
  - <del>different gravatar sizes</del>
  - <del>support for gravatar ratings</del>
  - <del>enable/disable on preview pane</del>
  - <del>enable/disable on show message</del>
- <del>Show gravatar in address book</del>
- Caching maybe

