# Automation to install XOS on cloudlab

1. Modify the `inventory/cloudlab.yml` file to have your cloudlab instance `ctl` node name, and your cloudlab ssh username.

2. Modify the vars in `cloudlab-playbook.yml` to point at your repo/branch/version of XOS.

3. Run the playbook, which updates the system, checks out and installs XOS:

    `ansible-playbook -i inventory/cloudlab.yml cloudlab-playbook.yml`

4. Enjoy your XOS installation.

