Omada Installer
A script to perform a new install of the TP-Link Omada SDN Controller software on Ubuntu 16.04, 18.04 or 20.04.

Special thanks to @willquill for his Omada Ubuntu 16.04 guide :)

Recommended specs
Ubuntu 20.04
8+ GB disk ( You'll need min 4 GB of free space for MongoDB as found by /u/axel2230 )
1+ GB memory
Install
Connect via SSH or console, run the following command and enjoy a sip of coffee ;)

curl -s https://raw.githubusercontent.com/JORDANDJ41/Omada_SDN_Controller_v5.6.3-installer/main/install-omada-controller.sh | sudo bash
Once finished, complete the setup in your web browser via the URL in the final output.


Status: sudo tpeap status

Start: sudo tpeap start

Stop: sudo tpeap stop

Links
Offical guide: https://www.tp-link.com/us/support/faq/3272/

Guide by @willquill : https://www.reddit.com/r/HomeNetworking/comments/mv1v9d/guide_how_to_set_up_omada_controller_in_ubuntu/ / https://github.com/willquill/omada-ubuntu

Upgrade guide: https://www.tp-link.com/en/omada-sdn/controller-upgrade/
