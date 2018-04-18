# icinga-role
A role for provisioning Icinga2

This builds on manual work done by JamesJ and Martyn to install a quick POC 
icinga2 system, to automate the install, and apply fixes to LDAP user lookups.

The related ansible role icinga2-register is to allow hosts to register 
themselves and what services they require monitoring with icinga2 via the API
provded by Icinga2 installations created with this role.

The related hapsql branch of the postgres-role is for setting up postgres in
a HA pair for the back-end database of icinga (possibly other things). We 
set the back-end storage of Icinga to be postgres here to link to that stuff.

