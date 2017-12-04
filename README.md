cron
====


What is does this role do?
--------------------------

This role installs and enables a cron implementation.  By default the
cronie implementation will be used.

Meta
----

Files Managed:
  * /etc/sv/crond
  * /var/service/crond

Defaults Provided:
  * cron_implementation: cronie

Variables Required:
  * None

Optional Variables:
  * cron_implementation: the implementation of cron to install

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * None
