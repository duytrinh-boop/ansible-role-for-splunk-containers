This directory path is a place to put all your splunk licenses.

This directory path is defined in the ansible variable
license_files_dir_path: "{{ role_path }}/files/splunk_licenses"

See the task named configure_license.

It is possible to encrypt the license file, so that it is inaccessible to unauthorized users.
use the command:
ansible-vault encrypt <license_file_name>
In the prompt, use the same password which was used to encrypt ../../../environments/vault.yml