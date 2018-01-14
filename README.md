# System-monitor-script

This is a system monitor script used by my server.
It displays the following information if called:
1.  Current release
2. The status of the configured sensors. In order to use it, first you need to configure your system's sensors:
https://askubuntu.com/questions/53762/how-to-use-lm-sensors
Modify the 'grep' directives to display the information returned by your system.
3. It will display the status of the APC UPS. Also, you can tailor this to your needs if you have a different UPS.
Here's how to configure the APC UPS:
https://www.cyberciti.biz/faq/debian-ubuntu-centos-rhel-install-apcups/
4. Will querry the S.M.A.R.T. status of all existing disks and displays it.
5. It will display the RAID array status.


Note:
This is a script i've created to display the status of my server. It can be freely modified and edited to suit your neeeds.
If you try to use it on a different system without tailoring it to your needs might display innacurate results or some parts might not work at all.
Do not use it unless you fully understand what it does.
