Role Name
=========

Ansible role to install OWASP Threat Dragon Desktop

Requirements
------------

Debian (amd64) 

Role Variables
--------------

threat_dragon_version: 1.6.1
threat_dragon_app_name: threat-dragon-desktop
threat_dragon_artifact_url: 'https://github.com/OWASP/threat-dragon/releases/download/v{{ threat_dragon_version }}/{{ threat_dragon_app_name }}_{{ threat_dragon_version }}_amd64.deb'
threat_dragon_deb_file: 'threat_dragon.deb'
threat_dragon_download_path: /home/arun


License
-------

Apache-2.0

