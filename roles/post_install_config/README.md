Post Install Config
===================
Perform post install configuration steps for [GalaxyNG](https://github.com/ansible/galaxy_ng).

Variables
---------
* `pulp_config_dir`: Directory which will contain Pulp configuration files. Defaults to "/etc/pulp". 
* `pulp_install_dir`: Location of a virtual environment for Pulp and its Python dependencies. Defaults to "/usr/local/lib/pulp". 
* `pulp_user`: System user that owns and runs Pulp. Defaults to "pulp". 
* `pulp_default_admin_password`: Initial password for the Pulp admin. Defaults to "password".
* `pulp_api_host`: Host for connecting to the Pulp API server. Defaults to "127.0.0.1".
* `pulp_api_port`: Port used for connecting to the Pulp API server. Defaults to "24817".
* `pulp_settings_file`: Location of the Django setings files. Defaults to "{{ pulp_config_dir }}/settings.py".
