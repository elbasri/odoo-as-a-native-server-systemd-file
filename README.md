# odoo-as-a-native-server-systemd-file
create a file using : sudo nano /lib/systemd/system/odoo.service

save => reload:
''''''''
$ sudo systemctl daemon-reload

then use it as follow: 
''''''''
$ sudo systemctl start odoo.service

$ sudo systemctl status odoo.service

$ sudo systemctl enable odoo.service
''''''''

https://www.nacer.ma
