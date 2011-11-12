gitolite-hipchat-notification
==============================

HipChat notification of activity for Gitolite hosted Git servers.

Installation
------------

1. Copy files to your gitolite user's .gitolite/hooks/common folder
2. Rename config.yml.example to config.yml, and fill in your HipChat account information
3. Re-run "gl-setup" to propogate the hooks to each repo's hook folder

References
----------

edouard's Campfire hook: https://github.com/edouard/campfire-git-post-receive-hook
