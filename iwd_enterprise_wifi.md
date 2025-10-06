# create enterprise WiFi for iwd

sudo mkdir -p /var/lib/iwd

sudo nvim /var/lib/iwd/YourSSID.8021x
---


[Security]

EAP-Method=PEAP

EAP-Identity=your_username@domain

EAP-PEAP-Phase2-Method=MSCHAPV2

EAP-PEAP-Password=your_password