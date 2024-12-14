# Quilibrium Tools

**Quilibrium for Dummies** 

This script is an all-in-one quil usage software for newcomers.

For installation and first run, please run

    cd /root && rm -f quilibrium_for_dummies.sh && wget https://raw.githubusercontent.com/xt1085/QuilibriumTools/main/quilibrium_for_dummies.sh && chmod +x quilibrium_for_dummies.sh && ./quilibrium_for_dummies.sh



After first run, when you need to reach your node, you need to run only;

    ./quilibrium_for_dummies.sh

    

**Autoinstaller Script for Quilibrium as a Service**

Use below command to install v2.0


    wget -O - https://raw.githubusercontent.com/xt1085/QuilibriumTools/main/install/install_quilibrium_service.sh | bash

    
**Autoupdater**


If you need to update your node from previous version to 2.0, apply below command


    wget -O - https://raw.githubusercontent.com/xt1085/QuilibriumTools/main/update/update.sh | bash

For easy management of your nodes I created some shortcodes. You can import .profile or .bash_profile (Some Debian installations) file and source. Then you can easily query node related infos.

**Check Your Node Visibility**

You can check if your node sees Q Inc Bootstraps. If you don't see you most probably will not get any rewards.

    wget -O - https://raw.githubusercontent.com/xt1085/QuilibriumTools/main/visibility_check.sh | bash
