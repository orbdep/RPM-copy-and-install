# RPM copy and install

Change the servers in the serverlist, and add the username/password. then edit the main.yml in the rpmcopyinstall directory with the location both on your ansible server, and the target location on the boxes that it will be copied to.

Then run the playbook, like this:

	ansible-playbook -i hosts.ini rpmcopyinstall.yml -v
