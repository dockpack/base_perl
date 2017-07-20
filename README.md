bbaassssiiee.artifactory
=========

Perl - The practical eclectic rubbish lister. Perl development.

Requirements
------------

This role was built for Ubuntu Trusty, Debian, or RedHat systems like RHEL 6, Centos 6.
It needs bbaassssiiee.base_java8.

Role Variables
--------------

perl\_modules: CPAN modules for installation. Abstracts the distribution.

perl\_rpms: Pre-compiled module packages for RedHat-like systems

perl\_apts: Pre-compiled module packages for Debian-like systems


Dependencies
------------
cpanminus is included in the role, this goes in /usr/local/bin/cpanm

bbaassssiiee.base\_cplusplus

bbaassssiiee.base\_common


Example Playbook
----------------
For a complete example with this role check out my buildserver:
git clone https://github.com/bbaassssiiee/buildserver.git

Example of how to use this role:

    - hosts: servers
      roles:
         - { role: bbaassssiiee.base_perl }

License
-------

MIT

Author Information
------------------
Bas Meijer @bbaassssiiee
