```sudo su
echo thinkpad_acpi > /etc/modules-load.d/thinkpad_acpi.conf
echo "options thinkpad_acpi force_load=1" > /etc/modprobe.d/thinkpad_acpi.conf 
update-initramfs -u
reboot```
