# chromebook_ansible_prep

Set up Arch Linux live environment to work with ansible:
1. Set correct keymap:
   # loadkeys <keymap>

2. Connect to wifi:
   # iwctl station wlan0 connect <ssid>

3. Set root password
   # passwd

4. Start sshd
   # systemctl start sshd

5. Allow root ssh login
