# create enterprise WiFi for iwd

## create the directory and edit the file

sudo mkdir -p /var/lib/iwd

sudo nvim /var/lib/iwd/YourSSID.8021x *make sure to change the SSID to the actual WiFi name*

## enter this into the file created

[Security]

EAP-Method=PEAP

EAP-Identity=your_username@domain

EAP-PEAP-Phase2-Method=MSCHAPV2

EAP-PEAP-Password=your_password



## uni specific set up
[Security]

EAP-Method=PEAP
EAP-Identity=cole.sumner23@my.northampton.ac.uk
EAP-PEAP-Phase2-Method=MSCHAPV2
EAP-PEAP-Password=SuperBowl@52